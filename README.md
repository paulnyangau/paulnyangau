# Importing the data into R
library(readr)
data <- read_csv("C:/Users/pnyangau/Downloads/archive/data.csv")
View(data)

# Declaring file path
file_path <- 'C:/Users/pnyangau/Downloads/archive/data.csv'
df <- read.csv(file_path)

df = pd.read_csv("C:/Users/pnyangau/Downloads/archive/data.csv")

# Display the first few rows of the dataset to inspect the data
head(df)

# Calculate and present descriptive statistics
descriptive_stats <- summary(df)

# Display the descriptive statistics
print(descriptive_stats)

# Check for missing values
missing_values <- colSums(is.na(df))
