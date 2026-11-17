## Hi, I'm Muhammad Waqas

I am a computational medicinal chemist. I build machine learning tools for drug discovery and protein engineering, and I like turning methods into software that other scientists can actually use without writing code.

I am a postdoctoral researcher in the [AI-Driven Drug Discovery Group](https://vhio.net) at the Vall d'Hebron Institute of Oncology (VHIO) in Barcelona. I did my PhD in the Cosconati lab at the University of Campania Luigi Vanvitelli, Italy.

[LinkedIn](https://www.linkedin.com/in/muhammad-waqas-8659261b3/) · [Google Scholar](https://scholar.google.com/citations?user=IL-IPWcAAAAJ) · [ORCID](https://orcid.org/0000-0003-0781-4659) · [ResearchGate](https://www.researchgate.net/profile/Muhammad-Waqas-92)

### What I work on

- Graph neural networks for predicting protein stability across combinatorial mutations
- AI-accelerated ligand-based and structure-based virtual screening of very large compound libraries
- Multi-target drug design, mainly for oncology
- Desktop GUIs that package these workflows for bench scientists

### Software I built

**[StabLyzeGraph](https://github.com/cosconatilab/StabLyzeGraph)**

GNN framework for high-throughput screening of combinatorial protein mutations. Proteins are represented as graphs that combine physicochemical, evolutionary and 3D structural features. It runs in two modes, benchmarking (model tuning) and screening (mutant library generation and ranking), with a PyQt6 interface for Linux and Windows.

- Stack: Python · PyTorch · PyTorch Geometric · Biopython · PyQt6
- Paper: [Protein Science 2026, 35(4), e70534](https://doi.org/10.1002/pro.70534)

**[PyRMD Studio](https://github.com/cosconatilab/PyRMD-Studio)**

GUI suite for AI-powered virtual screening that combines PyRMD (ligand-based) and PyRMD2Dock (structure-based, with AutoDock-GPU) in one application. Vectorizing the core code made screening about 3.3 times faster than the previous release, and Butina clustering with grouped cross-validation keeps similar compounds out of both training and test sets.

- Stack: Python · RDKit · scikit-learn · NumPy · PyQt5
- Paper: [J. Chem. Inf. Model. 2026, 66(11), 6197-6203](https://doi.org/10.1021/acs.jcim.6c00648)

Both tools are developed within the Cosconati lab and hosted on the lab's GitHub.

### Selected publications

- Waqas M, Natale B, Roggia M, Saha PP, Mileni M, Cosconati S. StabLyzeGraph: High-throughput screening of combinatorial mutations using graph neural networks. *Protein Science* 2026. [doi:10.1002/pro.70534](https://doi.org/10.1002/pro.70534)
- Natale B, Waqas M, Roggia M, Di Maro S, Cosconati S. PyRMD Studio: A unified suite for next-generation, AI-powered virtual screening. *J. Chem. Inf. Model.* 2026. [doi:10.1021/acs.jcim.6c00648](https://doi.org/10.1021/acs.jcim.6c00648)
- Poggetti V, et al. Discovery of the first-in-class dual TSPO/carbonic anhydrase modulators with promising neurotrophic activity. *ACS Chem. Neurosci.* 2025. [doi:10.1021/acschemneuro.4c00477](https://doi.org/10.1021/acschemneuro.4c00477)

Full list of 18 papers on [Google Scholar](https://scholar.google.com/citations?user=IL-IPWcAAAAJ).

### Tools I use

- **Cheminformatics and structure:** RDKit, Open Babel, Biopython, AutoDock-GPU, Schrödinger Suite, PyMOL, ChimeraX
- **Machine learning:** PyTorch, PyTorch Geometric, scikit-learn
- **Programming and data:** Python, R, Bash, pandas, NumPy, SciPy, Matplotlib
- **Software and compute:** PyQt5/6, Git, SLURM

### Get in touch

I am happy to talk about collaborations in AI for drug discovery, protein engineering or virtual screening. The quickest way to reach me is [LinkedIn](https://www.linkedin.com/in/muhammad-waqas-8659261b3/) or email at [muhammadwaqas@vhio.net](mailto:muhammadwaqas@vhio.net).
