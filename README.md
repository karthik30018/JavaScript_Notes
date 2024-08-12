# Day 1
## Video 1
"Everything in javascript happens inside an **Execution context**".

"Javascript is **Synchronous Single threaded language**".

![image](https://github.com/user-attachments/assets/e7a7b4dc-f5fe-4fb1-b544-1a0be59a2a3d)

### Memory Component(Variable environment)
Memory to store variable and functions.

### Code Component(Thread of execution)

- Whole code is executed, one line at a time.
- Synchronous Single Threaded - Only exexutes one line at a time in a specific order.

## Video 2

### How javascript code is executed.

- When a javascript code is executed a **execution context** is created.
- It is created in two phase
  1)Creation phase(Memeory Allocation/creation phase)
  2)Code Execution phase.

### Creation Phase or Memory allocation phase:

- When a code is executed it creates memory for the variable and function.
- By default the value for variables will be a special value **Undefined**.
- For function it stores the whole code of that function.

### Code Execution phase:

- The javascript again runs through the code line by line and executes the code.
- Assign the actual value by replacing undefined.
- **When a function is called a brand new execution context is created inside the global execution context.**
- **Return** keyword states that to return the control to the place where this function was invoked.
- After returning the value of the function **the whole execution context of that function will be deleted.**
- Once the program execution is done **the whole Global Execution Context will be deleted.**
![image](https://github.com/user-attachments/assets/e88fc30d-b508-4aa6-aeaf-9171c83fc5d2)

## Note:

- All the above process is managed by **Call Stack**.
- Used to manage execution context.
  
### Call Stack also known as 
- Execution Context stack
- Program stack
- Control stack
- Runtime stack
- Machine stack
![image](https://github.com/user-attachments/assets/6e03a74f-28f0-4e5a-a86b-1cb5e2307e31)

