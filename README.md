# YouTube_WebScrapping_Project
This project is for web scrapping for popular movies on youtube. First of all, url link was launched in chrome by virtue of selenium chromedriver.
In this web elements are located by using python selenium (xpath, id, class locators) and fetched its string values into dataframes to create .csv file for storing all required values.
.csv file contains all values of object type and some basic python was used to convert 2 columns into integer values to make them quatitative variables to perform some data visualization tasks.
Some fucntions applied to dataframe to perform tasks like:
1) Fetch top 5 movies with highest views after sorting dataframe in descending order.
   ![1](https://github.com/VeerpalBravo/YouTube_WebScrapping_Project/assets/35980959/69430f30-47b3-4a89-a1fa-c4d2f3031d14)

2) Create bar chart which represents Total Number of views corresponds to each moview for Top 10 popular movies on youtube.
   ![2](https://github.com/VeerpalBravo/YouTube_WebScrapping_Project/assets/35980959/67057a1a-4d32-46f7-8a4a-69323638addc)

3) Scatter plot to expalain the relation with number of views with uploaded time of video.
  ![3](https://github.com/VeerpalBravo/YouTube_WebScrapping_Project/assets/35980959/6a26a0f9-d3b9-4a63-9b0c-634b0d6a2eb2)

4) bar graph shows top 10 youtube movies uploaded time means how many days before these are uploaded but after sorted data in desceding order of total views to each movie. 
from colorama import Fore, Back, Style.
![4](https://github.com/VeerpalBravo/YouTube_WebScrapping_Project/assets/35980959/e8821ebb-7cc6-48ba-87c7-52020997880c)

5) Pie chart shows total percentage of moviews which are grouped according to their uploaded time in terms of days, months, weeks, years ago.
![5](https://github.com/VeerpalBravo/YouTube_WebScrapping_Project/assets/35980959/9ee0927e-2a33-4e86-a076-54c3f847b8f6)
