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

## List
- can contain diff elements of diff data types
```
mylist = list(1L, 5.678, c("Hello"))
```

## Matrix
- R objects in which elements are arranged in a 2D rectangular layout

```
matrix(data, nrow, ncol, byrow, dimnames)
```
```
matrix(c(5:29), 5, 5)
```

## Arrays
- store data in more than 2 dimensions.

```
array(data, dim, dimnames)
array(c(0:15), dim=c(4,4, 2,2))
```

## Data Frame
-  2D array like structure, store data in ordered manner(tabel/excel like format).

```
sno= c(1:5)
name= c("A","B","C","D","E")
marks= c(99,98,75,80,60)
data.frame(sno,name,marks)

data.frame(airquality)
```
