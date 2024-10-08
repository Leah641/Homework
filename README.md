# 8th Oct Homework
## Student Number:2875167

*Question: write the algorithm that count how many even numbers are in list[5,4,3,6,7,7,1,1]*

**Step 1** Make even numbers= 0

**Step 2** Start with the first entry of the list and go to step 3

**Step 3** Check if it can be devided by 2 with no remainders.
If it can be devided then increase even numbers by 1.
Go to step 4

**Step 4** Move to the next entry in the list and go to step 3, but if there are no more entries then go to step 5

**Step 5** The even numbers is in order

- [5=2*2+1], even numbers= 0
- [4=2*2], even numbers= 1
- [3=2*1+1], even numbers= 1
- [6=2*3], even numbers= 2
- [7=2*3+1], even numbers= 2
- [7=2*3+1], even numbers= 2
- [1=2*0+1], even numbers= 2
- [1=2*0+1], even numbers= 2
- There are 2 even numbers
