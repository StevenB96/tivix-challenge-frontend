# tivix-challenge-frontend
This project was created to satisfy the requirements of the frontend coding challenge from Tivix.

The application is simple in structure, yet tries to incorperate some of the fundamentals of programming.

#### Requirements:

1. Implement data tracker class that keeps track of min, max, mean, and mode values.
	- insert(value) - Records a new value into the tracker
	- showMin() - Show the minimum value from the recorded tracker values
	- showMax() - Show the maximum value from the recorded tracker values
	- showMean() - Show the mean value from the recorded tracker values
	- showMode() - Show the mode value from the recorded tracker values

2. Call 5-day forecast on the target city and create different data tracker objects from above data tracker class:
	- Show day temperature

#### Usage:
The only setup step is to insert a valid https://openweathermap.org/ API key between the quotation marks on the follwoing line.
`const appid = '';`

#### Discussion:
A more polished application would have been possible by using a framework such as React JS.

It would be good to break out some of the code, particularly the js ands css, into their own files.

However, this application is only meant as a demonstration of coding skill and not an attempt to create the perfect app. Therefore, the decision was made to make it as native as possible.