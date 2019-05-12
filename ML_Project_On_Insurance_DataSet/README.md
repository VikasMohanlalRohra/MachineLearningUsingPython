## Machine Learning Project on Insurance Dataset

![image.png](images/Insurance2.png)

__Insurance DataSet__ comprises of 59381 rows X 127 columns.
- Below is the table showing description of all columns and their description

| Column Name		   |  Description                                                       |
| -----------------    |  ------------                                                      |
|Id			           |  A unique identifier associated with an application.               |
|Product_Info_1-7	   |  A set of normalized variables relating to the product applied for |
|Ins_Age			   |  Normalized age of applicant                                       |
|Ht			           |  Normalized height of applicant                                    |
|Wt			           |  Normalized weight of applicant                                    |
|BMI			       |  Normalized BMI of applicant                                       |
|Employment_Info_1-6   |  A set of normalized variables relating to the employment history of the applicant.|
|InsuredInfo_1-6	   |  A set of normalized variables providing information about the applicant.|
|Insurance_History_1-9 |  A set of normalized variables relating to the insurance history of the applicant.|
|Family_Hist_1-5	   |  A set of normalized variables relating to the family history of the applicant.|
|Medical_History_1-41  |  A set of normalized variables relating to the medical history of the applicant.|
|Medical_Keyword_1-48  |  A set of dummy variables relating to the presence of/absence of a medical keyword being associated with the application.
|Response		       |  This is the target variable, an ordinal variable relating to the final decision associated with an application

## Steps followed during ML Project
- Import necessary packages
- Load the dataset
- Perform Pre Profiling on data i.e. finding the missing values or zero value or incorrect values in the dataset
- Perform Pre Processing on data i.e. Replacing the incorrect values with the mean,median or mode. If some column contains the large number of null/missing values then we need to drop that column
- Perform Post Profiling on data in order to see how data looks after Pre Processing
- Removing Highly Correlated Columns
- Separating Features (X) and Response (y)
- Converting AlphaNumeric data to Numerical data using __LABEL ENCODER__
- Splitting Features (X) and Response (y) into Training and Test Dataset
- Applying Model : a) Decision Tree
                   b) Random Forest
- Conclusion

### For more details please click on the below link:
- [Link for the Jupyter Notebook](./Insurance_ML_Project.ipynb)
- [Link for the PowerPoint Presentation of ML Project](./Insurance_ML_Project_PPT.pptx)
- [Link for the Recording of PowerPoint Presentation](./Insurance_ML_Project_Recording.mp4)
- [Link for the Insurance Dataset](./Insurance_DataSet.txt)

