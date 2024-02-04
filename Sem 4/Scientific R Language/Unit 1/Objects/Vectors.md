In R, Vectors are fundamental data structures used to store ordered collections of elements. They can contain elements of the same data type, such as numeric, character, logical, or complex values.
## Creating Vectors
- Use the `c()` function to concatenate elements and create a vector.
```r
# Numeric vector 
numeric_vector <- c(1, 2, 3, 4, 5) 
# Character vector
character_vector <- c("apple", "banana", "orange")
# Logical vector
logical_vector <- c(TRUE, FALSE, TRUE)
```

## Accessing Elements
- Use square brackets `[ ]` with numeric indices to access specific elements of a vector.
- Indices start at 1 in R.
```r
# Accessing elements 
first_element <- numeric_vector[1] # Access the first element 
third_element <- character_vector[3] # Access the third element
```

## Vector Functions
- R provides several functions for vector manipulation and analysis.
- Common functions include `length()`, `sum()`, `mean()`, `min()`, `max()`, `sort()`, `rev()`, etc.
```r
# Vector functions 
vector <- c(3, 1, 2, 5, 4)
vector_length <- length(vector)
vector_sum <- sum(vector)
vector_mean <- mean(vector) 
vector_min <- min(vector)
vector_max <- max(vector)
sorted_vector <- sort(vector)
```