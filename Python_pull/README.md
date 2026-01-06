# python-pull

Notebooks that pull Swedish regional statistics from SCB (PXWeb), reshape the results to tidy tables, and write CSV outputs to `data/`.

## Notebooks

- `notebooks/01_Population_Density.ipynb`: Population density (per km²) by county for the latest available year → `data/Pop_density.csv`
- `notebooks/02_UnempDirect.ipynb`: Unemployment rate (LFS, 15–74) by county for the latest available quarter → `data/UnempDirect.csv`

## Data sources

- Population density: https://www.statistikdatabasen.scb.se/pxweb/en/ssd/START__BE__BE0101__BE0101C/BefArealTathetKon/table/tableViewLayout1/
- Unemployment (direct estimates): https://www.statistikdatabasen.scb.se/pxweb/en/ssd/START__AM__AM0401__AM0401N/NAKUBefolkningLK/table/tableViewLayout1/

