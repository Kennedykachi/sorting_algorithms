  * [102-counting_sort.c](./102-counting_sort.c): C function that sorts an array of integers in ascending order using the Counting Sort algorithm.
  * Assumes that the array will only contain numbers `>= 0`.
  * Prints the counting array after it has been initialized.
  * [102-O](./102-O): Text file containing the best, average, and worst case time complexities of the Counting Sort algorithm, one per line.

* **7. Merge sort**
  * [103-merge_sort.c](./103-merge_sort.c): C function that sorts an array of integers in ascending order using the Merge Sort algorithm.
  * Implements the `top-down` Merge Sort algorithm.
    * When an array is divided, the size of the left subarray is always less than or equal to the size of the right subarray.
    * Always sorts the left subarray before the right one.
  * Prints subarrays each time they are merged.
  * [103-O](./103-O): Text file containing the best, average, and worst case time complexities of the Merge Sort algorithm, one per line.

* **8. Heap sort**
  * [104-heap_sort.c](./104-heap_sort.c): C function that sorts an array of integers in ascending order using the Heap Sort algorithm.
  * Implements the `sift-down` Heap Sort algorithm.
  * Prints the array after each swap.
  * [104-O](./104-O): Text file containing the best, average, and worst case time complexiites of the Heap Sort algorithm, one per line.

* **9. Radix sort**
  * [105-radix_sort.c](./105-radix_sort.c): C function that sorts an array of integers in ascending order using the Radix Sort algorithm.
  * Implements the Least-Significant-Digit (LSD) Radix Sort algorithm.
  * Assumes that the array will only contain numbers `>= 0`.
  * Prints the array for each significant digit increase.
  * [105-O](./105-O): Text file containing the best, average, and worst case time complexities of the Radix Sort algorithm, one per line.

* **10. Bitonic sort**
  * [106-bitonic_sort.c](./106-bitonic_sort.c): C function that sorts an array of integers in ascending order using the Bitonic Sort algorithm.
  * Assumes that `size` is a power of 2 (ie. `size` can be expressed as `2^k` where `k >= 0`).
  * Prints subarrays each time they are merged.
  * [106-O](./106-O): Text file containing the best, average, and worst case time complexities of the Bitonic Sort algorithm, one per line.

* **11. Quick Sort - Hoare Partition scheme**
  * [107-quick_sort_hoare.c](./107-quick_sort_hoare.c): C function that sorts an array of integers in ascending order using the Quick Sort algorithm.
  * Implements the Hoare partition scheme.
  * Always uses the last elemement of the partition being sorted as the pivot.
  * Prints the array after each swap.
  * [107-O](./107-O): Text file containing the best, average, and worst case time complexities of the Quick Sort Hoare Partition cheme algorithm, one per line.

* **12. Dealer**
  * [1000-sort_deck.c](./1000-sort_deck.c): C function that sorts a `deck_node_t` doubly-linked list deck of cards.
  * Assumes that there are exactly `52` elements in the doubly-linked list.
  * Orders the deck from spades to diamonds and from aces to kings.


