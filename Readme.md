# My Latex resume

Linkedin serves well, but not in all situations. At some point my profile just
cluttered up, while all I wanted 'them' to have is a good looking two page
resume. Naturally turned to Latex.

Looking at some Latex resumes online I found one that I really liked, so I gave
it my best shot. The I documented my effort here on Github as I expect more
geeks want their resume to be typeset like this.

It uses TeX Gyre Pagella, a font similar to Pallatino that is often used for
books. When compiled with XeLaTeX it has 'lower case numerals', which I think
look very nice.

Except the horizonal lines and bullets everything is made of text. Hyper-refs
are used where applicable, all in dark blue so 'print safe'.

A 'last updated at\*\* date is printed on the top-right of the page.

Obviously it only relies on open source stuff.

## Generating the PDF

### Linux

```
  # Debian
  sudo apt-get install texlive-full

  # Fedora
  sudo dnf install -y texlive-scheme-full

  # openSUSE
  sudo zypper install -y texlive-scheme-basic

  # Generate resume on pdf format
  pdflatex jvillasante-resume.tex
```

### OSX

```
  $ brew install mactex --cask
  $ pdflatex jvillasante-resume.tex
```
