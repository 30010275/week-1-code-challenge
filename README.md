# we
//Grade Assignment:

Uses a series of else if conditions to determine the grade based on the range the input falls into:
Grade A: Marks greater than 79.
Grade B: Marks between 60 and 79 (inclusive).
Displays the corresponding grade using console.log()



//Net sallary calculations

input:
we use Prompts the user to enter their basicSalary and benefits.
Converts the input to floating-point numbers using parseFloat() to allow decimal values.

input validation
Ensures both inputs are valid numbers.
If either basicSalary or benefits is invalid, the function stops execution and prints an error message

Calculations:

Gross Salary: Sum of basic salary and benefits.
Tax: Calculated based on the KRA tax brackets:
10% for salaries ≤ 24,000.
25% for salaries between 24,001 and 32,333.


//speed detector
user input
we use Prompts so the user to enter the car’s speed.
Converts the input from a string to a number using Number(). This ensures numeric operations can be performed on the input.

Const
limit: The speed limit, set at 70 km/h.
kmPerPoint: Specifies the number of kilometers per hour over the limit that results in one demerit point

//speed exceed limit

If the car's speed exceeds the limit:
Calculates the demerit points by subtracting the speed limit from the car’s speed, dividing by kmPerPoint (5), and using Math.floor() to round down to the nearest integer.
