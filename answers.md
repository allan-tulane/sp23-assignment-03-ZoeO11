# CMPS 2200 Assignment 3
## Answers

**Name:** Zoe Oboler


Place all written answers from `assignment-03.md` here for easier grading.






- **b.**
work = w(n-1)
span = s(n-1)
0(n) 


- **d.**
 W(scan) = W(n-1)+1 = 0(n)
 W(reduce) = 2W(n/2) + 1 = 0(n)
 Therefore the work of the function is 0(n)

Span(scan) = log(n)
Span(reduce) = log(n)
therefore Span = 0(log(n))


- **f.**
W(n) = 2W(n/2) + 1
so the work of the function is 0(n)
The function is balanced to span is the depth of the tree, 0(log(n))