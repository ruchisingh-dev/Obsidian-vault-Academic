Here are the special values in R programming, explained with code:

### 1. NA (Not Available)
- Represents missing data.
- Example:
```r
x <- c(1, 2, NA, 4, NA) 
is.na(x) # Check for missing values
```

### 2. NULL
- Represents the absence of any object.
- Often used to define empty vectors or lists.
- Example:
```r
y <- NULL
is.null() # TRUE
length(y) # Length of NULL is 0
```

### 3. Inf (Infinity) and -Inf (Negative Infinity)
- Result from division by zero or extremely large calculations.
- Example:
```r
10 / 0 # Inf
-5 / 0 # -Inf
is.infinite(10/0) # TRUE
```

### 4. NaN (Not a Number)
- Arises from undefined mathematical operations, like 0/0 or sqrt(-1).
- Example:
```r
0 / 0 # NaN 
is.nan(0/0) # TRUE
sqrt(-1) # NaN
```
