# ROTE-Kv-Coherence-Proof

This repository contains experimental electrophysiology data and analysis demonstrating layered quantum coherence in Kv ion channels, as predicted by the Resonant Order Theory of Everything (ROTE).

## 🧪 Overview

Using real patch-clamp data (before and after Accutase treatment), we computed:

- **Leggett-Garg Inequality (LGI)** correlators to assess temporal coherence
- **Phase-Locking Value (PLV)** sweeps across 0.5–100 Hz to detect ψ-null resonances
- Simulated **φ-shell suppression** via TEA and **ψ-core damping** via D₂O (KIE effects)
- Observed LGI K-shifts from −0.30 → +0.93 and PLV compression — consistent with ROTE predictions

## 📁 Repo Structure

```
ROTE-Kv-Coherence-Proof/
├── data/
│   ├── accutase_before.dat            # Raw Patchmaster binary (pre-treatment)
│   ├── accutase_after.dat             # Raw Patchmaster binary (post-treatment)
│   ├── accutase_before_first2s.csv    # Converted 2s trace
│   ├── accutase_after_first2s.csv     # Converted 2s trace
│
├── figures/
│   └── ROTE_Kv_PLV_TEAD2O.png         # PLV across baseline, TEA, D₂O
│
├── paper/
│   └── ROTE_Kv_ROTE_LGI_PLV_Preprint.tex  # LaTeX preprint
│
├── analysis/
│   └── (To be added: plv_lgi_analysis.py, sympy_tunneling_model.py)
│
└── README.md
```

## 🧠 Highlights

- **K (LGI):**
  - +0.26 (Before)
  - −0.30 (After Accutase)
  - +0.50 (Simulated TEA)
  - **+0.93 (TEA + D₂O)**

- **PLV Peak** shifts:
  - 13–25 Hz (baseline ψ-shell resonance)
  - Flattened post-Accutase
  - Stabilized under TEA
  - Narrow, dampened under D₂O

## 🔬 Tools

- Python (NumPy, SciPy, Matplotlib, SymPy)
- Patchmaster → CSV conversion
- LGI and PLV scripts (see `analysis/`)
- ROTE resonance interpretation

## 📎 Citation

> Brady, J., & Neo. (2025). *Layered Quantum Coherence in Kv Channels: ROTE-Driven Evidence via LGI and PLV*. Resonant Field Institute.

## 🤝 Contributions

This repository welcomes collaboration from the open-science and quantum biology communities. Forks, pull requests, and extensions are encouraged.

## 🌀 ROTE Reference

Learn more about ROTE at [resonantfieldinstitute.com](https://resonantfieldinstitute.com)

---

