# Find probability of getting 3 Houses in OldTown in a row

Let's say we're picking houses from our dataset, and removing each one that we pick. What are the odds of picking three houses successively in OldTown without replacement in a row ?

## Write a function `cond_prob` that 
* Calculates the conditional probability of picking 3 houses successively in OldTown

## Parameters:

| Parameter | dtype | argument type | default value | description |
| --- | --- | --- | --- | --- | 
| df | DataFrame | compulsory |  | Input DataFrame |


## Returns:

| Return | dtype | description |
| --- | --- | --- | 
| conditional_prob | float | probability of picking three OldTown houses successively |
