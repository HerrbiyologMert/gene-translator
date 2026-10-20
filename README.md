# Gene Translator

A small Python program that finds the start codon (ATG) in a DNA sequence and translates the gene into a protein, stopping at the first stop codon.

## What it does

- Searches the DNA sequence for the start codon `ATG`
- Reads the sequence from there in groups of three bases (codons)
- Translates each codon into an amino acid using the standard genetic code table
- Stops at the first stop codon (TAA, TAG, TGA)
- Shows a clear message if no `ATG` is found

## How to run

```
python tag26.py
```

## Example

Input sequence: `CCATGGGCTTTAAGTGAGG`

Output:

```
['Met', 'Gly', 'Phe', 'Lys']
```
