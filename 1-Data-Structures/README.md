<h1 align="center">Data Structures</h1>

### Definition

Imagine you have a bunch of different things you need to organize and store. These things could be numbers, words, or any type of information. Now, you want to store them in a way that makes it easy to find, retrieve, and manipulate them whenever you need.

Data structures are like containers or organized formats that help you store and manage these pieces of information efficiently. They provide a way to organize and store data so that you can perform operations on them effectively.

### Importance

We deal with lots of information. Data structures are like the organizational system for this information. They help us store and manage data efficiently so that we can retrieve, update, and use it easily. They make it easier for developers to handle data, leading to more efficient and effective software.

They show importance in organization, efficiency, accessibility, speed, and memory usage.

#

### Classification of Data Structures

```
Data Structure
 ├── Basic Data Structure
 │    ├── Basic Data Type
 │    │    ├── Simple Type
 │    │    │    ├── Integer Type
 │    │    │    ├── Real Number Type
 │    │    │    ├── Character Type
 │    │    │    ├── Logical Type
 │    │    │    ├── Enumeration Type
 │    │    │    └── Partial Type
 │    │    │
 │    │    └── Pointer Type
 │    │
 │    ├── Structure Type
 │    │    ├── Array Type
 │    │    └── Record Type
 │    │
 │    └── Abstract Data Type
 │
 └── Problem-Oriented Data Structure
      ├── List Structure
      ├── Stack
      ├── Queue
      ├── Tree Structure
      └── Hash
```

### Definition of Terms:
- **Data Structure**: A way of organizing and storing data so that it can be efficiently used and accessed.
    - **Basic Data Structure**: The fundamental building blocks for organizing and storing data.
        - **Basic Data Type**: The most basic kinds of data, like numbers or characters, that a programming language can work with.
            - **Simple Type**: Basic data types that store individual values directly.
                - **Integer Type**: Stores whole numbers (integers).
                - **Real Number Type**: Stores numbers with decimal points (floating-point numbers).
                - **Character Type**: Stores individual characters (letters, numbers, symbols).
                - **Logical Type**: Stores boolean values (true or false).
                - **Enumeration Type**: A set of named constant values.
                - **Partial Type**: Represents a subset of values from another type.
            - **Pointer Type**: Stores memory addresses, pointing to the location of another piece of data.
        - **Structure Type**: Combining basic data types to create more complex structures.
            - **Array Type**: An ordered collection of elements of the same type.
            - **Record Type**: A collection of fields, each with its own data type.
        - **Abstract Data Type**: A high-level description of how a data structure should behave without specifying its implementation.
    - **Problem-Oriented Data Structure**: Data structures designed to solve specific types of problems.
        - **List Structure**: An ordered collection of elements.
        - **Stack**: A collection of elements with last-in, first-out (LIFO) access.
        - **Queue**: A collection of elements with first-in, first-out (FIFO) access.
        - **Tree Structure**: A hierarchical structure with nodes connected by edges.
        - **Hash**: A structure that maps data to a fixed-size array for quick access.

#


### Categories of Data Structures

```
Categories
 ├── Primitive Data Structure
 │    ├── Integer
 │    ├── Char
 │    ├── Real
 │    └── Boolean
 │
 ├── Simple Data Structure
 │    ├── Array
 │    ├── String
 │    └── Record
 │
 └── Complex Data Structure
      ├── Compound Data Structure
      │    ├── Linear
      │    │    ├── List
      │    │    ├── Stack
      │    │    └── Queue
      │    │
      │    └── Non-Linear
      │         ├── Binary
      │         │    ├── Binary Tree
      │         │    ├── Binary Search Tree
      │         │    └── AVL Tree
      │         │
      │         └── N-Ary
      │              ├── Graph
      │              ├── General Tree
      │              ├── M-Way Search Tree
      │              ├── Heap
      │              └── B-Tree
      │
      └── File Organization
           ├── Sequential
           ├── Relative
           ├── Indexed Sequential
           └── Multi-Key
```

### Definition of Terms:
- **Primitive Data Structure**: Basic building blocks of data.
    - **Integer**: Whole numbers without decimal points.
    - **Char**: Single characters like letters or symbols.
    - **Real**: Numbers with decimal points.
    - **Boolean**: Represents true or false values.
