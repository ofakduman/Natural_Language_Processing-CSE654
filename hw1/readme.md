# Waterman-Smith Algorithm Project

This project is an implementation of the Waterman-Smith Algorithm in Python. The Waterman-Smith Algorithm is a local alignment algorithm that helps to find the most similar regions between two sequences, which can be used for comparing text files or biological sequences.

## Requirements

To run this project, you need to have the following packages installed:

- numpy
- tqdm
- PyPDF2 (for the extra part of the project)

To install the required packages, run:

Use the smith_waterman_algorithm function to find the most similar regions between two sequences:

``` python
result = smith_waterman_algorithm("A B C D", "D D C D")
print(result)
```

Use the `compare` function to find the similarity rate and matched text between two strings:

``` python
matched_str, similarity_rate = compare("G C C T C N T C C C G G C", "G G G C N T C C G G G F H")
print(matched_str, similarity_rate)

```

Run the runHW() function to compare text files located in the "sources" folder:

Check the H_similarity_matrix and H_matched_txt_matrix to see the similarity matrix and matched text matrix for the text files:

## Extra Part

The extra part of the project includes:

-> A recursive version of the Waterman-Smith Algorithm
-> A script to parse and process PDF files to TXT format
-> A progress bar to show the processing duration

To use the recursive version of the Waterman-Smith Algorithm, import the `smith_waterman_algorithmR` function from the script:

``` python
from script import smith_waterman_algorithmR
```
Then, use the smith_waterman_algorithmR function like this:


``` python
result = smith_waterman_algorithmR("A B C D", "D D C D")
print(result)
```

To use the script to parse and process PDF files, first, import the translateTotxt function from the script:

```python
from script import translateTotxt
```
Then, use the translateTotxt function to convert a PDF file to a TXT file:

```python
translateTotxt("example.pdf")
```
This will create a TXT file named "example.txt" in the same folder as the PDF file.


