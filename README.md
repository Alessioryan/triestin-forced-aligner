# README

This is an aligner for Triestin data. 
Since Triestin's inventory is a subset of Italian's, we are simply using an Italian aligner and manually correcting the outputs after.

After initializing/activating conda AND downloading the italian model, run the following command
`mfa align --clean --overwrite [IN_DIR] models/vowel_experiment_dict.txt models/italian_cv.zip [OUT_DIR]`