> # Brainhack 2023

# Brain tumor subtyping



## Contributors

- Jędrzej Kubica (jj.kubica@student.uw.edu.pl)
- Barczuk Julia (julia.barczuk@stud.umed.lodz.pl)
- Justyna Wiśniewska (j.wisniewska@nencki.edu.pl)
- Katarzyna Grad (k.grad@student.uw.edu.pl)
- Milena Królikowska (mm.krolikows@uw.edu.pl)
- Paulina Domek (p.domek68@gmail.com)
- Urszula Baranowska (umbaranowska@gmail.com)
- Weronika Plichta (plichta.weronika@gmail.com)


## Introduction

Brain tumors can be classified into different subtypes to recommend a patient-specific treatment. Characterization of patients into groups based on molecular features can help clinicians to choose proper medications for each individual and to improve the outcome of the treatment.

Various classification tools for tumors of the central nervous system have been developed. For instance, MethPed  is an open-access classifier which uses DNA methylation as an epigenetic marker for subtype classification.

The goal of the project is to develop of a data analysis workflow to analyze publicly-available epigenetic data of brain tumor patients from databases, such as The Cancer Genome Atlas.

Future work will include subtype-specific drug recommendations. Further research can also be extended from brain tumors into tumors of the nervous system.


## Methods

Methylation data for 3 pediatric (< 18 y/o) patients with brain tumors was used in the project (Case IDs: TCGA-12-1091, TCGA-HT-7483, TCGA-DB-5278).


MethPed

## Results

Case 1 (ID: TCGA-12-1091)

![plot_case1](https://user-images.githubusercontent.com/82537630/226108606-b0a8f2ed-dee2-4655-9fa8-95d932c27b68.png)

Case 2 (ID: TCGA-HT-7483)

<img width="443" alt="plot_case2" src="https://user-images.githubusercontent.com/82537630/226108613-2b06d866-0ab0-4fbc-a8be-15d77875abf4.png">

Case 3 (ID: TCGA-DB-5278)

![plot_case3](https://user-images.githubusercontent.com/82537630/226108621-1018492f-63bd-4b3f-be87-aa8fa88e874c.png)


## Discussion

We validated an open-source software MethPed as a potentially useful tool for clinical application. However the result might require additional confirmation.


## References

1. Ahamed M, Danielsson A, Nemes S, Carén H (2022). MethPed: A DNA methylation classifier tool for the identification of pediatric brain tumor subtypes. R package version 1.26.0.

2. Davis S, Du P, Bilke S, Triche, Jr. T, Bootwalla M (2022). methylumi: Handle Illumina methylation data. R package version 2.44.0.

The results shown here are in whole or part based upon data generated by the TCGA Research Network: https://www.cancer.gov/tcga.
