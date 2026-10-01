# scientific writing

My scientific writing — LaTeX manuscripts typeset in APA 7th edition.

## papers

- **Effects of Interference and Task-Switching Demands on Completion Time in D-KEFS Color-Word Interference** — PSY 410, Fall 2026. `Ta_PSY410_Experiment1.tex`
- **Tobacco Smoke Remediation Practices Among Residential Cleaning and Restoration Professionals in San Diego County** — CTE lab project under PSY 499 supervised research with Dr. Georg E. Matt, May 2026. `Ta_PSY499_Tobacco_Smoke_Remediation.tex`
- **Smoking and Vaping Policies in Newly Constructed, State-Funded Multiunit Housing in California** — methods section from a CTE lab project. `Ta_MUH_Smoking_Vaping_Policies_Methods.tex`

## compiling

Each paper is a standalone `.tex` file built on the `apa7` document class.
Figures are drawn in-document with `pgfplots`, so no external image files are needed.

Compile with `pdflatex` (run twice so cross-references resolve). Requires a standard TeX Live / MiKTeX install with the `apa7` and `pgfplots` packages.
