# Monty-Hall
Simulation of the very popular Monty Hall Problem using Python
## Steps Followed:
1. Create an list of lists with A,B,C repeated N times.
2. From this list, randomly pick one door which we assume contains the car and create a list.
3. Using set operations generate a list of lists of doors which contain goats.
4. User selection will be a list of randomly selected doors from list created in step 1.
5. Using set operations generate a list of lists of doors which were not selected by the User.
6. Using set operations (intersection) select (one) door which is common in list generated in step 5 and 3.This is the door opened by the presenter.
7. Create two branches here. One where user switches and one where he does not:
  a. Perform switch operation by performing un-intersect of step 5 and 6. Compare this list to list created in step 2 and get match %. This is the winning percentage.
  
  b. Perform no operation and compare original user selection with list created in step 2 and get match %. This is the winning percentage.
8. Compare the winning % in both the cases. Make observation on switch vs no switch.
