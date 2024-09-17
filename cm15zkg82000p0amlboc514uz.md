---
title: "Activity 9: Data Structure in Typescript"
datePublished: Tue Sep 17 2024 05:21:04 GMT+0000 (Coordinated Universal Time)
cuid: cm15zkg82000p0amlboc514uz
slug: activity-9-data-structure-in-typescript

---

* **Research and Study Data Structures in TypeScript:**
    
    * Understand the commonly used data structures in TypeScript and how they are implemented.
        
    * Focus on how TypeScript’s strong typing system enhances the use of data structures.
        
* **Explain Each Data Structure in TypeScript:** For each data structure, provide the following details:
    
    * **Definition:** A brief explanation of the data structure.
        
    * **Key Features:** The important characteristics and behaviors of the data structure.
        
    * **Use Cases:** Where and why this data structure is typically used.
        
    * **Time Complexity:** Analyze the performance of each data structure (Big-O notation) for common operations like insert, delete, and search.
        
    * **Example Code in TypeScript:** Provide a TypeScript code snippet demonstrating how to use each data structure.
        
* **Data Structures to Cover:**
    

* ### **Arrays**:
    
* **Definition**: Arrays store multiple elements of the same type in contiguous memory locations. In TypeScript, arrays can be strongly typed to hold only specific types.
    
    * **Key Features**:
        
        Fixed or dynamic size.
        
        Zero-based indexing.
        
    * **Use Cases**: Storing a collection of items where order is important (e.g., product lists, user data).
        
    * **Time Complexity**:
        
        Access: O(1)
        
        Insertion (at the end): O(1)
        
        Deletion (at the end): O(1)
        
        Search: O(n)
        
* **TypeScript Code**:
    
* ![](https://cdn.hashnode.com/res/hashnode/image/upload/v1726548080872/9506267d-75ac-4ef7-aa2a-58b692efe3e1.png align="center")
    
* ## **Tuple:**
    
* **Definition**: Tuples are a special kind of array where the length and types of elements are fixed. Tuples can contain multiple data types.
    
* **Key Features**:
    
    * Fixed size.
        
    * Can store mixed data types.
        
* **Use Cases**: Returning multiple values from functions, structured data like coordinates or records.
    
* **Time Complexity**: Same as arrays.
    

**TypeScript Code**:

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1726548391569/9835bd9e-7c38-4d4c-82c0-bf6b1e2ed0e3.png align="center")

## **ArrayList (Dynamic Arrays):**

* **Definition**: ArrayLists are dynamic arrays that resize themselves when needed.
    
* **Key Features**:
    
    * Dynamic resizing.
        
    * Random access.
        
* **Use Cases**: Managing lists where the size is unknown or may change frequently.
    
