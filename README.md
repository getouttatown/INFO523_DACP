# INFO 523 - DAPC Project

## Contributors:  
Riley Mawson (U of A)  
Ben Morgan (U of A)

## Summary

Discriminate Analysis of Principal Components (DACP) is a multivariate method of data classification. It takes the dimension reduction of PCA and combines it with the linear combination of features capabilities of Discriminant Analysis (DA) to create a new method of data clustering. This process can handle large datasets while improving performance over other large feature classification methods. Its benefits lie primarily in the study of genetic variations and classification across genomes and populations but can also apply beyond that.

To put this method to practice we performed DAPC on the “penguins” dataset from “palmerpenguins”. Using all of the numeric columns of the observations as the input, PCA was performed to reduce the feature size to 3. Then, DA was performed on the PCA results, and the two most effective DA functions were retained and used for categorizing the observations. With the combination of these two methods, the data was clearly grouped into the three penguin species, evidenced by the distinct groupings within the resulting graph. While this example was performed on a relatively small dataset, the results are obvious and easily understood. Using it as a starting point, It would be simple to modify the implementation for a larger dataset.



## Notable Files

`DAPC_Info_523_RPM_BJMM.pptx`

Presentation of final project

`DAPC_penguins.R`

Source code for the example used in the presentation

`Graphs.Rmd`

Code used to generate some of the graphs shown in the presentation
