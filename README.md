## Jack Fenn

M.S. in AI & Computational Drug Discovery and Development, UCSF. Biochemist by training,
now working on evaluation and benchmarking for ML in drug discovery.

Currently ML Bioengineer at Varosync. Previously Shoichet Lab and Bivona Lab at UCSF.

---

### Repositories

**[boltz2-sea-offtarget](https://github.com/j-fenn/boltz2-sea-offtarget)** ·
Re-analysis of a Boltz-2 vs SEA off-target benchmark, rebuilt from the Lounkine 2012 supplementary
data. Both structural confidence metrics — the composite score and ipTM — separate confirmed binders
from confirmed non-binders at chance (within-target AUC 0.527 and 0.486), while the affinity outputs
reach 0.68–0.71. Also documents a back-transform inconsistency that reversed a reported conclusion,
and an audit finding 18% of model inputs carried expression-construct scaffold.
`Python · RDKit · scikit-learn`

**[perturbation-readouts](https://github.com/j-fenn/perturbation-readouts)** ·
GEARS reproduction on Norman/Adamson/Dixit with every common readout computed on identical
predictions. Choosing between two MSEs moves the number by 10–41×; pairing them across models
manufactures a 17–35× "improvement" between models within 4–37% of each other. Direction accuracy
sits at 0.19 across all genes and climbs to 0.77 once genes without a measurable response are
excluded, 91–96% of true deltas are within 1.96 SE of zero.
`PyTorch · PyTorch Geometric · scanpy`

**[stk11-3d-remodeling](https://github.com/j-fenn/stk11-3d-remodeling)** ·
Hi-C, ATAC and ChIP pipeline for 3D genome remodeling under KRAS-inhibitor resistance across STK11
contexts. Differential contact analysis without biological replicates, a scored ranking rather than
manufactured p-values, plus seven pretrained sequence-to-function models and the two silent failure
modes (assembly mismatch, chimeric read loss) that nearly ruined it. Ships no study data; runs end to
end on a synthetic fixture.
`Python · cooler · cooltools · pairtools · Nextflow`

---

### What I work on

Model evaluation and benchmarking · perturbation modelling · structure and sequence-to-function
models · multi-omics pipelines · pharmacovigilance data engineering

`Python` `PyTorch` `PyTorch Geometric` `scanpy` `RDKit` `cooler/cooltools` `Nextflow` `Docker` `AWS` `SQL` `R`

---

San Francisco · [LinkedIn](https://www.linkedin.com/in/jackfenn/) · jack.fenn@ucsf.edu