* **Time plexity**:**Com**
    
    * Access: O(1)
        
    * Insertion: O(1) (amortized)
        
    * Resizing: O(n)
        
        **TypeScript Code**:
        
        ![](https://cdn.hashnode.com/res/hashnode/image/upload/v1726548523086/abf5fd00-6ffc-4090-a50c-693ac6ee5817.png align="center")
        
        ## **Stack:**
        
    * **Definition**: A stack is a linear data structure following the Last In, First Out (LIFO) principle.
        
    * **Key Features**:
        
        * Push (add) and pop (remove) from the top.
            
        * Supports `push`, `pop`, and `peek`.
            
    * **Use Cases**: Undo functionality, recursive function calls, expression evaluation.
        
    * **Time Complexity**:
        
        * Insertion (push): O(1)
            
        * Deletion (pop): O(1)
            
        * Peek: O(1)
            
    * **TypeScript Code:**
        
    * ![](https://cdn.hashnode.com/res/hashnode/image/upload/v1726548792314/7022795a-4189-42c0-a2cf-338be324aa8b.png align="center")
        
        ## **Queue:**
        
        * **Definition**: A queue is a linear data structure following the First In, First Out (FIFO) principle.
            
        * **Key Features**:
            
            * Elements are added at the back and removed from the front.
                
            * Supports enqueue and dequeue
                
        * **Use Cases**: Task scheduling, managing requests in real-time systems.
            
        * **Time Complexity**:
            
            * Enqueue (add): O(1)
                
            * Dequeue (remove): O(1)
                
        
        **TypeScript Code:**
        
    * ![](https://cdn.hashnode.com/res/hashnode/image/upload/v1726549045610/287e191b-5676-4f7d-a1f3-b35dacaa2881.png align="center")
        
        ## **LinkedList:**
        
        * **Definition**: A LinkedList is a linear collection of nodes where each node holds data and a reference to the next node (or both previous and next in a doubly linked list).
            
        * **Key Features**:
            
            * Dynamic size, easy insertions and deletions.
                
            * Sequential access.
                
        * **Use Cases**: Dynamic data structures, building queues and stacks, undo operations.
            
        * **Time Complexity**:
            
            * Access: O(n)
                
            * Insertion/Deletion: O(1) if position is known.
                
        
        **TypeScript Code**:
        
    * ![](https://cdn.hashnode.com/res/hashnode/image/upload/v1726549502705/69c29e2c-2327-4554-8ee7-5c19dc495698.png align="center")
        
        ## **HashMap (or Object/Map):**
        
        * **Definition**: A HashMap (or Map) is a key-value pair data structure that allows fast lookups, insertions, and deletions.
            
        * **Key Features**:
            
            * Key-value pairs.
                
            * Fast lookups by key.
                
        * **Use Cases**: Storing user information, caching, implementing dictionaries.
            
        * **Time Complexity**:
            
            * Search: O(1)
                
            * Insertion: O(1)
                
            * Deletion: O(1)
                
        
        **TypeScript Code**:
        
    * ![](https://cdn.hashnode.com/res/hashnode/image/upload/v1726549612048/1ca66b52-934e-4d11-8344-efd68cf48a3f.png align="center")
        
        ## **Set:**
        
        * **Definition**: A `Set` in TypeScript is a collection of unique elements, meaning it cannot contain duplicate values.
            
        * **Key Features**:
            
            * Stores only unique elements.
                
            * No index-based access, like in arrays.
                
            * Elements can be of any type.
                
        * **Use Cases**:
            
            * Managing collections with unique data (e.g., list of unique users or tags).
                
            * Efficiently checking for the existence of an element in a collection.
                
        * **Time Complexity**:
            
            * Insertion: O(1)
                
            * Deletion: O(1)
                
            * Search (Check for element existence): O(1)
                
        
        **Code in TypeScript**:
        
    * ![](https://cdn.hashnode.com/res/hashnode/image/upload/v1726549840047/2b3d6edd-b6db-4f94-9ddc-0de19093ea29.png align="center")
        
        ## **Tree:**
        
        * **Definition**: A **Binary Search Tree (BST)** is a tree data structure where each node has at most two children (left and right), and the left child contains nodes with values less than the parent node, while the right child contains nodes with values greater than the parent node.
            
        * **Key Features**:
            
            * Efficient for searching, inserting, and deleting nodes.
                
            * Elements are stored in a sorted order, facilitating faster search.
                
        * **Use Cases**:
            
            * Storing sorted data and enabling quick search, insert, and delete operations.
                
            * Implementing data structures such as sets, maps, or priority queues.
                
        * **Time Complexity**:
            
            * Insertion: O(log n)
                
            * Deletion: O(log n)
                
            * Search: O(log n)
                
        * Worst case (unbalanced tree): O(n) for all operations.
            
        
        **Code in TypeScript**:
        
    * ![](https://cdn.hashnode.com/res/hashnode/image/upload/v1726550330046/33b9127f-52e9-485a-8120-40a4895843d4.png align="center")
        
    * ![](https://cdn.hashnode.com/res/hashnode/image/upload/v1726550205028/6c2f9b4c-a9da-4ee3-9640-5528290eaf2d.png align="center")
        
    * ![](https://cdn.hashnode.com/res/hashnode/image/upload/v1726550230817/0bd5bf2e-9f65-4072-92ff-d4f47c6d2214.png align="center")
        
    * ![](https://cdn.hashnode.com/res/hashnode/image/upload/v1726550305327/dffd3d52-0449-4f64-9703-5649f840676d.png align="center")
        
        ## **Deliverables:**
        
        **Explanation**:
        
        * For **Set**, we covered its properties of uniqueness, and how to add, remove, and check for elements.
            
        * For **Binary Search Tree**, we discussed the sorted nature of the structure, and how it allows for efficient searching, insertion, and traversal.
            
        * **TypeScript Code Snippets**:
            
            * For **Set**, the code demonstrates creation, addition, removal, and checking for existence.
                
            * For **Binary Search Tree**, the code shows insertion, searching, and in-order traversal of nodes.