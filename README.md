# Gender-Classification

In this project we train a model to correctly identify the gender of a person given an image. 

Below is the file structure used for this project.

```bash
├── Main Data Directory
│   ├── images folder
│   ├── train.csv(the training dataset, with image names and labels)
│   ├── test.csv(the test dataset)
│   ├── output.csv(output of test dataset)
│   ├── weights file(.h5 format)
```
I have not added the images folder and weights file, due to file size constraints. The image data can be downloaded from the contest home page and weights can be saved by merely running the model.save_weights() cell in the ipynb notebook.

For further information on the problem statement refer to the link below.

Contest Home page: https://datahack.analyticsvidhya.com/contest/gender-classification/

I have an output accuracy of 89.76% on unseen data used for the contest
