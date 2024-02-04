### 1. Arithmetic Operators

Arithmetic operators are used to perform mathematical operations like addition, subtraction, multiplication, division, and exponentiation.

- Addition: `+`
- Subtraction: `-`
- Multiplication: `*`
- Division: `/`
- Exponentiation: `^`
- Modulus (Remainder): `%%`
- Integer Division: `%/%`

**Example:**
```r
x <- 10 
y <- 5 
sum <- x + y # Addition 
difference <- x - y # Subtraction 
product <- x * y # Multiplication
quotient <- x / y # Division 
remainder <- x %% y # Modulus
```
### 2. Comparison Operators

Comparison operators are used to compare values and return logical values (`TRUE` or `FALSE`).

- Equal to: `==`
- Not equal to: `!=`
- Greater than: `>`
- Less than: `<`
- Greater than or equal to: `>=`
- Less than or equal to: `<=`

**Example:**
```r
x <- 10
y <- 5 
result <- x > y # TRUE
```
### 3. Logical Operators

Logical operators are used to combine logical values or evaluate conditions.

- Logical AND: `&` or `&&`
- Logical OR: `|` or `||`
- Logical NOT: `!`
**Example:**
```r
a <- TRUE
b <- FALSE 
result <- a & b # FALSE
```

### 4. Assignment Operators

Assignment operators are used to assign values to variables.

- Leftward assignment: `<-` or `=`
- Rightward assignment: `->`
**Examples:**
```r
x <- 10
```
### 5. Miscellaneous Operators

Other miscellaneous operators in R include:

- Colon operator (`:`): Creates a sequence of numbers.
- Concatenation operator (`c()`): Combines values into a vector.
- Membership operator (`%in%`): Checks if elements are present in a vector.
- Help operator (`?`): Accesses documentation.
**Examples:**
```r
sequence <- 1:5 
vector <- c(1, 2, 3)
is_present <- 2 %in% vector
```

