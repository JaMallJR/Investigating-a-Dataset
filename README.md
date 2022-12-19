# Investigating-a-Dataset
You should start by taking a look at your dataset and brainstorming what questions you could answer using it. Then you should use pandas and NumPy to answer the questions you are most interested in, and create a report sharing the answers.

#After completing the project, I had:

Known all the steps involved in a typical data analysis process
Been comfortable posing questions that can be answered with a given dataset and then answering those questions
Known how to investigate problems in a dataset and wrangle the data into a format you can use
An experience communicating the results of your analysis
Been able to use vectorized operations in NumPy and pandas to speed up your data analysis code
Beeen familiar with pandas' Series and DataFrame objects, which let you access your data more conveniently
Known how to use Matplotlib to produce plots showing your findings

## Introduction

### Dataset Description 

<br>This data set contains information about 4,803 movies collected from The Movie Database (TMDb), including user ratings, revenue,etc.. with 20+ features
<br>And its columns categorized into:</br>
><li>budget: Money spent to product the Movie</li>
><li>genres: Type of the Movie like: romantic,dramaa..</li>
><li>homepage: Official link of the Movie</li>
><li>id: id of the Movie in the database</li>
><li>keywords: Keywords used to help in the search for the Movie</li>
><li>original_language: Original Language used in the Movie's audio </li>
><li>original_title: Original Movie name</li>
><li>overview: Description of the Movie</li>
><li>popularity: how popular the movie is among the audience</li>
><li>production_companies: Company product the Movie</li>
><li>production_countries: Country at which the Movie is producted</li>
><li>release_date:Date where the Movie released</li>
><li>revenue: Revenue money from Box Office</li>
><li>runtime: Duration of the Movie</li>
><li>spoken_languages: Languages spoken in the Movie</li>
><li>status: Movie Status if Released,Rumored,Post Production</li>
><li>tagline</li>
><li>title</li>
><li>vote_average:Average of votes for the movie</li>
><li>vote_count: number of people voted</li>
</br>

### Question(s) for Analysis
#### 1)Classify the most used genre at current year
#### 2)Analysing the Runtime for every movie
#### 3)Relation between budget and revenue of the movie

## Data Wrangling

> We will load in the data, check for cleanliness, and then trim and clean your dataset for analysis.

### Data Cleaning

<br>1) We will drop the undesirable values like 'homepage','id','keywords','overview','production_countries','tagline'.</br>
<br>2) We will drop the values which have zeroes value like budget,revenue,runtime..</br>
<br>3) Dealing with release_date as datetime value not int, So we will change it</br>
<br>4) Extracting the wanted values from list of dictionaries we faced</br>

## Exploratory Data Analysis
> Performing our learned skills with __Pandas__ and __NumPy__ on our dataset and **Visualizing** our results __Matplot__ and __Seaborn__

## Conclusions

### We reach the final of the project,let's conclude some of what we saw:
> We had seen that "Drama" was leading in that specific year (from Q1)

> The avg duration of the movie ranged from 90 - 99 min that's why the audience don't get bored (from Q2)

>The budget increases, so the revenue increases 

### Limitaion
> We face that genres column issue which we had to extract them from that list of dictionries, Whatever there can't be a movie which can take all that value of genres. As the budget and revenue weren't specified with certain currency but it doesn't matter we didn't use them in our analysis
