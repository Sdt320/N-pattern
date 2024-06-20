# N-pattern
This program prints a pattern where an asterisk (`*`) is placed at the beginning and end of each row, and at the diagonal positions. The `if (i == j || j == 0 || j == n - 1)` condition ensures that an asterisk is printed when the row index `i` is equal to the column index `j`, or when the column index `j` is `0` (the first column) or `n - 1` (the last column).

Here's what the output looks like:

```
*    *
**   *
* *  *
*  * *
*   **
*    *
```

This pattern has asterisks forming a diagonal line from the top left to the bottom right, along with asterisks at the start and end of each row.
