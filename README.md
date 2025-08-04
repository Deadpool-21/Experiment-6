AIM : To study and implement C++ decision making statements Loops

SOFTWARE USED : VS CODE

THEORY :

Loops in C++ :

Loops allow a set of instructions to be executed repeatedly until a certain condition is met. They help simplify code, reduce redundancy, and make programs more efficient.

Types of Loops in C++:

for Loop

Purpose: Used when the number of iterations is known beforehand.

Structure: Combines three parts—initialization, condition, and update—in a single line.

Execution Flow:

Initializes the loop control variable.

Checks the condition.

Executes the loop body if the condition is true.

Updates the control variable and repeats.

Use Cases: Iterating through arrays, printing patterns, performing fixed number of calculations.

while Loop

Purpose: Used when the number of iterations is not known in advance.

Structure: The condition is checked before entering the loop.

Execution Flow:

Checks the condition.

If true, executes the loop body.

Repeats the process until the condition becomes false.

Use Cases: Reading data until a certain input is entered, waiting for a condition to be met.

do-while Loop

Purpose: Ensures that the loop body is executed at least once.

Structure: The condition is checked after executing the loop body.

Execution Flow:

Executes the loop body.

Then checks the condition.

If the condition is true, repeats the loop.

Use Cases: Menus, user-driven programs, input validation (where at least one attempt is needed).

ALGORITHM :

Algorithm for Password Checker
Algorithm:

Start.

Declare password, input, attempts = 0, and max = 3.

Prompt the user to set the password and store it in password.

Display confirmation message.

Repeat while attempts < max:

Ask the user to enter password.

If input == password:

Display success message.

Exit the program.

Else:

Show "Incorrect password".

Increase attempts by 1.

If attempts < max, prompt to try again.

If max attempts reached, show "Access denied".

End.

Algorithm for Number Reversal

Algorithm:

Start.

Declare num, reversed = 0.

Prompt user to enter a number and store in num.

Repeat while num != 0:

digit = num % 10 (extract last digit).

reversed = reversed * 10 + digit (append digit).

num = num / 10 (remove last digit).

Display the reversed number.

End.

Flipped Inverted Pyramid Pattern

Algorithm:

Input the number of rows n.

Loop from i = 0 to n - 1:

Print i spaces.

Print n - i stars (*), each followed by a space.

Move to the next line.

Flipped Pyramid Pattern

Algorithm:

Input the number of rows n.

Loop from i = 1 to n:

Print n - i spaces.

Print i stars (*), each followed by a space.

Move to the next line.

Floyd’s Triangle Pattern

Algorithm:

Input the number of rows n.

Initialize a variable num = 1.

Loop from i = 1 to n:

Loop from j = 1 to i:

Print the current value of num.

Increment num.

Move to the next line.

Hourglass Pattern

Algorithm:

Input the number of rows n.
Top Half:

Loop from i = n to 1:

Print n - i spaces.

Print i stars (*), each followed by a space.

Move to next line.

Bottom Half:

Loop from i = 2 to n:

Print n - i spaces.

Print i stars (*), each followed by a space.

Move to next line.

Pyramid Pattern

Algorithm:

Input the number of rows n.

Loop from i = 1 to n:

Print n - i spaces.

Print i stars (*), each followed by a space.

Move to the next line.
