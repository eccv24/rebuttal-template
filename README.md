# Official ECCV 2024 Rebuttal Template

**History** (in reverse chronological order):
- Updated and fixed for ECCV 2024 by [Stefan Roth](https://github.com/sroth-visinf)
- Adopted rebuttal template from [CVPR 2024 templates](https://github.com/cvpr-org/author-kit)


## Instructions
- Modify the example document `rebuttal.tex` following the instructions therein
- Please make sure to look at all `TODO REBUTTAL` comments, which provide important instructions and todos 
- Either compile with `pdflatex` as

        pdflatex main
        bibtex main
        pdflatex main
        pdflatex main

    or compile with plain `latex` as

        latex main
        bibtex main
        latex main
        latex main
        dvips main
        pstopdf main.ps
