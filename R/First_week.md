[TOC]

## R Objects and Attributes

### Objects

The five basic or "atomic" classes of objects:

- character
- numeric
- complex
- logical
- integer

The most basic object is *vector*

- A vector can only contain objects of same class
- Empty vector can be created with the `vector()`function

### Numbers 

- If you explicitly want an integer, you need to specify the `L` suffix
- There is a special **number** `Inf`  which represents **infinity**
- The value `NaN` represents an undefined value("**not a number**"), it can also be thought of as a **missing value**

### Attributes

R objects can have attributes:

- names, dimnames
- dimensions(e.g. matrices, arrays)
- class
- lengh
- other user-defined attributes/metadata

Attributes of an object can be accessed using the `attributes()` function



## Data Types - Vectors and Lists

### Creating Vectors

- Using the  `c()` function
- Using the `vector()` function

### Explicit Coercion

Objects can be explicitly coerced from one class to another using the `as.*` functions, if available.
