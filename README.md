


# Scope

This repostory contains demo notebooks using the PDS API (see https://github.com/NASA-PDS/pds-api).


# Prerequisites

- python 3.7


# Quickstart


    python -m venv venv
    pip install -r requirements.txt
    jupyter-lab
    
    
Enjoy the jupyter notebooks provided there (/notebooks/):
- Osiris-REX OVIRS instrument collection:
    - Part1: explore the collection (notebooks/pds-api-client-ovirs-part1-explore-a-collection.ipynb)
    - Part2: find and visualize specific datasets (notebooks/pds-api-client-ovirs-part2-find-data.ipynb)
    
- api-client: very simple demo of the PDS API client 
- wwt: attempt to use PDS data in WWT (https://pywwt.readthedocs.io/en/stable/) through the PDS API (to be done)