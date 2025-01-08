# Resume
LaTex template files for my personal resume

Based off of [sb2nov/resume](https://github.com/sb2nov/resume/)

## Prerequisites

### System Wide dependency

```bash
sudo pacman -S texlive-core texlive-formatsextra texlive-latexextra
```

### Compile to PDF

```bash
pdflatex ajay_resume.tex
```

### Compile to JPG

```bash
magick -density 300 ajay_resume.pdf resume.jpg
```
![Resume Preview](./images/resume.jpg)
