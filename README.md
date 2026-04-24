# Forest Fire Station Placement — Scenario-Based Covering Framework

Companion repository for:

> Özcan, Z., Kabak, Ö., Caglayan, İ. (202X). Forest fire station 
> placement under spatial uncertainty: A scenario-based covering 
> framework applied to Mediterranean forests. *International 
> Transactions in Operational Research*, DOI: [pending].

## Contents

- `code/` — Java implementation of the Scenario-Based Set Covering 
  Model (SSCM), Scenario-Based Maximal Covering Model (SMCM), 
  Expected Fire Location Problem (EFLP), and scenario generation 
  via inverse transform sampling.
- `data/` — Aggregated 1 km × 1 km risk map of the Antalya region 
  used in the case study (Section 6 of the paper).
- `dss/` — Spreadsheet-based decision support tool (Excel + VBA).

## Requirements

- Java 11 or later
- Gurobi 10.1 with an academic license 
  ([gurobi.com/academia](https://www.gurobi.com/academia/))
- Microsoft Excel 2016+ for the decision support tool

## Citation

If you use this code or data, please cite the paper above.

## License

MIT License — see `LICENSE` file.

## Contact

Zühal Özcan, Bahçeşehir University  
`zuhal.ozcanyavuz@bau.edu.tr`
