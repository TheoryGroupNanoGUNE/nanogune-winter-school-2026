# Tutorial 3

This tutorial aims at teaching atomistic machine learning, a new field that deals with the application of machine learning to atoms and molecules (and sometimes electrons!). An important focus of the tutorial is learning the fundamentals of molecular dynamics driven by ab initio machine learning (ML) models for the potential energy surface (PES).

First, in ```A-training```, we discuss datasets for atomistic machine learning and we show how to train ML models for the PES. We also follow the evolution of error metrics furing the training process and test the final model.

Then, in ```B-radial-distribution-function```, we discuss molecular dynamics simulations and analyze one such simulation driven by the ML model for the PES. We consider a system of water molecules and investigate their structure using the radial distribution function.

Finally, in ```C-dimensional-reduction```, we use descriptors to understand the structure of local atomic environments. We train a model to distringuish between environments compatible with water and ice, and we also visualize these environments using dimensionality reduction.
