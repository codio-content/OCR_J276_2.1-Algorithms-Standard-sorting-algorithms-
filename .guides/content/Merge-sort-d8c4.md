The merge sort algorithm is used to sort an unordered list by repeatedly (recursively) dividing a list into two smaller lists until the size of each list becomes one. It is a ‘divide and conquer’ algorithm. 
The individual lists are then merged with the items in their correct order.

Here is the merge sort algorithm:

1. Divide the list into two parts
1. Recursively divide these lists until the size of each becomes one
1. Recursively merge the lists with the items in the correct numerical order

The following is a list of items to be sorted into ascending order.

![](.guides/img/merge1.png)

Recursively split into two until each list has one item.

![](.guides/img/merge2.png)

The items are reassembled in ascending order.
Each pair are compared 7 with 3, 6 with 5, 8 with 2 and 4 with 1. They are then combined in ascending order.

![](.guides/img/merge3.png)

The leftmost items in each pair are now compared as they are the smallest e.g. 3 is compared with 5 and is inserted first. The 5 is then compared with the second number of the left hand list (the algorithm already knows that it is smaller than the second number of the right hand list where it came from). As it is smaller, the 5 is inserted next and then the second numbers are compared.

![](.guides/img/merge4.png)

The same procedure is done for the last merge.

![](.guides/img/merge5.png)

The merge sort algorithm is efficient for a large number of items but for small items (less than 1,000) the time difference is less than one second.

Have a look at this video:
<iframe width="560" height="315" src="https://www.youtube.com/embed/dENca26N6V4" frameborder="0" allowfullscreen></iframe>