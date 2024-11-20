# Overview
This repo holds the data and scripts used for Will St. John's independent study into CONs with John (Jay) Gallagher III. during the Fall of 2024. Below is a file tree with brief descriptions of each file/folder. Note, the primary information are in the bolded **`data/`** directory and **`CONs.qmd`** quarto file.
# File Structure
- `2023-2024/` - contains the work of the previous year's independent study with Lila Schisgal; likely not containing any pertinent information
- **`data/`** - data directory
  - `CONTargetList_filled.csv` - complete list of target with entries filled to best ability
  - `CONTargetList_filled.dat`
  - `CONTargetList_filled.tbl`
  - `CONTargetList_NoLeroyMass.csv` - list of targets with no masses in Leroy et al catalog
  - `CONTargets.csv` - original list of targets with missing values
  - `table_irsa_catalog_search_results.csv` - WISE-crossmatched target list of target potentions and WISE magnitudes
  - `table_irsa_catalog_search_results.tbl`
- `forms/` - beuracracy paperwork required to complete independent study; likely not pertinent
- `CONs.html` - rendered output of `CONs.qmd`
- **`CONs.qmd`** - primary document for analysis and visulizations
- `coordinates.ipynb` - notebook to convert coordinates into degrees
- `ipac_table_formatter.ipynb` - notebook to convert complete list of targets into a ipac-friendly table for WISE crossmatch
- `WISE_leroy_method.ipynb` - notebook to convert WISE-crossmatched target list search results into a csv for easier interation with `CONs.qmd`
