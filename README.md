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
~~~
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
~~~
## Output
<img width="577" height="81" alt="Screenshot 2025-08-21 153546" src="https://github.com/user-attachments/assets/9abf8bb3-ffe9-49ee-b2ad-87f95362a403" />


## b) while do:
~~~
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
~~~
## Output
<img width="850" height="169" alt="Screenshot 2025-08-21 153800" src="https://github.com/user-attachments/assets/c1b55536-d1e4-494a-9485-5b17e0845889" />


## c)if else:
~~~
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
~~~
## Output
<img width="868" height="80" alt="Screenshot 2025-08-21 154202" src="https://github.com/user-attachments/assets/656dbd53-6c68-4179-819c-79583521878d" />


## d)switch:
~~~
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
~~~
## Output
<img width="859" height="67" alt="Screenshot 2025-08-21 154400" src="https://github.com/user-attachments/assets/c1d9c21a-ac43-4a4f-8e1f-2f5dede61402" />

## e)for:
~~~
def iterate():
    string = input("Enter a string: ")  
    for i in string:
        print(ord(i), end=" ")

iterate()
~~~
## Output
<img width="864" height="62" alt="Screenshot 2025-08-21 154530" src="https://github.com/user-attachments/assets/3e1e2c22-f129-4e9f-b726-14acaf7ff3db" />

## Result
Thus, the python program to demonstrate the working of given constructs is implemented and the output is verified successfully.



