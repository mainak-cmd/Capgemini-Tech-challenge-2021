# Capgemini-Tech-challenge-2021
#ecomendation system for cloth

1)study the data useing  Excel and remove unnecessary features.prepare process data

2)Read process data useing pandas.

3)Prepare Brand list with avarage rateing and nuumber of rateing (popularity).

4)Charecter encodeing and includeing it inside process data.

5)Prepareing pivot table againest brand vs use id to create 1 d array or vector for each and every brand. 

6)User input for brand (quary point). 

7)Prepare sparse matrix to apply csr_matrix() funtion on pivot  table.(A sparse matrix is a matrix that is comprised of mostly zero values of the pivot table.

8)Prapare unsuperviced  model as NearestNeighbors(algorithm='brute', metric='cosine') and apply it on the sparse matrix.

9)Fire quary point into superviced  model.

10)Findout cosine distance of other brands and indices with respect to the quary point , Minimum distance have maximum likelyhood for similar brands recomendation

#Recomendation system for electronic.

Part_1:Recomendation of similar products/categories.

Part_2:recomendation of similar brand for particular product/category as well as similar choice of products.

Part_1

1)study the data useing  Excel and remove unnecessary features.prepare process data

2)Read process data useing pandas.


4)Charecter encodeing and includeing it inside process data.

5)Prepareing pivot table againest category vs user Id to create 1 d array or vector for each and every brand. 

6)User input for category (quary point). 

7)Prepare sparse matrix to apply csr_matrix() funtion on pivot  table.(A sparse matrix is a matrix that is comprised of mostly zero values of the pivot table.

8)prapare unsuperviced  model as NearestNeighbors(algorithm='brute', metric='cosine') and apply it on the sparse matrix.

9)Fire quary point into superviced  model.

10)Findout cosine distance of other categories and indices with respect to the quary point,Minimum distance have maximum likelyhood for similar brand recomendation

11)Prepare final result cointains of similar Categories recomendation for particular category (User input/quary point).


Part_2

1)Filter dataset with respect to user input.

2)Prepare Brand list with avarage rateing and nuumber of rateing (popularity).

