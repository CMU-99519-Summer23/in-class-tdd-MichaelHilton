[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=11448985&assignment_repo_type=AssignmentRepo)
# TDD-Starter

Use this code to start your Pair Programming/TDD exercise to convert roman numbers to arabic numbers. As a reminder, the rules are:

| Number | Numeral |
| --- | ----------- |
| 1	 |   I |
| 5	|    V |
| 10 |	    X |
| 50 |	    L |
| 100 |	    C |
| 500	|    D |
| 1000 |	M |

Rules:

- The 'base 1' symbols ('I', 'X', 'C', 'M') can be subtracted from the next highest 'base 5' symbol ('V', 'L', 'D') or 'base 1' symbol, but only one occurrence is allowed. The symbol cannot be prepended to a symbol that is the next decimal order higher. So 'IV', 'IX' is ok' but 'IL' or 'IC' are not. 'XL', 'XC' is valid' but XD and XM are not ('CD' and 'CM' are also valid)

- The symbols 'I' and 'X' can be repeated at most 3 times in a row when the symbol is being appended

- The 'base 5' symbols 'V', 'L' and 'D' can never be repeated