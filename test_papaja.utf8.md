---
title: Does Music Convey Social Information to Infants?
shorttitle: Title
author: Mehr, Song\textsuperscript{1}\ \& Spelke\textsuperscript{1,2}
affiliation:
- id: '1'
  institution: Wilhelm-Wundt-University
- id: '2'
  institution: Konstanz Business School
authornote: |
  Add complete departmental affiliations for each author here. Each new line herein must be indented, like this line.

  Enter author note here.
abstract: "One or two sentences providing a **basic introduction** to the field,  comprehensible
  to a scientist in any discipline. Five month old infants were exposed to one of
  two novel songs containing different melodies with lyrics and rhythms being the
  same. Infants either heard the songs through a toy in which their parent's voice
  was recorded or was sung live by a friendly unfamiliar person initially and later
  through video recording. Infant's selective attention was tested by having them
  listen to two presentations of either familiar or unfamiliar songs. Infants payed
  attention to the familiar song, sung by their parent in the past. No infant preference
  was observed between the toy onto which parent's voice was recorde or a video recording
  of an unfamiliar person, briefly met by an infant initially. Infants in the later
  two conditions retained the memory of the melody for longer than 8 months. These
  findings suggest that songs performed by parents at home convey social meaning to
  a child.  \n\nTwo to three sentences of **more detailed background**, comprehensible
  \ to scientists in related disciplines.\n\nOne sentence clearly stating the **general
  problem** being addressed by  this particular study.\n\nOne sentence summarizing
  the main result (with the words \"**here we show**\" or their equivalent).\n\nTwo
  or three sentences explaining what the **main result** reveals in direct comparison
  to what was thought to be the case previously, or how the  main result adds to previous
  knowledge.\n\nOne or two sentences to put the results into a more **general context**.\n\nTwo
  or three sentences to provide a **broader perspective**, readily comprehensible
  to a scientist in any discipline.\n\n<!-- https://tinyurl.com/ybremelq -->\n\n!!!papaja-author-note(Add
  complete departmental affiliations for each author here. Each new line herein must
  be indented, like this line.\n\nEnter author note here.\n\n\nCorrespondence concerning
  this article should be addressed to Mehr, Song, Postal address. E-mail: my@email.com)papaja-author-note!!!"
keywords: keywords
wordcount: X
bibliography:
- r-references.bib
- mybib.bib
floatsintext: no
figurelist: no
tablelist: no
footnotelist: no
linenumbers: yes
mask: no
draft: no
documentclass: apa6
classoption: man
output: papaja::apa6_pdf
header-includes:
- \shorttitle{Title}
- |-
  \affiliation{
  \vspace{0.5cm}
  \textsuperscript{1} Wilhelm-Wundt-University\\\textsuperscript{2} Konstanz Business School}
- '\keywords{keywords\newline\indent Word count: X}'
- \usepackage{csquotes}
- \usepackage{upgreek}
- \captionsetup{font=singlespacing,justification=justified}
- ''
- \usepackage{longtable}
- \usepackage{lscape}
- \usepackage{multirow}
- \usepackage{tabularx}
- \usepackage[flushleft]{threeparttable}
- \usepackage{threeparttablex}
- ''
- \newenvironment{lltable}{\begin{landscape}\begin{center}\begin{ThreePartTable}}{\end{ThreePartTable}\end{center}\end{landscape}}
- ''
- \makeatletter
- \newcommand\LastLTentrywidth{1em}
- \newlength\longtablewidth
- \setlength{\longtablewidth}{1in}
- '\newcommand{\getlongtablewidth}{\begingroup \ifcsname LT@\roman{LT@tables}\endcsname
  \global\longtablewidth=0pt \renewcommand{\LT@entry}[2]{\global\advance\longtablewidth
  by ##2\relax\gdef\LastLTentrywidth{##2}}\@nameuse{LT@\roman{LT@tables}} \fi \endgroup}'
- ''
- ''
- \DeclareDelayedFloatFlavor{ThreePartTable}{table}
- \DeclareDelayedFloatFlavor{lltable}{table}
- \DeclareDelayedFloatFlavor*{longtable}{table}
- \makeatletter
- \renewcommand{\efloat@iwrite}[1]{\immediate\expandafter\protected@write\csname efloat@post#1\endcsname{}}
- \makeatother
- |-
  \usepackage{lineno}

  \linenumbers

---





Introduction - Music is a universal phenomenon that captures our imaginations throughout our lifetime, starting from early childhood. Parents usually sing to their infants and children in a globally recognizable style of singing.

## subheader

# Methods
We report how we determined our sample size, all data exclusions (if any), all manipulations, and all measures in the study. <!-- 21-word solution (Simmons, Nelson & Simonsohn, 2012; retrieved from http://ssrn.com/abstract=2160588) -->

## Participants

## Material

## Procedure

## Data analysis
We used R [Version 3.5.2; @R-base] and the R-packages *data.table* [Version 1.12.0; @R-data.table], *dplyr* [Version 0.8.0.1; @R-dplyr], *papaja* [Version 0.1.0.9842; @R-papaja], *pwr* [Version 1.2.2; @R-pwr], and *summarytools* [Version 0.9.2; @R-summarytools] for all our analyses.



```
## Warning: package 'summarytools' was built under R version 3.5.3
```








![ ](test_papaja_files/figure-latex/unnamed-chunk-5-1.pdf) 

# Results
lets say we want to make a figure
if we wanted to find power

```
## Warning: package 'pwr' was built under R version 3.5.3
```

```
## 
##      Two-sample t test power calculation 
## 
##               n = 44
##               d = 0.8
##       sig.level = 0.05
##           power = 0.9599534
##     alternative = two.sided
## 
## NOTE: n is number in *each* group
```



![(\#fig:myfig)this is a histograpm](test_papaja_files/figure-latex/myfig-1.pdf) 

![ ](test_papaja_files/figure-latex/unnamed-chunk-8-1.pdf) 

```
## [1] 0.5210967
```


```
## [1] 0.1769651
```


```
## [1] 0.1769651
```
# Discussion


\newpage

# References


Mehr, S. A., Song. L. A., & Spelke, E. S. (2016). For 5-month-old infants, melodies are social. Psychological Science, 27, 486-501
@crump2013evaluating did some experiments

\begingroup
\setlength{\parindent}{-0.5in}
\setlength{\leftskip}{0.5in}

<div id = "refs"></div>
\endgroup
