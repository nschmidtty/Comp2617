# Comp_1627 Ch.8

### Pointers
* A pointer contains a single memory address
* Variable names dirrectly refrence values | Pointers inderectly refrence values
* Inderection - Refrencing a value through a pointer
``` cpp
//declares countPtr to be a pointer to an int datatype
//declares count to be a variable (a direct refrence) to an int
//not prefered decleration syntax
int *countPtr, count;

//put Ptr
//better
int *countPtr, *anotherPtr, *agianPtr;
int count, size, blue;

//when initializing empty pointers always set them to nullptr
int *anotherPtr = nullptr
```
* When `*` appears in a varibale decleration it is not an operator just a pointer indicator

