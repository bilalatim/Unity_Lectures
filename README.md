# Various Versions of Quick Sort Performance Testing

This ptyhon code is a program to test the performance of the Quick Sort algorithm with different input sizes, ranges, cases, and versions of the algorithm.
There are four version of algorithm:

1) **Classical Deterministic Quicksort Algorithm**: The pivot is chosen as the first element of the list. 
2) **Quicksort (1st version) Algorithm**: The pivot is chosen randomly.
3) **Quicksort (2st version) Algorithm**: The list is first randomly generated and then the classical deterministic algorithm is called where the pivot is chosen as the first element of the list.
4) **The Deterministic Quicksort Algorithm**: The pivot is chosen according to the **“median of three”** rule.

## Dependencies

This code requires the following python libraries:

* argparse
* random
* sys
* time

## Usage

To run the code, first go directory of file and use the following command:

- python main.py

To test spesific size, case or version you can use following optional arguments:

**-v or --version {classical,randomized_pivot,randomized_permutation,median,all}**    (the version of the Quick Sort algorithm to use, default : all)

**-n or --size N**        (the size of the input data)

**-r R, --range R**      (the range of the input data)

**-c or --case {average,worst,both}**        (the case of the input data)

## Output

The code will print the results of the Quick Sort performance tests to the console. The results will include the input size, range, case, and version of the Quick Sort algorithm, as well as the time it took to run the algorithm on the input data and also input array.

## Example Input

python main.py -v classical -n 10 -r 10 -c average

## Example Output
Data size 10:

        Input type InpType1 with range [1, 100]:
                Algorithm classical as version of Ver1:
                        Input1 (average)= [20, 45, 33, 31, 11, 11, 8, 71, 57, 38]
                        Input2 (average)= [48, 12, 47, 3, 93, 90, 49, 80, 72, 17]
                        Input3 (average)= [50, 75, 35, 12, 44, 63, 9, 7, 70, 33]
                        Input4 (average)= [13, 87, 25, 69, 90, 17, 41, 88, 70, 35]
                        Input5 (average)= [70, 6, 37, 77, 34, 96, 73, 56, 92, 38]
                        Duration for Case1 (average case): 0.0
