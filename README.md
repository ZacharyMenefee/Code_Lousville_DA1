# Code_Louisville_DA1

All necessary requirements are contained within my requirements.txt file. For my project all of the data utilized is freshly accessed twitter data provided via the twitter API, that data is then analyzed using Azure's sentiment analysis suite. The original idea was the integrate my own machine learning-sentiment analysis model but that was restricted due to time contstraints. From the project requirements, my project uses has the following features: ( Use an API to pull in data. The most common library for this is “requests”, while pulling the data itself is usually pretty easy, sometimes going through the specific API documentation can be kind of complicated., Use custom functions or lambdas to perform specific operations to clean or manipulate your data, return those values, then use them in other parts of your project., Write custom functions to operate on your data. You may discover that you want to find out something particular about data that just doesn’t have a built-in Pandas function that accomplishes your goal. Maybe you want your function to read in a DataFrame, search the columns for any mention of “Cars”, then return the lowest-priced car in the column along with the mileage. This category is very open to interpretation, so any function operating on your data will work., Make 2 basic plots with matplotlib, seaborn, or any other kind of visualization library that you think looks interesting., If using some format other than a notebook, make sure your README explains your project. )