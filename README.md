# EDMBOX

This repository contains a collection of Matlab routines to accompany the paper
_Euclidean Distance Matrices for Signal Processing_ by Ivan Dokmanic, Reza
Parhizkar, Juri Ranieri and Martin Vetterli.

## Main functions

| Filename               | Description                                      |
| -----------------      | -------------------                              |
| edm.m                  | Creates an EDM from a list of points             |
| classic_mds.m          | Classic multidimensional scaling                 |
| alternating_descent.m  | S-stress minimization with ACD                   |
| random_deletion_mask.m | Observation mask with randomly removed distances |
| sdr_complete_edm.m     | EDM completion with semidefinite relaxation      |
| rank_complete_edm.m    | EDM completion with rank alternation             |

## Helper functions

| Filename          | Description                 |
| ----------------- | -------------------         |
| cubicfcnroots.m   | Roots of a cubic polynomial |
| quadfcn.m         | Roots of a quadratic        |

## Examples and paper figures

| Filename                       | Description                            |
| -----------------              | -------------------                    |
| Example1_SwissTrains_SBB.m     | City locations in the Swiss trains box |
| Example2_RandomCompletion.m    | Generates Fig. 6 of the paper          |
| Example3_UnfoldingCompletion.m | Generates Fig. 7 of the paper          |
