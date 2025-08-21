# Experiment-1
##  Write programs in Python Language to demonstrate the working of
followingconstructs with possible test cases: a) do…while b) while…do c)
if …else d) switch e) for

## a) Aim
To write python programs for do…while, while, for, switch and if…else and test with possible test
cases.

## Algorithm
1.	Start the program.
2. Create separate files for each given program.
3. Write simple program for each construct.
4. Test the program with possible test cases.
5. Stop the program. 

## Program
## a) do while:
```
def display():
    start = input("Enter a positive value for START: ")
    end = input("Enter a positive value for END: ")

    if start.isnumeric() and end.isnumeric():
        start = int(start)
        end = int(end)

        while True:
            print(start, end=' ')  # Corrected quote

            if start < end:
                start += 1
            else:
                break
    else:
        print("Enter a valid positive number.")

display()
```
## Output
<img width="577" height="81" alt="Screenshot 2025-08-21 153546" src="https://github.com/user-attachments/assets/e20c1879-4ca8-41a1-a4b4-d6debf567d74" />
## b) while do:
```
start = input("Enter a positive value for START: ") 
end = input("Enter a positive value for END: ") 

if start.isnumeric() and end.isnumeric():
    start = int(start)
    end = int(end)

    while start < end:
        print(start)
        start += 1
else:
    print("Enter a valid positive number.")
```
## Output
<img width="850" height="169" alt="Screenshot 2025-08-21 153800" src="https://github.com/user-attachments/assets/078f8560-0f80-4c2a-969b-6ce9eca8eb5b" />
## c)if else:
```
def compare():
    a = input("Enter a value for A: ")
    b = input("Enter a value for B: ")
    
    try:
        a = int(a)
        b = int(b)

        if a > b:
            print("A is greater than B")
        elif a < b:
            print("B is greater than A")
        else:
            print("A is equal to B")
    
    except ValueError:
        print("Enter a valid number.")

compare()
```
## Output
<img width="868" height="80" alt="Screenshot 2025-08-21 154202" src="https://github.com/user-attachments/assets/92bece5b-1f57-4919-8cc0-29ec3918c548" />

## d)switch:
```
def switch():
    switcher = {
        0: "even",
        1: "odd"
    }

    n = input("Enter a value for N: ")
    try:
        n = int(n)
        print(switcher[n % 2])
    except ValueError:
        print("Enter a valid number.")

switch()
```
## Output
<img width="859" height="67" alt="image" src="https://github.com/user-attachments/assets/13acb70f-b178-4d47-a193-53d9b5377fc2" />
## e)for:
```
def iterate():
    string = input("Enter a string: ")  
    for i in string:
        print(ord(i), end=" ")

iterate()
```
## Output
<img width="864" height="62" alt="image" src="https://github.com/user-attachments/assets/a427f5ed-bd6b-47b3-a81c-45d9f48c4fb2" />

## Result
Thus, the python program to demonstrate the working of given constructs is implemented and the output is verified successfully.



