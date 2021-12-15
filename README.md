# Python coursework

This is the README file for my coursework for the data science and machine 
learning SWBio DTP taught week

# Data

I will analyse the breast cancer dataset from the scikit learn sample datasets
found here: 
https://scikit-learn.org/stable/modules/generated/sklearn.datasets.load_breast_cancer.html#sklearn.datasets.load_breast_cancer

This dataset contains 30 characteristics of breast cancer cell nuclei present in 
a digitised image from a fine needle aspirate (FNA) of a breast mass 

The creators of this dataset are:
1. Dr. William H. Wolberg, General Surgery Dept.
University of Wisconsin, Clinical Sciences Center
Madison, WI 53792
wolberg '@' eagle.surgery.wisc.edu

2. W. Nick Street, Computer Sciences Dept.
University of Wisconsin, 1210 West Dayton St., Madison, WI 53706
street '@' cs.wisc.edu 608-262-6619

3. Olvi L. Mangasarian, Computer Sciences Dept.
University of Wisconsin, 1210 West Dayton St., Madison, WI 53706
olvi '@' cs.wisc.edu

# Code 

The code within this GitHub repository will guide you through the necessary steps to 
load the data, gain a quick overview, then determine which are the most appropriate 
attributes to use as a prediction of if a cancer is benign or malignant.

We will focus on three pairs of attributes that appear to give a good categorisation 
of benign and malignant cancers, then work through the code to determine which two
are the best to use.

Some of the attributes are measured in quite different scales, so feature scaling
is applied to ensure accurate clustering of categories using the nearest neighbour
method

The code is annotated and should be easy enough to follow.
