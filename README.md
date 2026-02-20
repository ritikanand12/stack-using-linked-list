Stack Implementation Using Linked List in C (Peek Operation)

This project demonstrates how to implement a Stack using a Singly Linked List in C programming language and how to display the top element (Peek operation).

📌 Description

In this program:

A stack is implemented using a linked list.

Elements are inserted using the push() function.

The top element is displayed using the peek() function.

The stack follows LIFO (Last In, First Out) principle.

🧠 What is a Stack?

A Stack is a linear data structure that follows:

LIFO – Last In, First Out

Basic operations of stack:

Push → Insert element

Pop → Remove element

Peek (Top) → Display top element

IsEmpty → Check if stack is empty

📂 Data Structure Used
struct Node {
    int data;
    struct Node *next;
};

Each node contains:

data → Value stored in stack

next → Pointer to next node

The top pointer always points to the latest inserted element.

🔹 Functions
push(int value)

Allocates memory for new node.

Inserts node at the beginning.

Updates top.

peek()

Displays the top element of the stack.

Prints message if stack is empty.

▶️ Operations Performed in main()
push(10);
push(20);
push(30);
peek();
Stack Representation:
Top
 ↓
30
20
10
▶️ Sample Output
Top element = 30
⚙️ How to Compile and Run
1️⃣ Compile
gcc stack_linkedlist.c -o stack_linkedlist
2️⃣ Run
./stack_linkedlist
⏱️ Time & Space Complexity

Push: O(1)

Peek: O(1)

Space Complexity: O(n)

Where:

n = Number of elements in stack

📚 Concepts Covered

Stack Data Structure

Linked List

Dynamic Memory Allocation

LIFO Principle

Peek Operation

⚠️ Limitations

No pop() function included (can be added).

Memory is not freed using free().

👨‍💻 Author

Ritik Chauhan

If you want, I can also provide:

Full Stack implementation (Push, Pop, Peek, Display)

Menu-driven stack program

Stack using array version for comparison
