##ABOUT##

Author: Ibrahim, Ibrahim Opeyemi
Author's email: ibrahim.ibrahim13@kwasu.edu.ng; ibrahimibrahimopeyemi@gmail.com
Version: 1.0.0
Licence: This script is provided under the MIT Licenses.
This script was written to facilitate the retrieval of 
3D structures from "https://pubchem.ncbi.nlm.nih.gov/" in SDf format using 
puchem cid.
This version is rigid in the sense that:
    1)it compel users to provide an excel spreedsheet with the first 
    and second column containing the preferred name and the cid, 
    respectively.
    2)Molecules downloaded are automatically named using the 
    Molecule's name, a delimiter "_@_", and the compound cid for each
    record
Future version will supported
    1)different file format such as SMILES
    2)retrieval of compound record in a .txt file
    3)flexible directory choice and naming style


##USAGE##
1)  Install pipenv
2)  from the terminal, cd to the project's folder containing pubchem.py
    and pipfile and run "pipenv install"
3)  Activate the virtual environment created using "pipenv shell" command
3)  Copy your spreedsheetfile (xlsx format) containing the records to the 
    same directory/folder as the pubchem.py script
4)  Rename the spreadsheet to "compounds_library_use.xlsx" and ensure
    the first column contains names "e.g common names" corresponding to 
    cid. This is for easy identification of downloaded compound.Please note that each compounds
will be name with it cid prefixed the name provided.

5) create a "downloads" folder in the same directory
6) run the script in the terminal.
7) user will be notified if a particular record search yields no results
Thank you for using this simple scripts, and I wish success in your projects.


##ACKNOWLEDGEMENTS##
I would like to recognize the following authors for providing their packages
under the MIT  licence
Matt Swain for providing the python package "PubChemPy==1.0.4". 
Eric Gazoni, Charlie Clark for providing "openpyxl==3.0.9"
