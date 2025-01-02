# ISA Base Environment Setup

Welcome to the ISA Base Environment setup guide! This repository provides the ISA_base_environment.yml file, which defines the exact python development environment used by ISA (International Spy Agency) developers. By using this environment, you ensure compatibility with the tools and libraries that ISA developers use to create cutting-edge spy-themed applications and systems.

## Steps to Install and Run the Environment
Follow these steps to set up your environment and start using the same tools as the ISA development team:

## Prerequisites:
Install Miniconda or Anaconda: To get started, you’ll need Miniconda or Anaconda installed on your machine. If you don’t have them yet, you can download and install one of the following:
Miniconda
Anaconda

## 1. Clone the Repository (or Download the YAML File):
To get the ISA_base_environment.yml file, you can either clone the repository using Git:

`cd ~ `

`git clone https://github.com/SpyExpert/ISA_Base_Env.git `

Alternatively, you can download the ISA_base_environment.yml file directly from the GitHub repository.

## 2. Create the Conda Environment:
First check your list of environments:
conda info --envs

Once you have the ISA_base_environment.yml file, create your Conda environment by running:

`cd ~/ISA_Base_Env`

`conda env create -f ISA_base_environment.yml`

## 3. Activate the Environment:
After the environment has been successfully created, activate it with the following command:

`conda activate ISA_base`


## 4. Verify the Installation:
To ensure everything is set up correctly, you can verify the installed packages with:


`conda list`

You should see all the packages installed as defined in the environment.

## 5. Using environment in VScode:
To use it in VScode or any other code editor, simply choose the environment.

## 6. Start Working with the Environment:
You’re now ready to start working within the ISA Base Environment! This environment includes all the tools and libraries necessary for building and testing the software used by ISA developers. Begin using the environment to work on your own projects or explore the tools we’ve set up for you.
## 7 Uninstallation
To deactivate any conda environment simply run: `conda deactivate`

To Uninstall the environment:
`conda env list `

Identify the name of the one you want to install.

Run command to uninstall:

`conda env remove --name ISA_base`

Confirm Removal:

`conda env list`

## Need Help?
If you encounter any issues or have questions, feel free to visit our website: www.isaofficial.xyz or contact spyexpert@isaofficial.xyz. The ISA team is here to assist you in making sure everything works smoothly. Also join one of the best intelligence communities, the ISA community with the best agents to help you out: https://discord.gg/mumatr3cCT

