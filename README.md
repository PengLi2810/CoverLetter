# Peng Li — Cover letter for Blykalla

Application for **Senior Thermohydraulic Analyst**, Fluid Systems Engineering, Stockholm.

- [Cover letter (PDF)](Peng_Li_Cover_Letter_Blykalla.pdf)
- [Editable LaTeX source](Peng_Li_Cover_Letter_Blykalla.tex)
- [Official vacancy](https://careers.blykalla.com/jobs/8428493-senior-thermohydraulic-analyst)

The application emphasises conservation-based transient models, heat transfer, 0-D/3-D code coupling, OpenFOAM, scientific programming, parameter studies, and verification and validation. Nuclear system codes and reactor-specific safety methods are presented as development areas.

Ph.D. defence is scheduled for 4 December 2026. Swedish level is A2. The CV separates published papers from unpublished manuscripts.

Build with a standard TeX Live or MiKTeX installation:

```sh
pdflatex -interaction=nonstopmode -halt-on-error Peng_Li_Cover_Letter_Blykalla.tex
pdflatex -interaction=nonstopmode -halt-on-error Peng_Li_Cover_Letter_Blykalla.tex
```

[Previous CorPower application](https://github.com/PengLi2810/CoverLetter/blob/main/Peng_Li_Cover_Letter_CorPower.pdf)

## Compiling on Overleaf

Pull the latest changes from GitHub. In Settings > Compiler, choose **pdfLaTeX** and set **Main document** to `Peng_Li_Cover_Letter_Blykalla.tex` (or `Peng_Li_Cover_Letter_CorPower.tex` for CorPower). Then select **Recompile from scratch** from the Recompile menu.

The sources also compile with XeLaTeX and LuaLaTeX. Unicode-mapping commands specific to pdfTeX are enabled only when supported by the compiler.

If compilation still fails, select **Stop on first error** in the Recompile menu and inspect the first actual LaTeX error in the raw log; the general “didn’t produce a PDF” message does not identify the cause.
