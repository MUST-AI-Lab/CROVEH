CROVEH dataset

CROVEH dataset has 426 samples that contain both 7,587 persons and 6,361 vehicle annotations.
Each sample has at least 11 persons and 11 vehicles, and at most 98 persons and 38 vehicles.
The average number of persons and vehicles are 17.8 and 14.9.
These samples are selected from nuImages [1] and Cityscapes[2] datasets. We eliminate ego vehicles, bicycles, and motorcycles from vehicle annotations. And we change the annotation of riders to persons.

Content in the directory:
1. "./train_dm.m and ./test_dm.m". the matlab script to generate the ground truth.
2. "./train_data/samples". It contains the original images.
3. "./train_data/anns_human". The folder of human annotations.
4. "./train_data/anns_vehicle" The folder of vehicle annotations.
5. "./test_data/*" Similar to the training set above

The Google Drive link is https://drive.google.com/file/d/1g6phLXIWLrEFwlj_7pNPZPh6KsGbUljD/view?usp=sharing.