- **Simple Data Structure**: More complex than primitives, used to store and organize data.
    - **Array**: A collection of elements, each identified by an index or a key.
    - **String**: A sequence of characters.
    - **Record**: A collection of different data elements grouped together.
- **Complex Data Structure**: Structures made up of simpler data structures.
    - **Compound Data Structure**: Combinations of simple and primitive types.
        - **Linear**: Organized in a linear (sequential) manner.
            - **List**: A collection of elements with a linear order.
            - **Stack**: A collection with Last In, First Out (LIFO) access.
            - **Queue**: A collection with First In, First Out (FIFO) access.
        - **Non-Linear**: Not organized in a linear manner.
            - **Binary**: Structures based on a binary relationship.
                - **Binary Tree**: A tree structure with each node having at most two children.
                - **Binary Search Tree**: A binary tree with specific ordering properties.
                - **AVL Tree**: A self-balancing binary search tree.
            - **N-Ary**: Structures with multiple branches.
                - **Graph**: A network of nodes connected by edges.
                - **General Tree**: A tree structure with nodes having any number of children.
                - **M-Way Search Tree**: A tree structure used for searching.
                - **Heap**: A specialized tree-based data structure.
                - **B-Tree**: A self-balancing tree structure.
    - **File Organization**: How data is arranged in files.
        - **Sequential**: Data stored in a sequence.
        - **Relative**: Data referenced by a record number.
        - **Indexed Sequential**: A combination of sequential and indexed access.
        - **Multi-Key**: Multiple keys used for organizing data.
#

<br/>

| Characteristic of Data Structure | Description |
|:- |:-|
| Linear | Data elements are arranged in a sequential order, much like a line. ```Ex. Array, Linked List, Stack, Queue ```
| Non-Linear | Data elements are not arranged in a sequential order; they have a more complex structure. ```Ex. Tree, Graph```
| Homogenous | All elements in the structure are of the same type. ```Ex. Array```
| Non-Homogenous | Elements in the structure can be of different types. ```Ex. Structures, Records```
| Static | The size of the data structure is fixed and does not change during program execution. ```Examples: Array```
| Dynamic | The size of the data structure can change during program execution. ```Examples: Linked List created using pointers``` 

<br/>

| Type of Data Structure | Description |
|:- |:-| 
| Array | An array is like a list or a **sequence of items**. These items can be numbers, words, or anything else. The key feature is that they're arranged in a specific order, and each item can be accessed using its position in the list.
| Linked List | A linked list is another way to organize a sequence of items, but instead of being stored in one block of memory like an array, each item (node) in a linked list has a reference to the next item in the sequence. It's like a **chain** of connected elements.
| Queue | A queue is like a **line** of people waiting for something. The first person who arrives is the first to get served, and new people join at the back. Similarly, in a programming context, a queue is a data structure where the first item added is the first one to be removed, following the First In, First Out (FIFO) principle.
| Stack | Imagine a **stack** of plates. You add a plate to the top and remove the top plate when you need one. In computing, a stack is a data structure that follows the Last In, First Out (LIFO) principle. The last item added is the first one to be removed.
| Graph | A graph is **like a map** that shows how different things are connected. In the world of computers, a graph is a way to represent relationships between various items. These items are called "nodes," and the connections between them are called "edges." Imagine nodes as points on the map and edges as the paths or roads that connect these points. It helps to understand how things are related or linked to each other.
| Tree | A tree is **like a family tree**. At the top, you have one person (or node), called the "root." This person has children, and each child can have more children, forming branches. A tree is a way to organize data in a hierarchical structure. The "root" is the starting point, and each "child" node can have its own set of "children," creating a branching structure. It's useful for representing relationships or organizing information in a hierarchy.
| Tries | A trie, also known as a **keyword tree**, is a tree-like structure used to store a dynamic set of strings, where the keys are usually sequences, such as strings of characters. The word "trie" comes from the word "retrieval," and it's pronounced like "try."
| Hash Table | A hash table, also known as a **hash map**, is a structural arrangement that enables effective retrieval and storage of data through the utilization of a process called hashing. Think of a hash table as a giant index for a book. You have a key (like a word) and a value (like the page number). It's a way to quickly find information based on a unique identifier. 

<br/>


