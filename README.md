# weekdayselect

Sure, let's dry run the provided program step by step:

1. The program starts by declaring a `main` method.
2. Inside the `main` method, it creates a `Scanner` object named `sc` to take input from the user.
3. It also declares a boolean variable `continueloop` and initializes it to `true`.
4. The program enters a `while` loop that continues as long as `continueloop` is `true`.
5. Inside the loop, it declares an integer variable `day`.
6. It prints the message "Choose a day number from 1 - 7: " to prompt the user.
7. It reads an integer input from the user using the `nextInt()` method of the `Scanner` object and assigns it to the `day` variable.
8. It enters a `switch` statement based on the value of the `day` variable.
9. Depending on the value of `day`, it executes the corresponding `case` block:
   - If `day` is 1, it prints "Monday".
   - If `day` is 2, it prints "Tuesday".
   - If `day` is 3, it prints "Wednesday".
   - If `day` is 4, it prints "Thursday".
   - If `day` is 5, it prints "Friday".
   - If `day` is 6, it prints "Saturday".
   - If `day` is 7, it prints "Sunday".
   - If `day` is 0, it sets `continueloop` to `false`, which will exit the loop.
   - If none of the above cases match, it prints "Enter Valid Number".
10. After the `switch` statement, the program continues to the next iteration of the loop or exits the loop if `continueloop` is `false`.
11. After the loop, it prints "Program exited!!!...".
12. It closes the `Scanner` using the `close()` method to release resources.

The purpose of the program is to prompt the user to input a number representing a day of the week (1 to 7) and then display the corresponding day name. The loop continues until the user enters 0, at which point the program exits.
