
# Fill the following table for the expression given below and then evaluate the result

> (a) g=10/5/2/1; (b) b=3/2+5*4/3; (c)a=b=c=3+4;

## Answer:-

| **operators** | **Left** | **Right** | **Remarks**|
| ------------- | -------- | --------- | ------------|
| (a) | g=10/5/2/1| | |
| / | 10 | 5 or 5/2/1 | Left operands is unambiguous, Right is not |
| / | 10/5 or 2 | 2 or 2/1 | both operands are non-unambiguous |
| / | 10/5/2 or 1 | 1 | right operands is unambiguous, Left is not|
|(b) | b=3/2+5*4+3 | | |
| / | 3 | 2 or 2+5*4+3 | Left operands is unambiguous |
| + | 3/2 or 5 | 5 or 5*4+3 | Both operands are non-unambiguous |
| * | 3/2+5 or 4 | 4 or 4+3 | Both operands are non-unambiguous |
| + | 3/2+5*4 | 3 | Right operands is unambiougous , Left is not |
| (c) | a=b=c=3+4 | | |
| = | a | b=c=3+4 | Left operands is unambgiuous ,Right is not |
| = | a=b or c | c or c=3+4 | Both operands are non-unambiguous |
| = | a=b=c or 3 | 3 or 3+4 | Both operands are non-unambiguous |
| + | a=b=c=3 | 4 | Right operands is unambiguous ,Left is not
