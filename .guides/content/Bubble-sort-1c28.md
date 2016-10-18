Here is the bubble sort algorithm which compares pairs of values:

1. Start at the beginning of the list of values.
1. Compare the first and second values. Are they in order? If so, leave them; if not, swap them.
1. Compare the second and third values. Are they in order? If so, leave them; if not, swap them.
1. Now move on to the third and fourth values, then the fourth and fifth values.
1. Continue in this way to the end of the list, comparing each pair of values. 
1. Go through the list of values for a second time (which will be the second pass), a third time (the third pass), and so on, repeating steps 1–5 until there are no more swaps or passes to be made.

The following is a list of items to be sorted into ascending order.


![](.guides/img/firstpass.png)

After the first pass the highest value (Stephen) has risen like a bubble into its correct position and doesn’t need comparing again.


![](.guides/img/secondpass.png)

Now all of the values are in their correct positions.
But the computer would have to carry out a third pass to confirm this – it has to carry out passes until there are no swaps.


Have a look at this video:
<iframe width="560" height="315" src="https://www.youtube.com/embed/lyZQPjUT5B4" frameborder="0" allowfullscreen></iframe>