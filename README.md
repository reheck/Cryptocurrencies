# Cryptocurrencies
## Purpose
### An investment firm is interested in providing their clients with opportunities to invest in cryptocurrencies. Using Unsupervised Machine Learning and principal component reduction technique, PCA, the vast world of cryptocurrency options was clustered into the most likely candidates for sound investing. Preprocessing of the data was performed to prepare for PCA. Preprocessing included ensuring only the tradable cryptocurrencies with working algorithms were kept in the dataframe, and then ensuring all rows with at least one NaN value were removed.
![image](https://user-images.githubusercontent.com/102757676/184557156-6ca8eb0b-a8aa-4cc3-959b-8342d7f1f051.png)

### The dataset was processed further to ensure only the coins that were being mined were retained.
![image](https://user-images.githubusercontent.com/102757676/184557174-b3fc3611-befc-44ea-b479-c8127cd6d866.png)

### Because unsupervised machine learning models only work with numbers, the text values had to be converted to numerical values.
![image](https://user-images.githubusercontent.com/102757676/184557195-c11578e0-5fe0-4327-8987-977b9b6984d6.png)

### Finally, PCA could be used to reduce the data dimensions. There were three principal components chosen for this model.
![image](https://user-images.githubusercontent.com/102757676/184557223-4aa7d5d8-fc12-4d2f-a6ae-e70bf20d932b.png)

## Results
### Looking for the best K-means value meant creating an elbow curve. A k-means of 4 was determined by the curve.
![image](https://user-images.githubusercontent.com/102757676/184557258-4356b08d-c843-4e90-a072-2ce152d756b2.png)

### The clustered data was printed on a 3-d scatter plot
![image](https://user-images.githubusercontent.com/102757676/184557286-d1a03004-e5ca-4741-a7f1-01f2e6157c01.png)

### The x-values were scaled and a scatter plot created to show Total Coins Mined versus Total Coin Supply
![image](https://user-images.githubusercontent.com/102757676/184557327-56e51ca8-5369-4a03-aa31-8758684b5246.png)
