# Lists

Is mostly doing the same for IT-Fundamentals

## Pointers

```c
int a = 0; // define and set a
int * A = NULL; //define a pointer not wild
A = &a; // A now point to a
*A = 5; // a = 5 using a pointer
```

## Struct or ADT(Abstract Data Type)

```c
struct nodo{
    int info;
    struct nodo * next;
}
```
## "Pile" or Stack :

#### [LIFO - Last in First out]
You can immagine like a normal array of elements,

using functions like "Push" you insert the element in the first slot avaible, and using "POP" you get and remove the last element.

## "Code" or Queue:

#### [FIFO - First in First out] 
You can immagine it like an circolar array (if you try to add in tail and exced the N value, basicly you index+1 % N) of size N-1,
 
using functions like "Enqueue" you can insert the element in the tail, and using "Dequeue" you get and remove the head element.  

## [Sentinel node](https://en.wikipedia.org/wiki/Sentinel_node)
```c
nodo head = null;
// set the 1st element to be a sentinel
head->next = 1 element;
// the actual head of the list
head->prev = last element;
// the tail of the list if has to be double connected
head->info = NULL;
// since is a sentinel, it should be a NULL value
//or a Special Value like -1 if you don't have negative elsewhere. 
```

## Complextity:

#### Big-O notation (higher bind)

#### Theta notation (higher and lower bind)

#### Omega notation (lower bind)

#### [Time_complexity](https://en.wikipedia.org/wiki/Time_complexity): Constant , Logarithmic, Linear , Exponential, Factorial. 
