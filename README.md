# Urban Analytics and City Science

## Unit description and aims

This unit introduces students to the research fields of Urban Analytics and City Science. 
It enables them to utilise cutting-edge methods from these fields and pair them 
with new sources of data to answer urging research questions about cities. Moreover, 
the students will develop a critical understanding of these tools and data as 
well as their applicability and value for urban research, planning and urban policy 
making. Emphasis will be placed on the interactions between digital technologies 
and urban space and the smart city agenda. 

Emphasis will be placed on the *network understanding* of our cities. Networks 
have long formed a distinctive element of urban research. Various sub-fields of 
geography, such as transport, economic and urban geography, are heavily based on 
networks both from a conceptual and an analytical point of view. Moreover, the digital 
revolution and developments related to social media and connectivity as well as 
heightened flows of information within and between urban regions, have greatly enhanced 
the relevance of a network approach to contemporary socio-economic and cultural 
trends. This module will approach the above issues both from a theoretical and practical 
perspective.

The first part of this unit will be dedicated to concepts and tools from social 
network analysis, including hands-on practicals. This part will provide the fundamental 
knowledge of this module. Networks analysis will then lead to the concept of scaling 
in urban science, which will be linked with essential urban economic elements such 
as agglomeration economies and urban hierarchies. The practical knowledge of network 
analysis will be used as a stepping stone to understand ideas and methods from the 
field of transport geography regarding modelling flows within and between cities. 
Common thread here is the network structure which is an essential element of both 
transport geography and social network analysis. The empirical element of this part 
will deal with basic concepts such as gravity models as well as connectivity and 
accessibility measures. 


The unit aims: 

- To enable students to use tools and methods from the Urban Analytics and City 
Science fields in order to answer urban questions. 

- To critically assess the value of new sources of big data in urban research. 

- To use such data and tools to provide theoretically grounded urban research which 
can help urban planners and policy makers to better understand cities. 

- To obtain a broader and critical understanding of how the digital revolution affects 
cities. 

## Intended Learning Outcomes 

1. Be able to creatively utilise cutting edge methods from Urban Analytics and Urban 
Science in order to answer urban research questions. 

2. Be able to critically assess the value of and utilise new sources of big data 
for urban research. 

3. Identify key concepts and theories of digital transformations and smart cities. 

4. Present the results of statistical analysis in a clear, cogent manner, using effective visualizations, tables, and written argument. 


## Assessment details

One 3500-word report (100% of the unit mark) for an urban data analysis project. 
The report will be written in a reproducible manner and will include the necessary code for the data analysis and the outputs (e.g. an Rmarkddown document). 

## Sooftware

All the analysis will be done using `R` and `RStudio`.

## Curiculum 
This is a very indicative list of lectures and practicals.

Describe why networks: from social to spatial.

1. Why cities **L** *ADD UNIT INFO** 

   - Urban Models from Bettencourt
   - Lecture on Urban Economics by Jan Bruckner
   - Cities as complex system: p. 11 Bettencourt, p. 14 scale

2. Smart cities and big data, digital twins **L** *done*

    1. APIs **P**: *done*
    2. digital traces **P**: ??? think of traces
    3. Social Media **P**: Twitter

3. Lecture on networks **L** *done*

4. Network analysis practical 1

5. Network analysis practical 2

    - Csárdi, G., Nepusz, T., & Airoldi, E. M. (2016). Statistical network analysis with igraph. Springer.     Available online at https://www.uni-due.de/hummell/sna/igraph/docs/.BookDraft-CsardiNepuszAiroldi2016.pdf. [*methods*]

    - Degree distribution (see help_degree_sistribution.Rmd)

6. Network science, urban laws and scaling **L** *done*

    -  Build and compare models**P** *done*, *decide if I need to describe sample_* syntax

Network modelling???  *NO*
- @light2020oxford, Ch. 12-15
- @kolaczyk2020statistical Ch 6
- ERGM and other
- link prediction 7
- https://statnet.org/

Economic complexity??

7. Lecture on transport geography.

For spatial interactions:
- Bettencourt 2021 8.1.3 for Maximum entropym radiation and a variant of urban scaling
- https://www.nature.com/articles/nature10856


For network analysis:
-  Barthelemy 2018 Ch. 7. It has examples for road and subway studies + some policy elements. No code.

8. Networks small scale / Spatial networks

   -  https://cran.r-project.org/web/packages/sfnetworks/
   -  Boeing
   -  https://osf.io/78yub/
   -  Lovelace's book, Geocomputation with R https://geocompr.robinlovelace.net/

use sfnetworks as it contains igraph. Use the vignettes.
https://cran.r-project.org/web/packages/sfnetworks/index.html

9. Practical on spatial interaction modelling 
@kolaczyk2020statistical Ch 9

10. Urban policies and causality

---

*ASSESSMENT** 

---

Human dynamics and space-time Bettencourt 2.3

Diversity: Shannon entropy Luis M. A. Bettencourt 5.1 and Appendix C

---

- Batty, M. The New Science of Cities MIT press 2013 

- Barthelemy, M. Morphogenesis of spatial networks 2018 Springer 

- Bettencourt, L. M. Introduction to Urban Science: Evidence and Theory of Cities as Complex Systems **GOOD**

- 