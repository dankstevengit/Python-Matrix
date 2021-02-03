# Python-Matrix
Implementation of the task of compiling a matrix with the distribution of specified variables
The credit matrix is a square table of N rows and N columns, in which each element A [i,j] must be equal to the size of the loan taken by the i-th company from the j-th bank. It is known for certain that the size of any loan is an integer from 0 to 100.

# Initial data
The first line contains an integer N (2 ≤ N ≤ 100). The second line contains N integers SR[i] (0 ≤ SR[i] ≤ 32000), which will be loans taken by the companies. The third line contains N integers SC [j] (0 ≤ SC [j] ≤ 32000), which will be loans given by the banks. The sum of all SR[i] is equal to the sum of all SC[j]. 

# Result
If the credit matrix cannot be filled, "NO" will be displayed. Otherwise, "YES" will be displayed in the first line, and in each of the next N lines, N corresponding elements A[i,j] of the credit matrix will be displayed separated by spaces. If the problem has several solutions, any of them will be displayed.
