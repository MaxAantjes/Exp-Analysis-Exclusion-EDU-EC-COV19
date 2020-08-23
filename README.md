README
================
Max Aantjes
23/08/2020

  - [Introduction](#introduction)
  - [Data Source](#data-source)
  - [Results](#results)
  - [Conclusion](#conclusion)
  - [References](#references)

## Introduction

This repository provides a brief analysis of the potential inequalities
generated in the Ecuadorian education system as a result of the outbreak
of Covid-19. In particular, it focuses on the government’s attempts to
digitalise education, which threatens to marginalise a substantial
proportion of learners due to their lack of digital resources. The
purpose of the analysis is *exploratory* in nature and intends to
highlight potential risks, rather than prove those risks or their
realisation beyond doubt. Apart from this file, the repository contains
two informative files:

  - **Brief Paper**: A short paper which provides (i) the context of the
    analysis; (ii) the detailed presentation of the results and
    conclusion of the analysis; and (iii) the sources used. This file is
    available
    [here](https://github.com/MaxAantjes/Exp-Analysis-Exclusion-EDU-EC-COV19/blob/master/brief-paper.md).
  - **Appendix**: A code and text file which (i) contains all code to
    generate the results; (ii) gives justifications for the performed
    computations where relevant; (iii) lists the variables used and
    their interpretations in code book tables. This file is available
    [here](https://github.com/MaxAantjes/Exp-Analysis-Exclusion-EDU-EC-COV19/blob/master/appendix.md).

The subsequent sections provide a short summary of the data set used and
the results. For more detailed information, the reader is referred to
the files above, as well as the references made within those files.

## Data Source

The analsyis is based on the results of the Ecuadorian National
Multi-Purpose Household Survey of December 2019 (Encuesta Nacional
Multipropósito de Hogares - Diciembre 2019). The survey collected data
for a variety of socio-economic indicators and was conducted by the
Ecuadorian national census and statistics institute, INEC. At the time
of writing, the form and raw data are available in this [online
repository](https://www.ecuadorencifras.gob.ec/encuesta-nacional-multiproposito-de-hogares/).
According to INEC, the data is representative at national,
national-rural and national-urban level. A total of 11,528 households
were surveyed, with the sampling design taking the form of randomised
cluster sampling. Supplementary information on the data collection
process and the definition of some variables has been made available by
INEC (Andrade et al., 2020). All other interpretations of variables are
directly taken from the form used during the survey process (INEC,
2019).

## Results

The analysis highlighted the three of the exacerbation of inequalities
due to three exclusionary factors:

1)  the access learners have to electronic devices;  
2)  the access learners have to internet;  
3)  the digital literacy levels of members of households with learners.

Learners are defined here as individuals who are of school-going age,
i.e. 5-18 years old.

### Factor 1: Availability of Smart Devices

The first factor of exclusion pertains to the potential unavailability
of what I call ‘smart devices’, i.e. smartphones, laptops, tablets or
desktops. Digital resources and online classes (even in downloaded form)
are not accessible to learners without smart devices. Ideally, one
device should be available for each household member, since this enables
all member to simultaneously work or learn from home. Figure 1 graphs
the distribution of the number of smart devices which are available per
household member in 3,595 urban and 2,254 rural households. In the
average (median) rural household, this value equals 0.33, meaning only
one out of three members can use a device at the same time. The results
in urban areas are slightly better. There, the median value equals 0.71,
meaning three out of four members can use a smart device simultaneously.

![Availability of Smart Devices per Ecuadorian Household Member 2019
INEC data analysed by Max Aantjes](Figure_1.png)

The variation in the data further demonstrates the inequality in the
availability of smart devices within urban and rural areas. In urban
areas, the bottom 25% have a value of less than 0.5, meaning less than
one device is available per two household members. In rural areas, the
bottom 25% have a value of 0, meaning these households do not own any
smart devices. Digital education is thus likely to be inaccessible to a
substantial proportion of learners, or at least, not accessible on
demand for those learners. It is worth noting that these results are not
influenced by household members who do not need such devices, i.e. zero
to four year-olds, as they were not counted. Nor were the results
influenced by households without learners, since only households with
children and young people of school-going age (5-18 year-olds) were
considered.

### Factor 2: Access to Internet

The second factor of exclusion stems from a potential lack of access to
the internet in households. Figure 2 summarises the proportion of the
school-age population which has access to internet at home for each
cultural and ethnic group. The results indicate substantial variability
between the access to internet between ethnic and cultural groups. Only
19% of Montuvio learners and 21% of Indigenous learners, had access to
internet from their homes. In contrast, 51% of learners in the
predominant Mestizo group had access. Care must be taken with the
interpretation of these results as there is substantial variation
between the sample sizes of the different ethnic and cultural groups.
Regardless of these limitations, these results demonstrate the need for
further research into the potential disproportional effect of the school
closures on different ethnic and cultural groups.

![Digital Actions Performed by Ecuadorian Computer Users 2019 INEC data
analysed by Max Aantjes](Figure_2.png)

### Factor 3: Digital Literacy

A holistic approach to digital illiteracy can be found in the Digital
Literacy Global Framework developed by UNESCO and partners. Amongst
other competencies, this framework stresses the importance of literacy
in terms of particular functions, including: basic hardware and software
operations; information and data literacy; communication and
collaboration; and digital content creation. Survey data on the actions
which fit within these broad categories also indicate divisions between
different sub-populations in Ecuador. Figure 3 shows the proportion of
Ecuadorian computer users who performed different software and hardware
operations in the past 12 months. Only computer users who were 15 years
and older and who belonged to household with learners of school-going
age were considered.

![Home Internet Connection of Ecuadorian School-Age Population per
Self-identified Ethnicity 2019 INEC data analysed by Max
Aantjes](Figure_3.png)

The figure indicates there is a convergence between the level of
literacy of urban and rural areas in terms of minimal digital content
creation, which typically requires copying and moving documents as well
as copying and pasting information. However, a potential divergence in
more advanced digital content creation is reflected in the lower
proportion of respondents in rural areas who created a digital
presentation. Furthermore, there is a more pronounced divergence in
terms of basic hardware and software operations, as the proportion of
respondents in rural areas who installed either software or hardware is
over 10 absolute percentage points lower than the corresponding
proportion in urban areas. Structural inequality in terms of the ability
to utilise digital resources thus even persists in situations where
digital resources are accessible.

## Conclusion

This exploratory analysis has suggested that structural exclusion of
learners may occur through at least three complimentary factors,
i.e. the unavailability of smart devices, the lack of internet access
and the prevalence of digital illiteracy. This structural exclusion
threatens to exacerbate the socio-economic inequalities that exist
between ethnic and cultural groups, as well as between rural and urban
populations. Any attempts to identify groups at risk should thus take
these factors into account, annd so should policies aimed at bridging
this gap. The response to the continuing education crisis in Ecuador and
in other countries should, as is almost always the case, take a holistic
rather than an all-or-nothing approach.

# References

Andrade D., Bucheli V., Nabernegg M., & Garcés Christian, (2020).
*Documento Metodológico de Diseño Muestral de la Encuesta
Multipropósito*. INEC. Available from:
<https://www.ecuadorencifras.gob.ec/documentos/web-inec/Multiproposito/2019/201912_Metodologia%20Disenio%20Muestral_Multiproposito.pdf>
\[accessed 23 August 2020\].

INEC, (2019). *Encuesta Nacional Multipróposito de
Hogares-Diciembre-2019*. Available from:
<https://www.ecuadorencifras.gob.ec/documentos/web-inec/Multiproposito/2019/201912_Formulario_Multiproposito.pdf>
\[accessed 23 August 2020\].
