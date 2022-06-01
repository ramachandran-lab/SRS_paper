# Section 2: The SRS detects instances from unknown classes

1. Download folders: 
  * SWIFr_train_seeds_rm_w1
  * SWIFr_train_seeds_rm_w2
  * SWIFr_train_seeds_rm_w3
2. Train using SWIF(r)
  * Example command with SWIF(r) installed: swifr_train --path ~/SWIFr_train_seeds_rm_w1
4. Run SWIF(r) on files in classified folder (subfolder within each folder downloaded above)
  * Example command with SWIF(r) installed: swifr_test --path2trained ~/SWIFr_train_seeds_rm_w1 --pi 0.5 0.5 --file ~/SWIFr_train_seeds_rm_w1/classified/test_set.txt



