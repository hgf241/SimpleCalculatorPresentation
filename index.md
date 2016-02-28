---
title       : A Simple Calculator
subtitle    : An example of reactive calculation
author      : Heiko Geiﬂler 
job         : 
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides


---

## Purpose Of The App

- The app should show some possibilies of the shiny.
- The formula for the numbers and operators will be shown below the input fields.
- In this formula will show some (actual unnecessary) paranthesises for better readability.
- Also the result of the calculation will be shown.



---

## Operators

- There are the basic operation '+', '-', '*' and '/' in this calculator
- You can input 3 numbers. All numbers have to be present.
- The paranthesis are not part of this example app. 
- The '*' and '/' will be evaluate first.

```r
   3+4*3
```

```
## [1] 15
```
- A division by zero will result in a zero not in an exception


--- .class #id 

## Additional Operations

- You can apply some additional operations.
- These are "square", "square root", "cube" and "cube root".
- The roots will be shown as exponentiation. for example the "cube root" will be shown as 

```r
  2^(1/3)
```

```
## [1] 1.259921
```
- These operators will be calculate before the normal operators.


---

## Special Operations

- Here are another sample for operations.
- These are "round", "DIV" and "MOD".
- All of these operations need an additional value as input.
- This value can be choosen in the field jus right beside the special operations.
- In the formula, the "DIV" and "MOD" will be shown in the R style:

```r
  # DIV
  5 %% 3
```

```
## [1] 2
```

```r
  # MOD
  5 %/% 3
```

```
## [1] 1
```
