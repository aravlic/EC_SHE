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

### Supplemental Material Data
In directory `supplemental_material` data used to generate Figs. S2--S3 can be found. To get the Fig. S2, the file
`results_No_stat_unc_0218.txt` contains only the EC contribution for $1^+$ and $1^-$ transitions, together with
1$\sigma$ uncertainties (denoted as ` dEC(1+)(s)` and ` dEC(1-)(s)`).

The data required to reproduce Fig. S3 is stored in files formatted as `results_Hs_RDIP.txt`, where `RDIP` stands for
the type of transition that is explicitly excluded from the calculation of the rate. Note that files for Hs contain both
EC and $\beta^+$ contribution, while files for Rf are $\beta^-$ only.

## File Format

Each `.txt` file is a plain-text table with the following columns:

| Column         | Description |
|----------------|-------------|
| `nucl`         | Nucleus identifier |
| `dec`          | Decay type (`HL+` denotes EC and β⁺ decay) |
| `Total(s)`     | Total weak-decay half-life (in seconds) |
| `Bp($J^\pi$)(s)` or `Bm($J^\pi$)(s)` | Partial half-lives for β⁺ or β⁻ decay channels with specified multipolarity $J^\pi$ (in seconds) |
| `EC($J^\pi$)(s)`   | Electron capture half-life for each multipolarity $J^\pi$ (in seconds) |

All half-lives are reported in **seconds**.

---

## Citation

If you use this data, please cite:

A. Ravlic and W. Nazarewicz, *Weak decays in superheavy nuclei*, to be published in **Phys. Rev. C Letters** (2025).
[ArXiv preprint arXiv:2409.04620 [nucl-th]](https://arxiv.org/abs/2409.04620)

