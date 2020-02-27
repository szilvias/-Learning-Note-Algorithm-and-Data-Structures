## Chapter 1 Basics
 
Definition
- Problem Instance: a specific input assignment for which the corresponding output is wanted.

### Algorithm requirements
- Specification of input / output: The number and types of all elements is defined. 
- Uniqueness: Each individual step is clearly defined and can be carried out. The order of the individual steps is fixed. 
- Finiteness: The notation has a finite length.

### Some properties of algorithms
- Generality (Allgemeinheit): Solution for problem class, not for single task 
- Determinacy (Determiniertheit): For the same input, the same output is always calculated (but other intermediate states are possible). 
- Determinism (Determinismus): The execution is always identical for the same input. For example non-deterministic: abs(x). 
- Termination (Terminierung): The algorithm only runs for a long time for each entry 
- (partial) correctness (partielle Korrektheit): Algorithm always calculates the specified output (if it terminates) 
- Efficiency (Effizienz): Economical use of resources (time, storage, energy, ...)

### Data Structures
- Organizational forms for data 
- Functional view: container objects with operations can be described as abstract data types. 
- Contain structural components and user data (payload) 
- Can be structured uniformly or heterogeneously 
- Requirements: 
    • Statically or dynamically determined size 
    • Transient or persistent storage
#### For example:
- Sequences: arrays, lists, cellar storage, queues 
- Multidimensional: matrices 
- Topological structures: trees, graphs, networks

### Data Typs
#### Elementary (atomic) data types (Java)
- Integers: byte (8-bit), short (16-bit), int (32-bit), long (64-bit)
- Binary truth value (true or false): boolean
- Char: char (16-bit)
- Floating point numbers: float (32-bit), double (64-bit)
#### Compound types
- String: string
- Record: data record (not explicit in Java; as an object or similar)
- Set: Quantity (predefined in Java, including methods for sorting Etc.)
- Array: order of fixed length of similar data

### Pointer
- Not explicit in Java
- Reference to another object
- Consists of the memory address of the referenced object
- For dynamic data structures: memory only when needed
- Explicit memory release in some programming languages
- Java has garbage collection: If there is no more reference, the memory will be released.

### Arrays
order (field) of fixed length of data of the same type
- Allows efficient access to elements: constant effort
- Reference type: reference to (address of) data
- An example: Sieve of Eratosthenes <https://en.wikipedia.org/wiki/Sieve_of_Eratosthenes>
#### Multi-dimensional Arrays
- Two-dimensional arrays (= matrices) are arrays of arrays. (like a[i][j])
- Build a new higher dimensional arrat:
```java
int [][][] hda = new int [2][2][2];//a 3*3 matric
```

### User-defined Data Types: class
- Combining various attributes into one object
- Example: returning multiple function results at once
  - But: Java only allows a single return value
  - Solution: return of a complex profitability segment

### Heterogeneous（异质） vs. Homogeneous（同质） data
- Classes are suitable for storing heterogeneous data types
  - Generally consist of different types of elements: class c {String s; int i;}
  - Each element has its own name: c.s, c.i
  - The number of elements becomes static when the class is declared.
- Arrays allow quick access to homogeneous data
  - Always consist of several similar elements: int []
  - Elements do not have their own names, but are over Indices addressed: a [i]
  - The number of elements becomes **dynamic** when the array is created: new int [n]
#### Dynamic Data Structures
- Motivation
  - Length of an array can not be changed after creation
  - Unlimited large data structures would be helpful
  - Solution idea: chaining individual objects into larger structures
- Examples: list, tree, graph
- Characterization
  - Nodes created and linked (dynamically) at runtime
  - Structures can grow and shrink dynamically
  - The size of a structure is limited only by available storage space; does not have to be determined in advance.




### Some useful JAVA methods here:
• parseInt() 
```
static int parseInt(String s)
static int parseInt(String s, int radix)
```
