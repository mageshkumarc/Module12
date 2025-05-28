# # 📚 Stack using Linked List: Check and Display Whether the Stack is Full or Not

This Python program demonstrates how to check if a stack (using `LifoQueue` from the `queue` module) is full or not. It uses the `full()` method to determine the stack's status and then displays the appropriate message.

## 🎯 Aim

To write a Python program that:
- Creates a stack with a fixed size.
- Adds elements to the stack.
- Checks if the stack is full.
- Displays a message indicating whether the stack is full or not.

## 🧠 Algorithm

1. **Import the LifoQueue class**:
   - Import `LifoQueue` from the `queue` module to create the stack.

2. **Create a Stack**:
   - Instantiate a `LifoQueue` with a maximum size (e.g., 4).

3. **Add Elements to the Stack**:
   - Add elements (e.g., 'a', 'b', and 'c') to the stack using the `put()` method.

4. **Check if the Stack is Full**:
   - Use the `full()` method of `LifoQueue` to check if the stack has reached its maximum capacity.

5. **Display the Status**:
   - Print "Stack is full" if the stack is full.
   - Otherwise, print "Stack is not full".

## 📝 Program
```
from queue import LifoQueue

stack = LifoQueue(maxsize=8)

stack.put('Snack_1')
stack.put('Snack_2')
stack.put('Snack_3')
stack.put('Snack_4')
stack.put('Snack_5')

print("Present quantity of snacks in the jar: ",stack.qsize(), end=" Snacks")
print("\nIs the jar full? ", stack.full())

print('\nAfter sales:')
print(stack.get())
print(stack.get())
print(stack.get())

print("\nIs the jar empty? ", stack.empty())
print("Current quantity of snacks in the jar: ", stack.qsize(), end=" Snacks")
```

## Sample Input & Output
![image](https://github.com/user-attachments/assets/e0b7a4d8-6cd5-4193-8f01-c65a1198f528)

## Result
Thus,the program is executed successfully
