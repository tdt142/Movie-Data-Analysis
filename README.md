# Movie Data Analysis
## Introduction
<ul>
    <li>The notebook implements SQLite3 database for searching movies on platforms and suggest movie</li>
    <li>Analyze Data using graphs (bar race, pie chart, line graph) and data frames</li>
    <li>Visualize the Relationships and Run Linear and Multiple Regressions</li>
    <li>Perform In-sample and Out-sample prediction using ARMA model</li>
</ul>

## Instruction for Using the Notebook
<h5>The Notebook has 4 main parts:</h5>
<ul>
    <li><b>Process Implemention:</b>
        <ul>
            <li>Import the dataset and search for movies</li>
            <li>Show movie details</li>
            <li>To use it:
                <ol>
                    <li>Make sure to have CSV file in the same folder(you can change the path by changing at f variable)</li>
                    <li>Run through all the cells to import modules</li>
                    <li>Input the movie name you want to search (It will show the movie details if exists)</li>
                    <li>If the movie does not exist in datasets, it will suggest some movies that has similar name</li>
                </ol>
            </li>
        </ul>
    </li>
    <li><b>Data Analytics:</b>
        <ul>
            <li>Describe the data and analyze through data frame and draw graphs</li>
            <li>To use it:
                <ol>
                    <li>Make sure to have CSV file in the same folder(you can change the path by changing data variable)</li>
                    <li>Run through all the cells to see the description and view the graphs</li>
                </ol>
            </li>
        </ul>
    </li>
    <li><b>Visualization and Regressions:</b>
        <ul>
            <li>Visualization the relationship between data</li>
            <li>Run the Linear Regression model and show on graphs</li>
            <li>Run the Multiple Regression model to predict data and show on graphs</li>
            <li>To use it:
                <ol>
                    <li>Make sure to have CSV file in the same folder(you can change the path by changing data variable)</li>
                    <li>Run through all the cells to import the packages to run models and view the graphs</li>
                </ol>
            </li>
        </ul>
    </li>
    <li><b>Prediction</b>
        <ul>
            <li>Implement ARMA model using SARIMAX package functionalities</li>
            <li>Perform in-sample prediction to compare the real data with predicted data for the last 25 years</li>
            <li>Perform out-sample prediction to forecast the data for the next 16 years</li>
            <li>To use it:
                <ol>
                    <li>Make sure to have CSV file in the same folder(you can change the path by changing data variable)</li>
                    <li>Run through all the cells to import the packages to run models and view the graphs</li>
                </ol>
            </li>
        </ul>
    </li>
</ul>

## Packages in use
<ul>
    <li>sqlite3: To implement SQLite database, and functions</li>
    <li>csv: To use CSV-related function</li>
    <li>matplotlib.pyplot: For data visualization</li>
    <li>pandas: To use for data manipulation and analysis</li>
    <li>numpy: To work with arrays</li>
    <li>Seaborn: For data visualization</li>
    <li>Linregress(scipy.stats): To run Linear Regression</li>
    <li>statsmodels.formula.api: To use classes and functions for the estimation of, test statistical models</li>
    <li>FuncAnimation(matplotlib.animation): To use function to draw a clear frame</li>
    <li>HTML(IPython.display): To display media to the screen</li>
    <li>SARIMAX(statsmodels.tsa.statespace.sarimax): To use and run ARMA model</li>
</ul>

## Data Source: <a href="https://www.kaggle.com/ruchi798/movies-on-netflix-prime-video-hulu-and-disney">Here</a>

## View on Kaggle: <a href= "https://www.kaggle.com/davidtran142/movie-data-analysis">Here</a>
