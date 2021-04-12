# Python auto analysis application

## Principle Component Analysis

##### Principle Component Analysis is a technique used to reduce the number of dimensions of your data. In the process you lose some accuracy but increase the simplicity of your data which can make it easier to use.

## Steps

1. Scale your numerical variables
2. Center all of your points around the origin
3. Find the line of best fit that goes through the origin but also maximizes the distance from your points projected points on the line, and the origin.
4. This is your first Principle Component and the slope of this line will tell you how important each variable is
    - Create a vector along this line of length 1, this is the Eigenvector
    - The sum of squares of the Eigenvector is the Eigenvalue
    - The amounts each variable contribute to the slope of the Eigenvalue are the Loading Scores
5. Repeat this process creating as many Principle Components as there are variables which each Principle Component being perpendicular to the existing ones

##Output

1. Upload file for analysis 
![alt text](https://github.com/KishanTeli/pca_python_application/blob/main/Screenshots/first_view.png "Upload File")

2. Analysis graph generated after file uploaded
![alt text](https://github.com/KishanTeli/pca_python_application/blob/main/Screenshots/graph_view.png "graph view")


##Settings

1. You can change variable parameters by changing
![alt text](https://github.com/KishanTeli/pca_python_application/blob/main/Screenshots/variable.png "variable")

2. You can change PCA variable for different graph
![alt text](https://github.com/KishanTeli/pca_python_application/blob/main/Screenshots/pca.png "PCA")

