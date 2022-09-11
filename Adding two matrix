#Program for adding two user input 'r' rows and 'c' columns matrices

def matrix_A(): #Taking the input from the user for matrix with 'r' rows and 'c' columns
    r = int(input("Enter the number of rows: "))
    c = int(input("Enter the number of columns: "))
    A = []
    for i in range(r):
        B = []
        for j in range(c):
            j = int(input(f"Enter the {i+1} row and {j+1} column element: "))
            B.append(j)
        print()
        A.append(B)
    print()
    print("The Matrix is: ") #printing the matrix
    for i in range(r):
        for j in range(c):
            print(A[i][j],end=" ")
        print()
    return A
    
def add_mat(A,B): # Defining a function for adding matrix A and matrix B

  result = [[0, 0, 0], [0, 0, 0], [0, 0, 0]]
  for i in range(len(A)):
      for j in range(len(A[0])):
          result[i][j] = A[i][j] + B[i][j]
  print(result)

    for i in range(len(result)):
        for j in range(len(result[0])):
            print(result[i][j],end=" ")
        print()
        
A = matrix_A()
B = matrix_A()


