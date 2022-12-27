the objective of this project is to use convoulutional neural networks to detect Helico bacter pylori in microscopic gastric slides.


This is the first version of the program. To run the program you first have to make a dataset directory and a base directory. Then you need to add a dataset to the dataset directory. the data must have a special name. For pictures that include the bacteria, the file_name must start with the phrase "positive" and for pictures with no bacteria included, the file_name must start with the phrase "negative".The rest of the file_name can be anything. Finally the last step before running the program is to copy the path of "dataset_direcory" and "base_directory" and insert them in the 5th line of the third cell of code_version_1.ipynb as shown below:
hp.divid_img(dset_dir="C:\\New folder\\hp project\\dataset_dir", base_dir="C:\\New folder\\hp project\\base_dir", pref=i)
Please run the code with a toy_dataset because right now, I'm running into a bug that i can't fix. The bug is shown in the issue section of this repository.
