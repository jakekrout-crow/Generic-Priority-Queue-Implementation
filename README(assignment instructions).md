# Assignment: Generic Priority Queue Implementation

## Introduction

In this assignment, you will implement a generic priority queue that can work with various data types using custom comparator functions. This implementation will demonstrate your understanding of generic programming concepts and priority queue operations while providing practical experience with handling different data types and comparison logic.

### Starter Files

Please complete this assignment in the Jupyter Notebook.

## Learning Outcomes

By the end of this activity, you'll be able to:

1. Implement a generic priority queue that handles any data type
2. Create custom comparator functions for complex data types
3. Apply proper error handling and type checking in generic implementations
4. Design and execute comprehensive test cases for data structures

## Instructions

**Implement a `GenericPriorityQueue` class with the following methods:**

- `__init__(comparator)`: Initialize the queue with a custom comparator function
- `enqueue(item)`: Add an item to the queue
- `dequeue()`: Remove and return the highest priority item
- `peek()`: View the highest priority item without removing it
- `is_empty()`: Check if the queue is empty
- `size()`: Return the number of items in the queue

**Create two complex data types with their respective comparator functions:**

- `Task` class with attributes: priority (int), deadline (datetime), description (str)
- `Patient` class with attributes: severity (int), wait_time (int), name (str)

**Implement comparator functions that:**

- Order Tasks by priority (higher first) and then by deadline (earlier first)
- Order Patients by severity (higher first) and then by wait time (longer first)

**Include proper error handling for:**

- Invalid comparator functions
- Incompatible data types
- Empty queue operations

**Write comprehensive test cases that verify:**

- Correct ordering of different data types
- Proper error handling
- Edge cases (empty queue, single item, multiple items with same priority)

## Testing Requirements

Your implementation should pass the following test scenarios:

**Basic Operations:**

- Create priority queues with different comparator functions
- Enqueue multiple items and verify order
- Dequeue items and confirm priority ordering
- Test peek operation

**Complex Data Types:**

- Create and order Task objects
- Create and order Patient objects
- Mix different data types (should raise appropriate errors)

**Error Handling:**

- Invalid comparator function
- Dequeue from empty queue
- Incompatible data type insertion

**Edge Cases:**

- Empty queue operations
- Single item operations
- Multiple items with same priority
- Large number of items

## Evaluation Criteria

Your implementation will be evaluated based on:

**Correctness (40%)**

- Proper implementation of priority queue operations
- Correct ordering based on comparator functions
- Appropriate error handling

**Design (30%)**

- Clean and maintainable code structure
- Effective use of generic programming concepts
- Proper type hints and documentation

**Testing (30%)**

- Comprehensive test cases
- Coverage of edge cases
- Clear test documentation

## Conclusion

This assignment challenges you to implement a flexible and robust generic priority queue that can handle different data types and custom ordering logic. Through this implementation, you'll gain practical experience with generic programming, comparator functions, and proper error handling in data structures.
