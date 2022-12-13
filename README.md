# nus-dissertation-latex-template

This repository contains a LaTeX template intended to conform to the National University of Singapore's (NUS) stylesheet as documented in _General Guidelines on Format of Research Thesis Submitted For Examination_ (RO.1042/03).  Dissertators should be sure to consult the latest version of RO.1042/03 (available here http://www.fas.nus.edu.sg/ell/download/Graduate/RO1042-03.pdf) for additional details and information.

Beyond specific NUS requirements, the stylistic conventions adopted by this template represent the author's preference. The repository itself may be used as a template from which to structure one's own dissertation project.

This template is designed to be used with the XeLaTeX package.

The template is now also available on [Overleaf](https://www.overleaf.com/latex/templates/nus-dissertation-latex-template/svxnmtdfxymk).  Please report any bugs or improvements here and the Overleaf template will be updated accordingly.


## Organisation

The template is organised into a number of seperate sections and chapters that are intended to be linked to the main document using `\input` statements.  The files below are discussed in the order in which they are used in the dissertation.  

The template is organised as follows:
1) `nus-thss-tmplt.tex` this is the main document
2) `ttlpg.tex` the title page
3) `ttlpg-kcl.tex` an alternate form of the title page for King's College London (KCL) — for use if the dissertator is in a joint degree programme with KCL or other university; in all other respects, the style conventios of NUS should be abided by.  At the time of this wirting, dissertators in Joint Degree Programmes (JDP) are only required to submit a dissertation that conforms to NUS style requirements — even to their JDP university.
4) `dclrtn.tex` the dissertator's signed and dated declaration
5) `acknwldgmnts.tex` is an optional 'Acknowledgements' section — typically not more than a page long
6) `smmry.tex` a summary of the work, typically not more than a page long
7) (The table of contents (TOC) and lists of figures or tables come next, but are typset in-line with the main document)
8) Individual chapters break from the above convention are also written in-line; this is mainly to facilitate convenient text-based searching across the entire document source code
9) (The bibliography and index are also generated in-line, similar to the TOC)
10) `clphn.tex` is a colophon; this page is not required by NUS and no style guidence has been provided.  The selected style of a minipage, typeset in the centre of the page, sans folio, conforms to a widely-accepted convention.  Consider texts, for example, from O'Reilly Media publishing.
