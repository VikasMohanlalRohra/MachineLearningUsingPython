## EDA On Movies Dataset

![image.png](images/MoviesDataSet.png)

- The dataset consists of the information about various movies from the year 2006 to 2016. Various variables present in the dataset includes data of Title, Genre, Director, Rating etc. 
- The dataset comprises of __1000 observations of 12 columns__. Below is a table showing names of all the columns and their description.

| Column Name        | Description                                               |
| ------------------ |:-------------:| 
| Rank               | Movie rank                                                | 
| Title              | The title of the movie                                    |  
| Genre              | A comma-separated list of genres used to classify the film| 
| Description        | Movie summary                                             |   
| Director           | The name of the film's director                           |
| Actors             | A comma-separated list of the main stars in the movie.    |
| Year               | The year that the film released.                          |
| Runtime (Minutes)  | The duration of the film in minutes.                      |
| Rating             | User rating for the movie 0-10                            |
| Votes              | Number of votes                                           |
| Revenue (Millions) | Movie revenue in millions                                 |
| Metascore          | An aggregated average of critic scores. Values are between 0 and 100. Higher scores       represent positive reviews.                                                      |

## Steps followed during EDA
- Import necessary packages
- Load the dataset
- Perform Pre Profiling on data i.e. finding the missing values or zero value or incorrect values in the dataset
- Perform Pre Processing on data i.e. Replacing the incorrect values with the mean,median or mode. If some column contains the large number of null/missing values then we need to drop that column
- Perform Post Profiling on data in order to see how data looks after Pre Processing
- Start with the Analysis by drawing different graphs, charts, etc
- Make some inference out of the graph, charts, etc drawn
- Finally conclude the EDA such that inference is benefical for the business

## Below are the questions addressed in Analysis
- How many movies are produced year by year?
- How critics ratings vary year by year?
- Who are the top 10 actors by the numbers of movies done by them?
- What are the top 10 runtimes of movies ?
- Top Directors w.r.t Revenue
- Why top director earned more ?
- Top Directors w.r.t Rating
- Why top director got high Rating ?
- Max. movies got which Rating ?
- Distribution of Ratings
- Genre Trend in Part1 of Rating
- Genre Trend in Part2 of Rating
- Genre Trend in Part3 of Rating
- Analysing Metascore and Rating
- Analysing Rating and Votes
- Analysing Votes and Revenue

### For more details please click on the below link:
- [Link for the Jupyter Notebook](./Movies_EDA_Project.ipynb)
- [Link for the PowerPoint Presentation](./Movies_EDA_Project.pptx)
- [Link for the Movies Dataset](./Movies_Data_Set.xlsx)
