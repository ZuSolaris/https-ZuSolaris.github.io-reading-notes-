
# Stack and Queues Basic Terminology

The lesson for today will be about the Stacks and Queues data structures.


## Introduction

So Stacks and Queues are relatively similar to linked list in their construction.

Today we will be going over Stacks and Queues. We will start with Stacks.

# Stacks and Pancakes

So the best way to visualise a stack is like a stack of pancakes. When you eat a stack of pancakes you don't eat from the middle of the stack, you start from the ends (if you eat like a normal person atleast.)


<img src="https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-10/resources/images/stack1.PNG" alt="Life Cycle" width="400"/>

## FILO and LIFO

Using pancake stack terms we can now bring up the concepts of how nodes travel within a stack.

### FILO

This is first in Last Out, meaning that the first item you put on a stack will be the last on top.

### LIFO

Last In First Out

This means the last item in the stack will be the first to go.

Using pancake terminology it makes sense. Who eats a pancake from the bottom?

# How to navigate the almighty stack

When you are at the opening of a stack we call that the top and the subsequent part of the stock is usually set as top.next. The parts of the stacks are called nodes. 

### Adding to the stack.

We add things to the stack by using the PUSH method.

 ALOGORITHM push(value)
// INPUT <-- value to add, wrapped in Node internally
// OUTPUT <-- none
   node = new Node(value)
   node.next <-- Top
   top <-- Node



### Removing from the stack.

We use Pop to remove nodes from the stack.

ALGORITHM pop()
// INPUT <-- No input
// OUTPUT <-- value of top Node in stack
// EXCEPTION if stack is empty

   Node temp <-- top
   top <-- top.next
   temp.next <-- null
   return temp.value

# Queues not Qs

Queues work like stacks except they are horizontal, like a line of people!


<img src="https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-10/resources/images/Queue.PNG" alt="Life Cycle" width="400"/>

## FIFO
First In First Out

This means that the first item in the queue will be the first item out of the queue.

## LILO
Last In Last Out

This means that the last item in the queue will be the last item out of the queue.

## Adding and removing from a queue

You wouldn't just jump in the middle of a line, and you definitely wouldn't jump into the front.

### Enqueue

This is the method used to add a node onto a queue, these can only be appended in the rear like a line full of people.

### Dequeue

This is what is used to remove a node from a queue and it always has to be the removed from the front like a line of people.


