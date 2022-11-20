# Project-X
## LIGHTS CAMERA ACTION!
### Introduction
This project is on the type of films that are currently trending at the box office.

![PROJECT X PICTURES](https://user-images.githubusercontent.com/117171052/202789606-6510fc9b-4d31-4037-8eca-239c08cc87dc.png)

### Business Understanding

Creating movies or original video content has taken the world by storm. All big companies are creating original video content and microsoft doesn't want to be left behind. The problem however is that Microsoft lacks experience in creating movies.

### Aim

Videos can create an instant rush of emotions.It cause us to laugh,make us feel nostalgic and has the power to bring us to tears, says one Forbes Magazine. With this in mind Microsoft create a new studio with the aim of generating unique,eye_catching video content that hooks attention immediately. They have contracted my consulting company CMK Analytics to explore what types of films are currently doing the best at the box office and turn the findings into actionable insights that the head of Microsoft's new studio can use to decide what film to create.

### Data Understanding

The data was acquired from various locations. The different files have different formats.The data has the following set of information about the movies: a. Principals - contains the ranks of the people who worked the movies that is whether director or writer. b. Movie_basics - contains basic information about the movies. c. Movie-ratings - contains movie-id ,ratings and number of reviews. d. movies-akas - countains movie details like its title and so on and so forth.

### Data Preparation
Before modelling the data had to undergo a cleaning process. The data was cheked for null values and duplicates. The columns and rows that had null values and duplicates were dropped.Some Exploratory Data Analysis(EDA) was done to the data to determine if there was any patterns in the data. It was dicovered that the data had a few categorical columns that had to be converted to numeric features in order to be used in modelling. This data was then ready for evaluation.

### Evaluation

![download](https://user-images.githubusercontent.com/117171052/202895476-5b35f65c-cbc4-4878-851d-760fa89c8d84.png)

The graph above compares the genres to the domestic gross revenue. It is evident that when genres are combined in one movie the revenue generally is higher as opposed to when the movie consists of only one genre.

![Screenshot 2022-11-20 125326](https://user-images.githubusercontent.com/117171052/202895749-79302352-770d-4fce-847e-3521f487c6d7.png)

There exists a positve correlation between the production budget and the average ratings.This is to mean that the more money allocated to producing the movie results in high ratings and vice versa.

### Conclusion.
1. When comparing the genre and ratings the documentary genre emerged the highest.
2. The movie genre that is most costly to produce seems to be the Drama followed by the Thriller.
3. In terms of domestic revenue the findings are a lot more interesting since the movie tends to be more profitable when it consists of one or more genres.
4. I also realized that the more the money allocated to movie production the more ratings it gets.

### Recommendations.
1. Drama is the best reccomended genre as according to the analysis it has the highest returns of revenue.
2. Documentaries have the highest ratings and hence means that the consumers like this type of genre.
3. Drama are the second best rated and shows also consumers appreciate the product.
4. Thrillers are also recommended for a start as they have a low cost production budget.

### Repository Guide
> The raw data used for the project can be found 
> The cleaned data can be found 
> The images from EDA can be found 
> The notebook that contains the project can be found 
> The presentation for this project can be found






