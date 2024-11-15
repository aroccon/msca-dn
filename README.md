# MSCA-DN

Doctoral Network proposal template
Upated according to template 2024.

There are three documents here:
* PartB1.tex: Part B1
* PartB2.tex: Part B2
* master.tex: Both parts in one document to ease the way it's built on overleaf.

There are couple of macros for adding comments:
* `\note{A note}`
* `\todo{Who}{What}` (also appears in table of contents)

To get rid of these, just remove the option `draft` from `\usepackage[draft]{msca-dn}`

To set the width of tables, start with the fact that we're on A4 paper with 15mm margins, so 210-30 = 180mm.
Within that 180, each column has 5mm of space; 2.5mm at each side.  So for, say, 5 columns we have 25mm of space (180-25 = 155).  The remaining set widths should add up to 155mm.

