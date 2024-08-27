# Curated Polyoxometalate Formula Dataset (Curated-POMs)

This repository hosts a systematically curated database of Polyoxometalate (POM) compounds. It is intended as a scholarly resource that provides detailed chemical data on various POMs for academic research, facilitating advancements in chemistry, materials science, and related disciplines.

## Contributors

The development and curation of this database have been accomplished through the collaborative efforts of the following contributors:

- **Dr. Aleksandar Kondinski**, University of Cambridge, UK
- **Dr. Nadiia Gumerova**, Universität Wien, Austria
- **Prof. Annette Rompel**, Universität Wien, Austria

## File Description

**Filename:** `Curated_POMs.json`

The JSON file consists of detailed entries for each POM, structured to support research and educational applications effectively. The entries are identified by unique identifiers and include comprehensive information about the compounds and associated materials.

### POM Formula and Material

Each entry within the database encompasses:

- **POM Formula**: The molecular formula of the POM, reflecting its chemical structure.
- **Molecular Formula**: Represents the simplest integer ratio of the elements.
- **Contains Elements**: Enumerates the elements present and their quantities in the molecule.
- **Molecular Mass**: Specifies the mass of the POM in atomic mass units (amu).
- **Charge**: Details the net ionic charge of the POM.
- **Labels**: Descriptive tags that help categorize the type of polyoxometalate.
- **POM Material**: Contains a dictionary of materials derived from or related to the POM, each identified by a unique code and includes:
  - **POM Material Formula**: The specific chemical formula of the material.
  - **DOI**: A link to the digital object identifier providing access to the publication where the material is detailed.

### Example Entry

```json
{
    "POM_GUKA": {
        "POM Formula": "[α-P2W18O62]6-",
        "Molecular Formula": "O62P2W18",
        "Contains Elements": {
            "O": 62,
            "P": 2,
            "W": 18
        },
        "Molecular Mass": "4363.006",
        "Charge": -6.0,
        "Labels": [
            "Polyoxotungstate", "Wells-Dawson"
        ],
        "POM Material": {
            "f3293b14-5fc3-4017-a825-e25e6b8ab056": {
                "Material Formula": "Li6[α-P2W18O62]·28H2O",
                "DOI": "10.1039/C3DT51120K"
            }
        }
    }
}
