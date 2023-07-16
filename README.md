# solutions to coding test @ bitnine

by F Njakai on [GitHub](def3) and [LinkedIn][def4]


## problems solved: questions 1 and 2


## question 1

### node is defined as follows :
```C
typedef struct Node
{
TypeTag type;
} Node;
typedef enum TypeTag {
...
}
Using this structure, please write a function that returns fibonacci sequence based on the following arithmetic operations (+, -, *, /) and conditions.
The fibonacci function should be implemented using Dynamic Programming.
main()
{
Node *add = (*makeFunc(ADD))(10, 6);
Node *mul = (*makeFunc(MUL))(5, 4);
Node *sub = (*makeFunc(SUB))(mul, add);
Node *fibo = (*makeFunc(SUB))(sub, NULL);
calc(add);
calc(mul);
calc(sub);
calc(fibo)
}
Output
add : 16
mul : 20
sub : -4
fibo : 2

```

### solution is in the dir [`question1`][def]


## question 2

▪ Implement the following piecewise recurrence relation in the 3 different ways.
▪ Explain the differences (advantages, disadvantages) between the 3.
▪ Must be written in C


The problem
F(n) = F(n-3) + F(n -2) where F(0) = 0, F(1) = 1, and F(2) = 2.
Assume that n will be less than or equal to the maximum integer value and non-negative. You only need to
write the function(s).

### solution is in the dir [`question2`][def2]

[def]: ./question1/
[def2]: ./question2/
[def3]: https://www.github.com/brk-a
[def4]: https://www.linkedin.com/in/fnjakai