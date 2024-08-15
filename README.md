# Pattern_printing

# 1. Square

    1. Initialization: The variables n and i are initialized. n is set to 6, indicating that the square will have 6 rows and 6 columns. i starts at 1 and will be used to control the number of rows.

    2. Outer Loop: The first loop runs as long as i is less than or equal to n. For each iteration of this loop, the program will generate one row of stars. After completing a row, the loop increments i by 1 and moves on to the next row.

    3. Inner Loop: Inside the outer loop, a second loop starts, which is controlled by the variable j. This loop runs as long as j is less than or equal to n, meaning it will execute n times for each row. During each iteration of this loop, a star (*) is printed, building the row. Once the row is complete, the loop increments j by 1 and prints the next star in the row.

    4. Newline: After the inner loop has printed a complete row of stars, the outer loop triggers a newline (endl), so that the next row begins on a new line.

    5. Completion: The process repeats until i equals n, at which point all rows have been printed, and the program ends.