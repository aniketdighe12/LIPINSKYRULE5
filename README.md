# LIPINSKYRULE5
Molecular Property Analysis with RDKit and PubChemPy

Molecular Property Analysis with RDKit and PubChemPy
This Python script analyzes molecular properties using the RDKit and PubChemPy libraries. It calculates various descriptors for a given chemical compound represented by its SMILES notation.

**Prerequisites**
Make sure you have the following packages installed:

RDKit: Install it using !pip install rdkit.
PubChemPy: Install it using !pip install pubchempy.

**Usage**
Clone this repository to your local machine.
Run the script molecular_properties.py.
Input the SMILES notation of the compound you want to analyze.

**Features**
Structure Visualization: The script generates a 2D structure representation of the input compound.
IUPAC Name Retrieval: It retrieves the IUPAC name for the given compound using PubChemPy.
Molecular Descriptors:
Molecular Weight (MW): Calculated using RDKit.
LogP (Octanol-Water Partition Coefficient): Also computed using RDKit.
Topological Polar Surface Area (TPSA): Another descriptor provided by RDKit.
Hydrogen Bond Acceptors (HBA) and Hydrogen Bond Donors (HBD): Both were determined using RDKit.

**Example**
For the compound CN(C)C(=N)NC(N)=N:

IUPAC Name: Guanidine
MW: 59.07 g/mol
LogP: -1.48
TPSA: 0 Å²
HBA: 4
HBD: 4
