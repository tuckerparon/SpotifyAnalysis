# Spotify Analysis 🎶👨🏽‍💻

## What? 💻
This project contains an analysis on my Spotify streaming data from January 2021 to January 2022. The code is done in Jupyter Notebook and the analysis uses mainly matplotlib to plot data (mostly organized in dictionary data structures) to garner insights about my favorite music and listening trends over time. The project also includes a decent amount of list comprehension - something I have been trying to incorporate into my code as of late, to cut down run time and improve readability.

Inside the repository is a SpotifyAnalysis.ipynb file which includes the full analysis with the code and graphics along with a SpotifyAnalysis.pdf file which just includes the generated visuals and written analysis for a cleaner looking report.

## Why? 🤔
I was simply very curious about how Spotify structured their data - although I'm sure the non-public data has many, many more features which may mean the structure is more advanced or different. I also saw a video by [Ken Jee](https://www.youtube.com/watch?v=B1g_yMKpdwo) which showed him reviewing an up and coming Data Scientists project which also analyzed their own data (however, I think their's was from the Spotify API). Lastly, in all honesty, I saw a Spotify application on LinkedIn and wanted to apply but thought it would be a good idea to do a relevent project first :)

## Other 💬
Due to the personal nature of the Spotify data, I did not include it in the repository. Should you want to do a similar analysis, you will need to first request the data and then place it in an appropriately named folder. To request the data, their is a 'request data' button at the bottom of the privacy settings page in your Spotify Account. You should then recieve an email with directions for recieving the data. At the time of writing the data comes in a file labeled 'MyData'. For the code to work, place the 'MyData' folder into the same working directory as your Python/Jupyter Notebook and rename it to 'data' (instead of 'MyData').

Also some of the code, particularly for the time-series plots, can admittedly be a bit clunky at times. I did consider using functions for filtering through the dictionary data, however I only needed to do so a few times and each time required slightly different ways of doing so, so I settled for several for loops with if statements :(
