# MechaCar_Statistical_Analysis

## Linear Regression to Predict MPG
- Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?

  Vehicle weight, spoiler_angle & AWD provided a non-random amount of variance. 

- Is the slope of the linear model considered to be zero? Why or why not?

  Our slope is not zero simply off of the fact that our p-value is significanlty lower than 0.05.

- Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?

  Our R-squared value is 71%, which means the model can accurately predict mpg 71% of the time. The reason it is not 100% accurate is becuase the model only captures only a few of the variables that affect the calculation and not ALL OF THEM.
  
  ## Summary Statistics on Suspension Coils,
- The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?

Lot 1 and 2 are within design specs while Lot 3 shows the most variance.


## Study Design: MechaCar vs Competition

One common feature that is always looked at when purchasing cars and comparing engines/mileage is Horsepower. We can design an experiment to compare the horsepower of the MechaCar vs the competitors. Null: the horsepower is not much different, and the Alternative being that is significantly differnt.
