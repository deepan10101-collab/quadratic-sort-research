
# Quadratic Sorting Algorithms: Performance Research

## Overview

This collaborative research project investigates the performance of sorting algorithms across different input sizes and arrangements.

The paper studies bubble sort, selection sort, insertion sort, and pancake sort. It also compares sorting implementations using objects and primitive values.

## Algorithms Studied

- **Bubble Sort:** Repeatedly compares adjacent elements and swaps them when necessary.
- **Selection Sort:** Finds the next element to place in the sorted portion of the array.
- **Insertion Sort:** Inserts each element into its correct position in the sorted portion.
- **Pancake Sort:** Uses prefix reversals to move elements toward their final positions.

## Experimental Analysis

The research compares runtime across:

- Randomized arrays
- Already-sorted arrays
- Descending-order arrays
- Object-based and primitive-based implementations

The paper includes graphs comparing runtime against array size and discusses the observed performance differences.

## Key Findings

- The experiments show approximately quadratic runtime growth for the quadratic sorting algorithms as input size increases.
- In the reported randomized-array experiments, insertion sort generally performs best among bubble sort, selection sort, and insertion sort.
- Insertion sort and bubble sort can perform more efficiently on already-sorted inputs.
- Object-based comparisons can introduce additional overhead compared with primitive values in the implementations studied.

## Research Paper

The original research paper is included in this repository:

`Quadratic Sort Research Paper.docx`

It contains the graphs, experimental analysis, and written discussion.

## Dataset and Related Materials

- [Active Businesses Dataset — Data.gov](https://catalog.data.gov/dataset/listing-of-active-businesses)
- [Research Spreadsheet](https://docs.google.com/spreadsheets/d/12c_j_92rsmykfZvpjbfiB-kJUpbpxm60nWlX9pK0Sxw/edit?usp=sharing)
- [Original Code Reference](https://drive.google.com/file/d/1U5DqzRAI8RUw3ztMuDgx-11NPkwdJaiy/view?usp=sharing)

Check that linked materials are accessible and may be shared before making the repository public.

## Authors

Deepan Idayachandiran and Anirudh Krishna

This was a collaborative project. Each author's individual contributions should be described accurately.

## Future Improvements

- Include the original source code.
- Document the benchmarking environment and methodology.
- Include raw timing data and reproducible graphs.
- Compare experimental results with theoretical time complexity.
