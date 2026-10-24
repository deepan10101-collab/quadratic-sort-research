# Quadratic Sorting Algorithms: Performance Research

## Overview

This project investigates the performance of several sorting algorithms by comparing their runtimes across different input arrangements. The research paper studies **bubble sort, selection sort, insertion sort, and pancake sort**, and discusses how input size and input order affect runtime.

The experiments described in the paper compare implementations using **objects and primitive values**, and examine randomized, already-sorted, and descending-order arrays.

## Research Questions

- How does runtime change as the input array grows?
- How do bubble sort, selection sort, and insertion sort compare on different input arrangements?
- How does sorting objects compare with sorting primitive values?
- How does pancake sort work, and how does its complexity compare with the other algorithms?

## Algorithms Covered

- **Bubble sort** — repeatedly compares adjacent elements and swaps them when they are out of order.
- **Selection sort** — repeatedly searches the unsorted portion for the next element to place.
- **Insertion sort** — inserts each element into its proper position in the portion already sorted.
- **Pancake sort** — uses prefix reversals to move selected elements toward their final positions.

## Method

The paper describes timing sorts on arrays of different sizes and with different initial arrangements:

- Randomized arrays
- Already-sorted arrays
- Descending-order arrays

The results are presented as graphs comparing runtime against array size. The report also compares object-based and primitive-based data.

## Main Findings Reported

- The paper observes approximately quadratic runtime growth for the quadratic sorting algorithms as input size increases.
- In the reported randomized-array experiments, insertion sort generally performs best among bubble, selection, and insertion sort.
- The paper explains that insertion sort and bubble sort can perform much better on already-sorted input than on reverse-ordered input.
- The paper notes that object comparisons can add overhead compared with operations on primitive values in the implementation studied.

These are findings from the experiments described in the accompanying paper; timings may vary with implementation, programming language, runtime environment, and hardware.

## Files

- `Quadratic Sort Research Paper.docx` — the original research report, including graphs, analysis, and discussion.

## Data and Related Materials

- **Dataset:** [Listing of Active Businesses — Data.gov](https://catalog.data.gov/dataset/listing-of-active-businesses)
- **Spreadsheet used for graph data:** [Open spreadsheet](https://docs.google.com/spreadsheets/d/12c_j_92rsmykfZvpjbfiB-kJUpbpxm60nWlX9pK0Sxw/edit?usp=sharing)
- **Code referenced in the original paper:** [Open code file in Google Drive](https://drive.google.com/file/d/1U5DqzRAI8RUw3ztMuDgx-11NPkwdJaiy/view?usp=sharing)

Please check that the linked spreadsheet and code are accessible and that you have permission to share them before making this repository public.

## Authors and Contributions

**Authors:** Deepan Idayachandiran and Anirudh Krishna

This was a collaborative research assignment. The paper documents the algorithms, runtime comparisons, graphs, and analysis. For an application or interview, describe only the portions of the research, data analysis, graphing, and writing that you personally contributed.

## Limitations

The results reflect the particular implementations, test data, and computing environment used for the original assignment. The paper reports runtime measurements, but this repository does not currently include a standalone, reproducible benchmarking program. Including the original source code and instructions to rerun the experiments would make the results easier to reproduce.

## Future Improvements

- Include the original source code in the repository.
- Document the language, runtime, hardware, and test procedure.
- Add a reproducible benchmark script and raw timing data.
- Regenerate the graphs from the raw data.
- Explain any unexpected results and distinguish measured results from theoretical time complexity.
