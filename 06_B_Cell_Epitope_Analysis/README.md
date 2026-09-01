# B-Cell Epitope Analysis

## Overview

This folder contains the results of **B-cell epitope prediction** performed as part of the in silico multi-epitope subunit vaccine design targeting the **LptE protein of multidrug-resistant *Acinetobacter baumannii***.

B-cell epitope analysis was performed to identify potential **linear B-cell epitopes** within the selected LptE protein sequence that may be recognized by antibodies.

## Prediction Method

Linear B-cell epitope prediction was performed using the **BepiPred Linear Epitope Prediction 2.0** method available through the IEDB Analysis Resource.

The LptE protein amino-acid sequence was used as the input sequence for prediction.

## BepiPred Analysis

BepiPred evaluates the likelihood of individual residues belonging to a linear B-cell epitope based on their prediction scores.

Regions showing scores above the applied prediction threshold were identified as potential B-cell epitope regions.

Continuous predicted regions were considered as candidate linear B-cell epitopes rather than selecting isolated individual residues.

## Results

The B-cell epitope prediction generated candidate peptide regions within the LptE protein sequence.

The following files contain the prediction results:

* `BepiPred_Graph.png` – BepiPred prediction graph showing the predicted epitope regions and scores.
* `B_Cell_Epitopes.xlsx` – Complete B-cell epitope prediction results.

## Epitope Selection

The predicted B-cell epitopes were considered candidate epitopes for subsequent screening and vaccine design.

Further screening may include:

* Antigenicity analysis
* Allergenicity analysis
* Toxicity analysis
* Conservancy analysis
* Other criteria specified by the project mentor

Only candidates satisfying the defined selection criteria will be considered for incorporation into the final multi-epitope vaccine construct.

## Summary

BepiPred-based analysis identified potential linear B-cell epitopes within the LptE protein of multidrug-resistant *Acinetobacter baumannii*. These predicted epitopes will be evaluated further using additional immunoinformatics parameters before final selection.

## Files

| File                            | Description                                |
| ------------------------------- | ------------------------------------------ |
| `BepiPred_Graph.png`            | BepiPred prediction graph                  |
| `B_Cell_Epitopes.xlsx` | Predicted B-cell epitope regions           |
| `README.md`                     | Description of the B-cell epitope analysis |
