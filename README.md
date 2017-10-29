# RandomPivotQuickSort



To demonstrate quick sort with random pivot, I first created two text files, "nuts.txt" and "bolts.txt" and placed it in the project directory. I used a scanner and File to read the contents from the two text files. Then, I created two array_lists and filled it with the numbers from the two text files. I used two methods to implement the sorting algorithm, "sort_NutsNBolts" and "sort_it" to sort the nuts and bolts. The "sort_NutsNBolts" method uses the sort_it method to set up the random chosen pivot. First, a random pivot is picked from the numbers present in the nuts_list to sort the numbers present in the bolt_list by using the idea that if threads of nuts_lists are larger, smaller or perfect match with the threads of bolts_list. Then, an algorithm similar to quickSort is used to sort the bolts and similarly, a random pivot is picked from the bolts_list to sort the nuts_list. 

