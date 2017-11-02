# parse_bib

This is a simple script that parses a bibtex file and generates the markdown files for the [Hugo academic theme](https://github.com/gcushen/hugo-academic). 

The script relies on [bibtexparser](https://github.com/sciunto-org/python-bibtexparser) to get the individual entries from the bibtex file with your publications and then generates a .md file for each one of them under */content/publications/* and a .bib file with the same name under *static/files/citations/*.

## Use

Simply download the script in your root website folder (e.g., next to the .toml file), make sure that you have [bibtexparser](https://github.com/sciunto-org/python-bibtexparser) installed and run:

    python parse_bib.py -i <inputfile>.bib

or,

    python.exe parse_bib.py -i <inputfile>.bib
  
 
