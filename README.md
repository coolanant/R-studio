# R-studio

## DataTypes
- There are 5 types in R
<br/>Vector, Matrix, Array, List, Data Frame

## Vectors
- sequence of data elements of same basic type
- There are 5 atomic vectors/ classes of vector - Logical, Integer, Numeric, Complex, Character
- To check **class** of vector -
```
class(vtr1)
```
### Logical

```
vtr1 = c(TRUE, FALSE)
```

### Numeric

```
vtr1 = c(15, 80.5, 90)
```

### Integer

```
vtr1 = c(15L, 80L)
```

### Character

```
vtr1 = c("Hello", "Boy")
```

## Matrix
- R objects in which elements are arranged in a 2D rectangular layout

```
matrix(data, nrow, ncol, byrow, dimnames)
```
