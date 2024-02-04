# Setting Up Your First Simulation

Welcome to the second module of the MD Simulations Basic Guides. This module is designed to help you set up your very first Molecular Dynamics (MD) simulation. Whether you're a student, researcher, or hobbyist, the resources and instructions here will guide you through the initial steps of MD simulation setup.

## What You Will Learn

In this module, you'll gain hands-on experience with:

- Identifying and obtaining your target protein structure.
- Preparing your protein for simulation, including cleaning and solvation.
- Adding ions and other necessary components to your system.
- Choosing an appropriate force field for your simulation.
- Performing energy minimization and system equilibration.

## Contents

- [**01_Protein_Prepartion**](01_Protein_Preparation.ipynb): A jupyter-notebook that automates the process of pre-processing a protein-ligand complex pdb.
- [**02_MD_System_Prepartion_for_GROMACS**](02_System_Preparation_GROMACS.ipynb): A jupyter-notebook that automates the process of preparing a protein-ligand , solvated system with AmberFF and GAFF for GROMACS MD package
- [**example_configs/**](example_configs/): Example configuration files that you can use as templates for your simulations.
  - [protein_preparation_config.txt](example_configs/protein_preparation_config.txt): An example configuration for protein preparation.
  - [simulation_parameters.md](example_configs/simulation_parameters.md): Descriptions of common simulation parameters and how to set them.

## Getting Started

To begin, it's recommended to read through the [setup_guide.pdf](setup_guide.pdf) for a complete understanding of the process. Then, proceed to the `example_configs` directory to familiarize yourself with the configuration files that you'll need to create for your own simulations.

## Prerequisites

Before starting, make sure you have:

- Installed the necessary MD simulation software (GROMACS, OpenMM, NAMD, etc.).
- Basic knowledge of command-line operations and text editing for configuration files.
- Access to the Protein Data Bank (PDB) for downloading protein structures.

## Support

If you encounter any issues or have questions, please refer to the `example_configs` directory for guidance on common configurations. For further assistance, feel free to open an issue in the repository or consult the community forums linked in the [Additional Resources](../05_Additional_Resources/useful_links.md) section.

## Contributing

Your contributions are welcome! If you have suggestions for improving the setup guide or the example configurations, please submit a pull request or open an issue. See the [contributing guidelines](../../CONTRIBUTING.md) for more details on how to contribute.

We hope this module will pave the way for your successful journey into the world of MD simulations!
## Contents of this directory : 02_Setting_Up_Your_First_Simulations
