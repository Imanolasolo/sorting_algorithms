# 0x1B. C - Sorting algorithms & Big O

<div style="text-align: justify">

Thank you for visiting this repository which contain our work to start learning C language programming. In this project, I implemented twelve different sorting algorithms. 	


![Logo](https://www.howtogeek.com/wp-content/uploads/2021/05/laptop-with-terminal-big.png?height=200p&trim=2,2,2,50)

# Getting Started :running:
<div style="text-align: justify">

## Table of Contents
* [AUTHORS](./AUTHORS)
* [MIT License](./LICENSE)
* [About](#about)
* [Dependences](#dependences)
* [Installing, compiling and using](#installing, compiling and using)
* [Builtins](#builtins)
* [Man page]
* [Credits](#credits)

## About
This directory contains a collection of files, functions, structs and scripts used to build and manage this repository. If there are any issues regarding the intention of a particular script (or even part of a certain script), please reach out to us.
	
	Contents:

- At least four different sorting algorithms

- What is the Big O notation, and how to evaluate the time complexity of an algorithm

- How to select the best sorting algorithm for a given input

- What is a stable sorting algorithm
	
## Dependences 
	
> [sort.h](https://github.com/Imanolasolo/sorting_algorithms/blob/master/sort.h) --> Header file containing all functions involved in project.

> [README.md](https://github.com/Imanolasolo/sorting_algorithms/blob/master/README.md) ---> README file to show the project insights. 

>[0-bubble_sort.c](https://github.com/Imanolasolo/holbertonschool-low_level_programming/blob/main/0x18-dynamic_libraries/libdynamic.so) ---> function that sorts an array of integers in ascending order using the Bubble sort algorithm

>[0-O](https://github.com/Imanolasolo/holbertonschool-higher_level_programming/blob/master/0x04-python-more_data_structures/2-uniq_add.py) ---> the big O notations of the time complexity of the Bubble sort algorithm

>[1-insertion_sort_list.c](https://github.com/Imanolasolo/sorting_algorithms/blob/master/1-insertion_sort_list.c) --> function that sorts a doubly linked list of integers in ascending order using the Insertion sort algorithm

>[1-O](https://github.com/Imanolasolo/sorting_algorithms/blob/master/1-O) --> the big O notations of the time complexity of the Insertion sort algorithm

>[2-selection_sort.c](https://github.com/Imanolasolo/sorting_algorithms/blob/master/2-selection_sort.c) --> function that sorts an array of integers in ascending order using the Selection sort algorithm

>[2-O](https://github.com/Imanolasolo/sorting_algorithms/blob/master/2-O) --> the big O notations of the time complexity of the Selection sort algorithm

>[3-quick_sort.c](https://github.com/Imanolasolo/sorting_algorithms/blob/master/3-quick_sort.c) --> function that sorts an array of integers in ascending order using the Quick sort algorithm 

>[3-O](https://github.com/Imanolasolo/sorting_algorithms/blob/master/3-O) --> the big O notations of the time complexity of the Quick sort algorithm

>[100-shell_sort.c](https://github.com/Imanolasolo/sorting_algorithms/blob/master/100-shell_sort.c) --> function that sorts an array of integers in ascending order using the Shell sort algorithm, using the Knuth sequence

>[101-cocktail_sort_list.c](https://github.com/Imanolasolo/sorting_algorithms/blob/master/101-cocktail_sort_list.c) --> function that sorts a doubly linked list of integers in ascending order using the Cocktail shaker sort algorithm

>[101-O](https://github.com/Imanolasolo/sorting_algorithms/blob/master/101-O) --> the big O notations of the time complexity of the Cocktail shaker sort algorithm

>[102-counting_sort.c](https://github.com/Imanolasolo/sorting_algorithms/blob/master/102-counting_sort.c) --> function that sorts an array of integers in ascending order using the Counting sort algorithm

>[102-O](https://github.com/Imanolasolo/sorting_algorithms/blob/master/102-O) --> the big O notations of the time complexity of the Counting sort algorithm

>[103-merge_sort.c](https://github.com/Imanolasolo/sorting_algorithms/blob/master/103-merge_sort.c) --> function that sorts an array of integers in ascending order using the Merge sort algorithm

>[103-O](https://github.com/Imanolasolo/sorting_algorithms/blob/master/103-O) --> the big O notations of the time complexity of the Merge sort algorithm

>[104-heap_sort.c](https://github.com/Imanolasolo/sorting_algorithms/blob/master/104-heap_sort.c) --> function that sorts an array of integers in ascending order using the Heap sort algorithm

>[104-O](https://github.com/Imanolasolo/sorting_algorithms/blob/master/104-O) -->  the big O notations of the time complexity of the Heap sort algorithm

>[105-radix_sort.c](https://github.com/Imanolasolo/sorting_algorithms/blob/master/105-radix_sort.c) --> function that sorts an array of integers in ascending order using the Radix sort algorithm

>[106-bitonic_sort.c](https://github.com/Imanolasolo/sorting_algorithms/blob/master/106-bitonic_sort.c) --> function that sorts an array of integers in ascending order using the Bitonic sort algorithm

>[106-O](https://github.com/Imanolasolo/sorting_algorithms/blob/master/106-O) -->  the big O notations of the time complexity of the Bitonic sort algorithm

>[107-quick_sort_hoare.c](https://github.com/Imanolasolo/sorting_algorithms/blob/master/107-quick_sort_hoare.c) --> function that sorts an array of integers in ascending order using the Quick sort algorithm

>[107-O](https://github.com/Imanolasolo/sorting_algorithms/blob/master/107-O) --> the big O notations of the time complexity of the Quick sort algorithm

>[deck.h](https://github.com/Imanolasolo/sorting_algorithms/blob/master/deck.h) --> header file, containing  data structures definition for next dependence

>[1000-sort_deck.c](https://github.com/Imanolasolo/sorting_algorithms/blob/master/1000-sort_deck.c) --> function that sorts a deck of cards

## Installing, compiling and using
	
> Only install cloning this repository on your local device:  https://github.com/Imanolasolo/sorting_algorithms.git
	
> Compile the .c files with `gcc` using ` -Wall -Werror -Wextra -pedantic -std=gnu89`
	
> Run the executable files with `./` 

## Builtins
```
void bubble_sort(int *array, size_t size);
void insertion_sort_list(listint_t **list);
void selection_sort(int *array, size_t size);
void shell_sort(int *array, size_t size);
void cocktail_sort_list(listint_t **list);
void counting_sort(int *array, size_t size);
void merge_sort(int *array, size_t size);
void heap_sort(int *array, size_t size);
void radix_sort(int *array, size_t size);
void bitonic_sort(int *array, size_t size);
void quick_sort_hoare(int *array, size_t size);
void sort_deck(deck_node_t **deck);

```
		
## Man page

-  No man page

## Flowchart
	
- No flowchart

## Resources

**Read or watch**:

[Sorting algorithm](https://intranet.hbtn.io/rltoken/tmzgO7xhCpNgPUxVhLKibw)

[Big O notation](https://intranet.hbtn.io/rltoken/XrLMaOhUMHfwsFEz15TVow)

[Sorting algorithms animations](https://intranet.hbtn.io/rltoken/kJ7rgWoqdLnxSnSEoAiFCQ)

[15 sorting algorithms in 6 minutes (WARNING: The following video can trigger seizure/epilepsy. It is not required for the project, as it is only a funny visualization of different sorting algorithms)](https://intranet.hbtn.io/rltoken/RdvoGNMTJ6Hq34aJ_HmCqA)

## Usage



## Credits

## Author(s):blue_book:

Work is owned and maintained by:
* Imanol Asolo <[3848](mailto:3848@holbertonschool.com)> [![M](https://upload.wikimedia.org/wikipedia/commons/thumb/9/91/Octicons-mark-github.svg/25px-Octicons-mark-github.svg.png)](https://github.com/Imanolasolo) [![M](https://upload.wikimedia.org/wikipedia/fr/thumb/c/c8/Twitter_Bird.svg/25px-Twitter_Bird.svg.png)](https://twitter.com/jjusturi) [![M](https://upload.wikimedia.org/wikipedia/commons/thumb/c/ca/LinkedIn_logo_initials.png/25px-LinkedIn_logo_initials.png)](https://www.linkedin.com/in/imanol-asolo-5ba9b42a/)


## Acknowledgments :mega: 

### **`Holberton School`** (*providing guidance*)
This program was written as part of the curriculum for Holberton School.
Holberton School is a campus-based full-stack software engineering program
that prepares students for careers in the tech industry using project-based
peer learning. For more information, visit [this link](https://www.holbertonschool.com/).
<p align="center">
	<img src="https://assets.website-files.com/6105315644a26f77912a1ada/610540e8b4cd6969794fe673_Holberton_School_logo-04-04.svg" alt="This is a secret;)">
</p>