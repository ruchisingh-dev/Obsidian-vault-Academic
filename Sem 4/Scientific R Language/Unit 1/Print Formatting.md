R uses the `print()` function to display the variables.

```r
x<-10
print(x)
```

R uses the `paste()` and `paste0()` functions to format strings and variables together for printing in few different ways.

```r
print(paste("hello", "world")) # hello world
print(paste("hello", "world", sep="-")) # hello-world
print(paste0("hello","world")) # helloworld
```