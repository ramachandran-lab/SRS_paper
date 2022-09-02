# Section 1: Overview and Definition of SRS

* To follow along with the process used to generate Figure 1 data, use the code included in SRS_Guide.ipynb
* To view or recreate SWIF(r) analysis, see the folders within "SWIFr_Models"
  * SWIF(r) can be trained using any of the included subfolders (the "SWIFr models")
    * Example command: swifr train --path ~/SWIFr_train_corr1
  * Testing data and testing output is contained in the "classified" subfolder within each SWIF(r) model folder
    * Example command: swifr_test --path2trained ~/SWIFr_train_corr1 --pi 0.5 0.5 --file ~/SWIFr_train_corr1/classified/vals1_testing.txt
