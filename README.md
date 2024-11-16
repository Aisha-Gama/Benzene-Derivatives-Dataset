# Benzene-Derivatives-Dataset

A Python script that generates and visualizes 2D molecular structures of common benzene derivatives using RDKit. The script converts SMILES notations to molecular structures and saves them as PNG images.

# Prerequisites

You need:
- Python 3.x
- RDKit (install via "pip install rdkit")
- Google Colab (for file downloads) or modify the script for local use

# Installation

Simply run "pip install rdkit" in your terminal or command prompt.

# Usage

1. Run the script in a Google Colab notebook or modify the file handling for local execution
2. The script will generate PNG images for each benzene derivative
3. Images will be automatically downloaded when running in Colab

# Included Compounds

The script generates visualizations for the following benzene derivatives:

1. Benzene (C6H6)
2. Toluene (C7H8)
3. Phenol (C6H5OH)
4. Aniline (C6H5NH2)
5. Nitrobenzene (C6H5NO2)
6. Benzaldehyde (C6H5CHO)
7. Benzoic Acid (C6H5COOH)
8. Chlorobenzene (C6H5Cl)
9. Bromobenzene (C6H5Br)
10. Iodobenzene (C6H5I)
11. Ethylbenzene (C6H5CH2CH3)
12. Styrene (C6H5CH=CH2)
13. Acetophenone (C6H5COCH3)
14. Benzonitrile (C6H5CN)
15. Catechol (C6H4(OH)2)

# Code Structure

The script is organized into three main sections:

1. Library Imports
   - Imports RDKit for molecular operations
   - Imports Drawing utilities for visualization

2. SMILES Definition
   - Contains a list of benzene derivatives in SMILES notation
   - Each SMILES string is labeled with the compound name

3. Image Generation
   - Converts SMILES to molecular structures
   - Generates 2D representations
   - Saves images as PNG files

# Output

The script produces:
- PNG files named benzene_derivative_1.png through benzene_derivative_15.png
- Console output confirming successful image generation
- Automatic file downloads when run in Google Colab

# Error Handling

The script includes safety features:
- Validates SMILES notation before image generation
- Reports invalid SMILES strings in console output
- Skips failed conversions without interrupting the process

# Customization

To add new compounds:

1. Add new SMILES strings to the benzene_derivatives list
2. Follow the format: SMILES_STRING with compound name as comment
3. New compounds will automatically be processed

# Local Usage

For local machine use:
1. Remove Google Colab import statement
2. Remove file download section
3. Images will save to your working directory

# License

This script is provided as-is under the MIT License.

# Contributing

We welcome:
- Bug reports
- Feature requests
- Code improvements
- Documentation updates
- New compound suggestions

# References

Essential resources:
- RDKit Documentation: www.rdkit.org/docs
- SMILES Notation: Visit Wikipedia's SMILES article
- Benzene Derivatives: Basic organic chemistry texts

# Support

For issues:
1. Check existing documentation
2. Verify RDKit installation
3. Ensure valid SMILES notation
4. Check file permissions for saving images

# Notes

- Images are generated in standard resolution
- Default image format is PNG
- Molecular orientations are automatically optimized
- 2D representations follow standard chemical conventions
