# Scraps

## Status
1. Introduction: Draft, copied from Latex
2. Foundations: Draft, copied from Latex
3. Ethics: Draft, copied from Latex
4. Design: Draft, copied from Latex
5. Measuring: Draft, copied from Latex
6. Data: Draft, copied from Latex
7. Sampling: Draft, copied from Latex
8. Surveys: Not Started
9. Interviews: Not Started
10. Experimental: Not Started
11. Field: Not Started
12. Unobtrusive: Not Started
13. Interpretive: Not Started
14. Mixed: Not Started
15. Presenting: Not Started
16. References: Empty

## Footnotes
To create a footnote:

^[See whatever]

## Bibtex Reference
1. enter the bibtex reference in "book.bib"
2. copy the shortref from the first line of the bibtex entry
3. paste into the text in this format: (@hughes2006evidence)

# RegEx Notes
Find single digits in dollar signs
\$( \d+ )\$
Replace with
$1

Find all section headers
\\section\{(.*)\}
Replace with ##
## $1

Find all single word italics
\\textit\{(\S+)\}
Replace with
_$1_


Find all italics phrases
\\textit\{(.*)\}
Replace with
_$1_

# Boxes and Highlighting

My defined DIV Box styles: grsnote and grswarn
Note: do not put line feeds after the opening tag or before the closing tag - that creates extra blank lines in the output.

<div class="grsnote">x</div>

For in-line highlighting 
(the color is the same pale yellow used in my note box)

<span style="background-color: #ffff99; font-style: italic;">x</span>

# Cross refs

Example:
[text](/target#x)

**NOTE: the markdown code makes all header links lower case and spaces are replaced with hyphens.**

# Math Formulas  

Math block: \[ A + \beta = \pi r ^ 2 \]
Inline formula: \(\pi r^2\) -- it shows up.

* The MathJax link for the header (not needed but link here for future ref):
<script type="text/javascript"
  src="https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.5/latest.js?config=TeX-MML-AM_CHTML" async></script>
