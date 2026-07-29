Research Proposal and Systematic Survey
This repository contains two separate academic works prepared as part of the Master of Information Technology program.
Repository Structure

research-proposal/
├── main.tex
├── proposal.pdf
└── Survey/
├── main_conf.tex
├── AI_Integrated_Edge_Fog_IoT.pdf
├── IEEEtran.cls
├── prisma.png
├── road2.png
└── README.md


1\. Research Proposal

Title:
*A Comparative Benchmarking Framework for Improving Data Analysis Efficiency Using Recurrent Deep Learning Architectures*

The proposal compares recurrent deep-learning architectures, including LSTM, BiLSTM, and GRU, against a traditional statistical baseline. It focuses on predictive accuracy, computational efficiency, reproducibility, and fair benchmarking.

### Files

* [`main.tex`](main.tex): LaTeX source of the research proposal.
* [`proposal.pdf`](proposal.pdf): Compiled PDF version.

## 2\. Systematic Survey

**Title:**  
*AI-Integrated Edge-Fog IoT Architectures: A PRISMA-Based Taxonomy and Systematic Review*

The survey presents a PRISMA-based review and a three-dimensional taxonomy covering architecture, intelligence mechanisms, and system functionality in AI-integrated Edge-Fog IoT environments.

### Files

* [`Survey/main\_conf.tex`](Survey/main_conf.tex): IEEE conference-format LaTeX source.
* [`Survey/AI\_Integrated\_Edge\_Fog\_IoT.pdf`](Survey/AI_Integrated_Edge_Fog_IoT.pdf): Compiled survey paper.
* [`Survey/IEEEtran.cls`](Survey/IEEEtran.cls): IEEE LaTeX class file.
* [`Survey/prisma.png`](Survey/prisma.png): PRISMA study-selection diagram.
* [`Survey/road2.png`](Survey/road2.png): Research roadmap figure.

## Compilation

### Research Proposal

Compile `main.tex` using a LaTeX distribution such as TeX Live, MiKTeX, or Overleaf.


pdflatex main.tex
pdflatex main.tex


### Systematic Survey

Open the `Survey` directory and compile `main\_conf.tex`.


cd Survey
pdflatex main\_conf.tex
pdflatex main\_conf.tex


Running LaTeX twice ensures that references, citations, figure numbers, and the table of contents are updated correctly.

## Author

**Abeer Morgan**  
Department of Information Technology  
Faculty of Computer and Information Technology  
Sana'a University, Yemen

## Academic Use

This repository is maintained for academic submission, review, and reproducibility purposes.
