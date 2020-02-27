Definition
• Problem Instance: a specific input assignment for which the corresponding output is wanted.

### Algorithm requirements
• Specification of input / output: - The number and types of all elements is defined. 
• Uniqueness: - Each individual step is clearly defined and can be carried out. 
              - The order of the individual steps is fixed. 
• Finiteness: - The notation has a finite length.

### Some properties of algorithms
• Generality (Allgemeinheit): - Solution for problem class, not for single task 
• Determinacy (Determiniertheit): - For the same input, the same output is always calculated (but other intermediate states are possible). 
• Determinism (Determinismus): - The execution is always identical for the same input. 
               - For example non-deterministic: abs(x). 
• Termination (Terminierung): - The algorithm only runs for a long time for each entry 
• (partial) correctness (partielle Korrektheit): - Algorithm always calculates the specified output (if it terminates) 
• Efficiency (Effizienz): - Economical use of resources (time, storage, energy, ...)

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

### Some useful JAVA methods here:
• parseInt() 
```
static int parseInt(String s)
static int parseInt(String s, int radix)
```
