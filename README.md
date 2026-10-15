# How We Found Out

**Evidence, Error, and the Making of Medical Knowledge**

*How We Found Out* is a history of the evidence behind medicine. It follows how observations, experiments, clinical trials, and public-health measures changed what people understood about disease and how they cared for patients.

Rather than presenting discovery as a series of isolated breakthroughs, the book looks at how claims were tested, challenged, and put into practice. It also considers uncertainty, professional resistance, unequal access, and the limits and risks that accompany medical progress.

## What the book covers

The chapters span the development of medical knowledge and care, including:

- Infectious disease, germ theory, cholera, sanitation, and clean water
- Vaccines, antibiotics, penicillin, and the rise of antimicrobial resistance
- Insulin, blood groups, transfusion, and other advances in treatment
- Medical imaging, laboratory testing, anesthesia, surgery, and intensive care
- Genetics, DNA sequencing, gene therapy, and modern vaccine technologies
- Medical devices, rehabilitation, dentistry, and present-day health challenges

Chapters include historical context, discussion of the evidence, and timelines. Citations and further reading are collected in the source manuscript's bibliography.

## Read the book

The latest compiled edition is [`med_history.pdf`](med_history.pdf). The complete LaTeX manuscript is [`med_history.tex`](med_history.tex).

## Build the PDF

The book is maintained as a single LaTeX source file. Install a LaTeX distribution such as TeX Live or MiKTeX with `pdflatex` and the packages used in the source, then run the following from the project directory:

```sh
pdflatex -interaction=nonstopmode -halt-on-error med_history.tex
pdflatex -interaction=nonstopmode -halt-on-error med_history.tex
```

Run LaTeX twice so the table of contents, links, and cross-references can settle. The resulting PDF is `med_history.pdf`. Auxiliary build files are excluded from version control.

## Scope

This is an educational work about the history and development of medicine. It is not medical advice and should not be used to diagnose or treat a health condition.
