# Lab exercise 1: solubilisation

Students measure how ethanol (co-solvent), β-cyclodextrin (complexation) and polysorbate 80 (micelles) affect the solubility of paracetamol, sulfadiazine and ibuprofen in water and phosphate buffer pH 7.4. In the exercise class the week after the lab, they import the pooled data, calculate mean and standard deviation of the triplicates, plot the results as grouped bar charts with error bars, and set up the report as a Quarto document.

## Files

| File | Description |
|------|-------------|
| `FA511_databehandling_solubilisering.html` | Guide to data analysis and the report, open in a browser (Danish) |
| `Data.csv`, `Data.xlsx` | Concentrations (mg/ml) for all solubilisers, concentrations and drugs, three replicates each |
| `Kontrol.csv`, `Kontrol.xlsx` | Equilibrated control samples |

The csv files use semicolons and decimal commas, so they are read with `read_csv2()`. The file names must stay as they are, because the code in the guide refers to them. The data are meant for practising the analysis, not as reference values.
