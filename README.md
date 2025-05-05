# EC_SHE: Weak Decay Data in Superheavy Nuclei

This repository contains data associated with:

**A. Ravlic and W. Nazarewicz**  
*Weak decays in superheavy nuclei*  
_To be published in Physical Review C Letters_

---

## Directory Structure

The data is organized into two directories, each corresponding to a different energy density functional used in the calculations:

- `data_DDPC1/` — results obtained with the **DD-PC1** functional  
- `data_DDPCX/` — results obtained with the **DD-PCX** functional  

Each directory includes:

- `results_EC.txt` — Electron capture and β⁺-decay data  
- `results_Bm.txt` — β⁻-decay data  

---

## File Format

Each `.txt` file is a plain-text table with the following columns:

| Column         | Description |
|----------------|-------------|
| `nucl`         | Nucleus identifier |
| `dec`          | Decay type (`HL+` denotes EC and β⁺ decay) |
| `Total(s)`     | Total weak-decay half-life (in seconds) |
| `Bp(J^π)(s)` or `Bm(J^π)(s)` | Partial half-lives for β⁺ or β⁻ decay channels with specified multipolarity *J^π* (in seconds) |
| `EC(J^π)(s)`   | Electron capture half-life for each multipolarity *J^π* (in seconds) |

All half-lives are reported in **seconds**.

---

## Citation

If you use this data, please cite:

A. Ravlic and W. Nazarewicz, *Weak decays in superheavy nuclei*, to be published in **Phys. Rev. C Letters** (2025).
ArXiv preprint arXiv:2409.04620 [nucl-th]
