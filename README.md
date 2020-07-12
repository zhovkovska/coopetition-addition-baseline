# Addition coopetition baseline

This repository will help you get started with coopetitions. The task is to modify the `solution.py`, so it stores the sum of two columns in a separate `data.predict` file into an output directory. 

## Metrics

Your solution will be evaluated by Mean Absolute Error metric:
``` 
from sklearn.metrics import mean_absolute_error
def scorer(solution, prediction):
    return mean_absolute_error(solution, prediction) 
```
It should give result as low as possible (absolute minimum is equal to zero).