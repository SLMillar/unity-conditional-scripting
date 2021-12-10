In C#, you can use if/else statements to check conditions:

```
if (condition-1)
{
  // Code to run if condition-1 is True
} 
else if (condition-2) 
{
  // Code to run if condition-1 is False and condition-2 is True
} 
else
{
  // Code to run if condition-1 and condition-2 are both False
}
```
 
You can use comparison operators to compare variables, numbers, and strings: `<`, `>`, `==`.

You can join conditions together using **Boolean AND** `&&` and **Boolean OR** `||`.

Example:

if(transform.position.x < minPosition || transform.position.x > maxPosition)
{
    transform.Rotate(0, 180, 0); // Turn around
}

![An animated gif of a car in Game view turning 180 degrees when it reaches the min OR max position.](images/car-patrol.gif)
