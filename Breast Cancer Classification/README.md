# Breast Cancer Classification 
This is a biomedical coding problem for classification
### Task:
> The task is to classify Malignant and Benign Tumor. (Malignant Tumor cells are cancerous, whereas Benign Tumor cells aren't dangerous.)
### Dataset:
> The Dataset was downloaded from https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+%28Original%29 and formated into a CSV file.
> 
> The Dataset consists of 699 individual people (rows). For all subjects the following features were collected from image analysis (columns).
>1. Clump Thickness: 1 - 10 
>2. Uniformity of Cell Size: 1 - 10 
>3. Uniformity of Cell Shape: 1 - 10 
>4. Marginal Adhesion: 1 - 10 
>5. Single Epithelial Cell Size: 1 - 10 
>6. Bare Nuclei: 1 - 10 
>7. Bland Chromatin: 1 - 10 
>8. Normal Nucleoli: 1 - 10 
>9. Mitoses: 1 - 10 
>10. Class: (2 for benign, 4 for malignant) THIS IS THE TARGET
>
> The first column is removed as it holded the instance ID. 
> 
> For the trainings process there were always taken the first 400 subjects, resulting in a testdataset of 298 instances. Training and Test data is strictly 
> through out the whole learning and prediction process. 
### Classifying Tools:
> In this repository the aim is to build a classifying algorithm. For this purpose there was chosen to build a neural network from scratch. 
> It has a flexible architecture, such that it was possible to find an optimal structure.
> 
> For crossvalidation of the performance of the self built neural network, there were also implemented networks with common toolboxes as sklearn or neurolab.
> All implementations can be seen in the different sections of the Jupyter Notebook.
### Conclusion:
> The self built Neural Network may need some few more iterations in order to build the model, however the 
> classification ends up to be as accurate as with the toolbox implementations. The accuracy of all three models averages (with the given ratio of trainings
> and testdata) about 99%. With an increase of the subjects in the training data to 500, it is even possible to get a 100% correct prediction with the self 
> built and sklearn model. 
