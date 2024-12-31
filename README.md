# Comparative Analysis of Constituency Parsers: A Case Study on Stanford U-PCFG and Berkeley Neural Parsers

[![Paper](https://img.shields.io/badge/Paper-007ACC?style=for-the-badge&labelColor=007ACC)](https://drive.google.com/file/d/16fMdIH3aEdgeILgvdDL4TgvwpM18FbpI/view?usp=sharing)
[![Course Page](https://img.shields.io/badge/Course_Page-007ACC?style=for-the-badge&labelColor=007ACC)](https://www.cl.cam.ac.uk/teaching/2324/L95/)

## Abstract
Constituency parser performance is typically evaluated with bracketing F-score, which is a useful proxy of overall performance but does not adequately reveal the strengths and weaknesses of a system. This report presents quantitative and qualitative evaluations that aim to capture the behavior of a parser under different scenarios through observations of parser performance on a designated test set.1 To that end, it offers a comparative analysis of two constituency parsers: Berkeley Neural Parser (Kitaev and Klein, 2018; Kitaev et al., 2019) and Stanford Unlexicalized Probabilistic Context-Free Grammar (PCFG) Parser (Klein and Manning, 2003)

# Results
## Precision and Recall
![Alt text](assets/precision-recall.png)
## Parsing Time
![Alt text](assets/parsing-time.png)
## Error Types
![Alt text](assets/error-types.png)
## Example: Stanford PCFG Parser Mistakes
![Alt text](assets/10bstanford.png)
![Alt text](assets/10bgold.png)
## Example: Berkeley Neural Parser Mistakes
![Alt text](assets/6gold.png)
![Alt text](assets/6berkeley.png)