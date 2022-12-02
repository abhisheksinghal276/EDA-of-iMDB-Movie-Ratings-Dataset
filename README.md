# EDA-of-iMDB-Movie-Ratings-Dataset
This dataset consists of the top iMDB rated movies along with their details. The details are shown by using attributes as below:

1. Name of the Movie
2. Original Language
3. Overview
4. Vote Count
5. Vote Average

## Step 1 - Importing the required libraries:
![image](https://user-images.githubusercontent.com/67495591/205359405-ad60b15b-3b39-4830-bb81-bbff5498470f.png)

## Step 2 - Loading the dataset and reviewing the dataset:
![image](https://user-images.githubusercontent.com/67495591/205360128-d4a95ef0-f443-48cb-b190-ea20ab79823d.png)


## Step 3 - Exploratory Data Analysis:
### Checking the data for Null Values:
![image](https://user-images.githubusercontent.com/67495591/205360320-a92becdf-6c9a-4b5c-87e6-680bd310e3d9.png)

Assumption: As we can see in the above heatmap, there are very less Null Values thus we can assume that the dataset does not contain any Null Values and can proceed with the further steps.
### Finding correlation between different numerical attributes of the dataset:
![image](https://user-images.githubusercontent.com/67495591/205360587-9a63745d-c4df-490c-bda7-144f086a9ca8.png)

### Finding the highest rating given to a movie and displaying the list of movies with the highest rating:
![image](https://user-images.githubusercontent.com/67495591/205361184-97337b29-3dd8-4f31-a56d-4338319dfec2.png)

### Finding the lowest rating given to a movie and displaying the list of movies with the lowest rating:
![image](https://user-images.githubusercontent.com/67495591/205361402-06f991f8-8a38-47fa-9b63-9501ddb29bd7.png)

### Displaying the no. of movies with different ratings using bar graph:
![image](https://user-images.githubusercontent.com/67495591/205361646-224ea04f-002e-4538-9e3a-be05f58b941e.png)

### Displaying the number of movies in the different languages:
![image](https://user-images.githubusercontent.com/67495591/205362396-ba4217d2-c3d6-49f4-82b8-b70be24a2f3c.png)

## Step 4 - Observtions:
1. As seen from the above graph, the maximum number of movies are having 6.4 as the their average rating. So, we can say that the majority of the movies in the dataset are having above average rating.
2. From the graph, we can see that there are very less films having rating in the range 8-10. Thus, there are few movies been made which are considered to be the high quality OR great movies as per audience.
3. As it is visible from the pie chart above, the maximum number of movies were made in English language due to the prominence of the language around the globe. French takes the second place as the most popular language in movies.

## Sources:
1. Kaggle
2. Youtube : Krish Naik
