![Project Logo](assets/banner.png)

![Coverage Status](assets/coverage-badge.svg)

<h1 align="center">
MCGA
</h1>

<br>


rename name of project and package as MCGA and mcga

## 🔥 Usage

```python
from mcga import main_func

# One line to rule them all
result = main_func(data)
```

This usage example shows how to quickly leverage the package's main functionality with just one line of code (or a few lines of code). 
After importing the `main_func` (to be renamed by you), you simply pass in your `data` and get the `result` (this is just an example, your package might have other inputs and outputs). 
Short and sweet, but the real power lies in the detailed documentation.

## 👩‍💻 Installation

## ♻️ 12 Principles of Green Chemistry Check‐List

!!! This is just an example of criteria. !!!
| Principle                                          | “Green” if…                                                                                                   |
| -------------------------------------------------- | ------------------------------------------------------------------------------------------------------------- |
| 1. Prevention of Waste                             | E-factor < 25 or PMI < 100                                                                                     |
| 2. Atom Economy                                    | % Atom Economy ≥ 90 %                                                                                          |
| 3. Less Hazardous Syntheses                        | No GHS Acute Tox. Cat. 1–2 or Carc/Muta Reagents                                                                |
| 4. Designing Safer Chemicals                       | Final product LD₅₀ (oral, rat) > 2 000 mg/kg; no ≥ Cat 1 aquatic tox                                           |
| 5. Safer Solvents & Auxiliaries                    | All solvents from CHEM21 “recommended”; auxiliaries ≤ 10 % w/w                                                   |
| 6. Design for Energy Efficiency                    | Reaction T ≤ 50 °C and ambient pressure only                                                                    |
| 7. Use of Renewable Feedstocks                     | ≥ 50 % of all C-atoms from bio-based feedstocks                                                                 |
| 8. Reduce Derivatives                              | ≤ 1 protection/deprotection step                                                                                |
| 9. Catalysis                                       | Uses catalyst loading ≤ 10 mol %                                                                                 |
| 10. Design for Degradation                         | Predicted half-life < 60 days; no PBT flags                                                                     |
| 11. Real-Time Analysis for Pollution Prevention    | ≥ 1 in-line monitor (FTIR, GC, HPLC…)                                                                            |
| 12. Inherently Safer Chemistry (Accident Prevention) | All reagents flash-point ≥ 60 °C; no peroxides or explosophoric groups                                          |



Create a new environment, you may also give the environment a different name. 

```
conda create -n mcga python=3.10 
```

```
conda activate mcga
(conda_env) $ pip install .
```

If you need jupyter lab, install it 

```
(mcga) $ pip install jupyterlab
```


## 🛠️ Development installation

Initialize Git (only for the first time). 

Note: You should have create an empty repository on `https://github.com:jihokeum/mcga`.

```
git init
git add * 
git add .*
git commit -m "Initial commit" 
git branch -M main
git remote add origin git@github.com:jihokeum/mcga.git 
git push -u origin main
```

Then add and commit changes as usual. 

To install the package, run

```
(mcga) $ pip install -e ".[test,doc]"
```

### Run tests and coverage

```
(conda_env) $ pip install tox
(conda_env) $ tox
```



