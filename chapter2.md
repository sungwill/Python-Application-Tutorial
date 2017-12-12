---
title       : Physics Application
description : Insert the chapter description here

--- type:NormalExercise lang:python xp:100 skills:2 key:5ef0ed3dfd
## Gravitational Force


*** =instructions
Jack is now standing at an altitude anywhere on Earth, where gravitational force is not 9.81 m/s^2. Please create a function called gForce that takes an integer, height, in its parameter. Then, use the equation (G * m * M) / height^2 to return the value of g.

G = 6.674 * 10^-11

m = 8

M = 5.972 * 10^24

g = (G * m * M) / height^2

*** =hint

*** =pre_exercise_code
```{python}

```

*** =sample_code
```{python}
def gForce(height):
    G = ___
    m = 8
    M = ___
    g = ___
    return g
```

*** =solution
```{python}
def gForce(height):
    G = 6.674 * math.pow(10, -11)
    m = 8
    M = 5.972 * math.pow(10, 24)
    g = (G * m * M) / math.pow(height, 2)
    return g
```

*** =sct
```{python}
##test_object("G")
test_object("G",
            eq_condition="equal",
            do_eval=True,
            undefined_msg = "Don't remove the predefined `G` object.",
            incorrect_msg = "Invalid value for 'G', please check again.")
success_msg("Great work!")
```


--- type:NormalExercise lang:python xp:100 skills:2 key:c6434d6e6b
## Pendulum Time Period


*** =instructions
While at the same location, Jack happens to have a pendulum in his pocket, so he wants to measure the time needed for the pendulum to complete 1 period. Please create a function called timePeriod that takes in 2 parameters: an integer length and an integer height. Then, use the equation 2 * π * sqrt of length / gravitational force to return the value of the time period. Call the gForce function to find the gravitational force.

*** =hint

*** =pre_exercise_code
```{python}

```

*** =sample_code
```{python}

```

*** =solution
```{python}

```

*** =sct
```{python}

```
