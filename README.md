<p align="center">
  <img src="./banner.svg" width="100%" alt="Riddhika D: Computational Biotechnology" />
</p>

<p align="center">
  <a href="https://github.com/riddhikad9b-ux">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&duration=3500&pause=800&color=2EA043&center=true&vCenter=true&width=680&lines=B.Tech+Biotechnology+%40+Sathyabama%2C+Chennai;Transcriptomics+%E2%80%A2+Comparative+Genomics+%E2%80%A2+Longevity;Reproducible+re-analyses+with+pre-registered+controls;I+report+null+results%2C+not+just+the+wins" alt="Typing intro" />
  </a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Status-2nd%20Year%20B.Tech%20Biotech-203a43?style=flat-square" />
  <img src="https://img.shields.io/badge/Based%20in-Chennai%2C%20India-2c5364?style=flat-square" />
  <img src="https://komarev.com/ghpvc/?username=riddhikad9b-ux&color=2ea043&style=flat-square&label=Profile+Visitors" alt="Visitor Count" />
</p>

---

## 🧬 About Me

I'm a 2nd-year B.Tech Biotechnology student at Sathyabama, Chennai. I build **open, reproducible pipelines** that test biological ideas on public data — with pre-registered questions, expression-matched random-gene-set controls, FDR correction, and a positive control in every analysis.

I report results honestly: most of these are **null or replication results**, and I say so. The goal is a clean, checkable method, not a headline.

- 🌱 **Plant meristem longevity & stress resilience** (Ginkgo, rice, *Arabidopsis*)
- 🧪 **Comparative longevity** — what public datasets do and don't show about ageing
- 📊 **Methods** — transcriptomics, comparative genomics, meta-analysis, epigenetic clocks

---

## ⭐ Featured

### [Sleep-CIRBP](https://github.com/riddhikad9b-ux/sleep-cirbp)
**Does sleep loss lower the cold-inducible DNA-repair factor CIRBP in the brain?**

A cross-dataset re-analysis: in **3 of 3** independent mouse-brain datasets (hippocampus and cortex, 3 labs), *Cirbp* was lower after sleep loss than in rested controls (pooled **p = 0.00016**). Consistent with a temperature-gated view of sleep-dependent DNA repair.

| Dataset | *Cirbp* change (log2) |
|:--|:--:|
| Hippocampus 1 | −0.51 |
| Hippocampus 2 | −0.68 |
| Cortex | −1.06 |

*Honest scope: this is a re-analysis of existing public data, not new wet-lab work. Archived on Zenodo with a DOI (link once minted).*

`Python` `Pandas` `SciPy` `GEOparse` `meta-analysis`

---

## 🔬 Projects

### Longevity & ageing
| Project | What it does | Result |
| :--- | :--- | :--- |
| **[Sleep-CIRBP](https://github.com/riddhikad9b-ux/sleep-cirbp)** | Cross-dataset GEO re-analysis: sleep loss vs *Cirbp* in mouse brain. | **Positive** (3/3 datasets, p = 0.00016) |
| **[CIRBP-Evolution](https://github.com/riddhikad9b-ux/cirbp-evolution)** | Did long-lived mammals evolve a "better" CIRBP? 251 mammals, family-clustered controls. | **Null** — no longevity signal |
| **[Jellyfish-GTEx](https://github.com/riddhikad9b-ux/jellyfish-gtex)** | Do human orthologs of *Turritopsis* expanded genes decline with age? 22 genes × 46 GTEx tissues, 2 matched controls. | **Null** — no age signal |
| **[Aging-Clock-Checker](https://github.com/riddhikad9b-ux/aging-clock-checker)** | Benchmarks published epigenetic clocks (pyaging) on the same public samples; handles clock-type and tissue correctly. | **Validation** (Horvath MAE ≈ 3 yr on blood) |

### Plant meristem & climate resilience
| Project | What it does | Result |
| :--- | :--- | :--- |
| **[Plant-Meristem-Longevity (Ginkgo)](https://github.com/riddhikad9b-ux/Plant-Meristem-Longevity-Research-)** | miRNA age trends in 20/200/600-yr Ginkgo cambium (GSE119213), duplicate-merged, with a positive control. | **Replication** — miR397 ↓ with age (Wang 2020) |
| **[Ginkgo-Stress-miRNA-Aging](https://github.com/riddhikad9b-ux/ginkgo-stress-mirna-aging)** | Do stress/defense miRNAs change with tree age? Same data, new pre-registered question. | **Null** (set p = 0.98; control passed) |
| **[Plant-Meristem-Climate-Resilience (rice)](https://github.com/riddhikad9b-ux/Plant--Meristem---Climate-Resillience)** | Does the flood-tolerance gene SUB1A pause cell division in rice? GEO re-analysis with label checks. | **Null** for cell division (known biology confirmed) |
| **[Space-Botany-Meristem](https://github.com/riddhikad9b-ux/space-botany-meristem)** | Do plant stem-cell genes respond to spaceflight? 8 independent NASA OSDR experiments. | **No consistent response** (incl. auxin lead) |

### Methods & tools
| Project | What it does | Notes |
| :--- | :--- | :--- |
| **[Mars-Closed-Loop-Verification-Engine](https://github.com/riddhikad9b-ux/Mars-closed-loop-verification-engine)** | Fail-closed data-consistency checker for closed-loop life-support data: element/charge balance + 12 validation gates. | Software demo, **23/23 self-tests**, simulated data |

---

## 🛠️ Tools

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Biopython-355F7D?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" />
  <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" />
  <img src="https://img.shields.io/badge/SciPy-8CAAE6?style=for-the-badge&logo=scipy&logoColor=white" />
  <img src="https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white" />
  <img src="https://img.shields.io/badge/Google%20Colab-F9AB00?style=for-the-badge&logo=googlecolab&logoColor=white" />
  <img src="https://img.shields.io/badge/NCBI%20GEO-20639B?style=for-the-badge&logoColor=white" />
  <img src="https://img.shields.io/badge/GTEx-6A1B9A?style=for-the-badge&logoColor=white" />
  <img src="https://img.shields.io/badge/NASA%20OSDR-0B3D91?style=for-the-badge&logoColor=white" />
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" />
</p>

---

<p align="center">
  <i>"Reproducible questions, honest answers — including when the answer is no."</i>
</p>
