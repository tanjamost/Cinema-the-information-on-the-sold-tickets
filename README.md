# Cinema-the-information-on-the-sold-tickets

Task from Hyperskill.

Multidimensional array.

The cinema has n rows, each row consists of m seats (n and m do not exceed 20). A two-dimensional matrix stores the information on the sold tickets: the number 1 means that the ticket for this place is already sold, and the number 0 means that the place is available. You want to buy k tickets to neighboring seats in the same row. Find whether it can be done.

Input data format:

On the input, the program gets the number of n rows and m seats. Then, there are n lines, each containing m numbers (0 or 1) separated by spaces. The last line contains the number k.

Output data format

The program should output the number of the row with k consecutive available seats. If there are several rows with k available seats, output the first row with these seats. If there is no such a row, output the number 0.

 Sample Input 1:

3 4

0 1 0 1

1 1 0 1

1 0 0 1

2

Sample Output 1:

3

Sample Input 2:

3 3

0 1 0

1 0 0

1 1 1

3

Sample Output 2:

0
