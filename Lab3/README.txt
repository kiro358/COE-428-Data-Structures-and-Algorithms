//Kirolos Youssef, 500968175

./insertionSort - has been completed and works using the metrics header, it implements insertion sort
and outputs the sorted array as well as the metrics for that specific sort.

./mergeSort - has been partially completed, I was having a very difficult time getting it to not throw
segmentation faults, the algorithm itself is sound, but there may be some properties of it that I may be
over looking. It has been also completed with the metrics header.


Insertion Sort Analysis:

Best Case - O(n) , n comparisons , 0 swaps , 0 copys
Average Case - O(n^2), (n(n-1)/2) comparisons ,(n(n-1)/2) swaps , (n-1) copys
Worst Case - O(n^2) ,(n(n-1)/2) comparisons ,(n(n-1)/2) swaps , (n-1) copys

Merge Sort Analysis:

Best Case - O(nlogn) ,
Average Case - O(nlogn) ,
Worst Case - O(nlogn), (nlgn - n +1) comparisons