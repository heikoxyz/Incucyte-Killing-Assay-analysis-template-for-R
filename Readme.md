This template was generated to streamline the analysis of various Incucyte readouts (NLR count, cytotox green, confluence or similar).
It finds its use case in all experiments where different cell lines are requiring comparisons (i.e. KO cell lines).
In those cases control cells are used to make sure the samples have controls which are seeded at the same density and similar growth.
Therefore multiple cell concentrations of the control cells are seeded around the range of the sample seeding.
For KO cells those control cells would be Scr-gRNA treated controls.

This analysis protocol then compares all samples to their corresponding growth control automatically by calculating the Area under the curve (AUC)
for each cell line and condition and plotting the samples with their controls according to the smalles AUC delta.

Various variables can be tweaked and multiple conditions can be tested while having the code automatically respond to the data available.

This template requires the R analysis.xlsx file for input of the data and correct formating of the graphs.
The Excel file holds further instruction on how to use this template.

This is my first project in its current state the template is still far from ideal or being polished but it should provide a quick analysis to get the required answers.
In case it will find appropriate demand, further improvments and changes will be made.

Further improvments that would be nice to have:
Having the cell lines included in the table of contents to quickly find the one of interest.
Having the report structured by cell line instead of Scr controls.
