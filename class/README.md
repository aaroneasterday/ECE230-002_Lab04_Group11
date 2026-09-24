# Lab 04 - SOP/POS and KMaps

In this lab, you’ve learned how to apply KMaps, Sum Of Products and Products of
sums to simplify digital logic equations. Then, you’ve proven out that they work
using an implemented design on your Basys3 boards.

## Rubric

| Item | Description | Value |
| ---- | ----------- | ----- |
| Summary Answers | Your writings about what you learned in this lab. | 25% |
| Question 1 | Your answers to the question | 25% |
| Question 2 | Your answers to the question | 25% |
| Question 3 | Your answers to the question | 25% |

## Lab Summary

Summarize your learnings from the lab here.
We learned how to use K-maps with SOP and POS to find minterm and maxterm of a given truth table. We also further developed our understanding of Basys3 and Verilog code using Vivado.

## Lab Questions

### Why are the groups of 1’s (or 0’s) that we select in the KMap able to go across edges?
As we discussed in the lecture, the K-map wraps around itself allowing us to create groups that go from one edge of the K-map to the opposite.

### Why are the names Sum of Products and Products of Sums?
Sum of product is named as such because you take all of the and statements, or products, and add them together using or statements, or sums. Product of Sum is named as such for the equal but opposite reason. 

### Open the test.v file – how are we able to check that the signals match using XOR?
The test.v file uses XOR gates to ensure that the three equations that we put into minterm.v, maxterm.v, and naive.v are all equivalent.