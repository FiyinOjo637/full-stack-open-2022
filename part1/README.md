							THESE ARE THE FILES FOR THE EXERSISES IN part1
   1.1: course information, step1
The application that we will start working on in this exercise will be further developed in a few of the following exercises.
In this and other upcoming exercise sets in this course, it is enough to only submit the final state of the application.
If desired, you may also create a commit for each exercise of the series, but this is entirely optional.

1.2: course information, step2
Refactor the Content component so that it does not render any names of parts or their number of exercises by itself.
Instead it only renders three Part components of which each renders the name and number of exercises of one part.

1.3: course information step3
Let's move forward to using objects in our application.
Modify the variable definitions of the App component as follows and also refactor the application so that it still works

1.4: course information step4
And then place the objects into an array. Modify the variable definitions of App into the following form and modify the other parts of the application accordingly:

1.5: course information step5
Let's take the changes one step further. Change the course and its parts into a single JavaScript object. Fix everything that breaks.

	  UNICAFE
1.6: unicafe step1
Like most companies, Unicafe collects feedback from its customers. Your task is to implement a web application for collecting customer feedback. There are only three options for feedback: good, neutral, and bad.
The application must display the total number of collected feedback for each category. 

1.7: unicafe step2
Expand your application so that it shows more statistics about the gathered feedback: the total number of collected feedback,
the average score (good: 1, neutral: 0, bad: -1) and the percentage of positive feedback.

1.8: unicafe step3
Refactor your application so that displaying the statistics is extracted into its own Statistics component. The state of the application should remain in the App root component.

1.9: unicafe step4
Change your application to display statistics only once feedback has been gathered.

1.10: unicafe step5
Let's continue refactoring the application. Extract the following two components:
Button for defining the buttons used for submitting feedback
StatisticLine for displaying a single statistic, e.g. the average score.
To be clear: the StatisticLine component always displays a single statistic, meaning that the application uses multiple components for rendering all of the statistics:
	
1.11*: unicafe step6
Display the statistics in an HTML table


	 ANECDOTES
1.12*: anecdotes step1
The world of software engineering is filled with anecdotes that distill timeless truths from our field into short one-liners.
Expand the following application by adding a button that can be clicked to display a random anecdote from the field of software engineering:

1.13*: anecdotes step2
Expand your application so that you can vote for the displayed anecdote.
fullstack content
NB store the votes of each anecdote into an array or object in the component's state. Remember that the correct way of updating state stored in complex data structures like objects and arrays is to make a copy of the state.

1.14*: anecdotes step3
Now implement the final version of the application that displays the anecdote with the largest number of votes:
fullstack content
If multiple anecdotes are tied for first place it is sufficient to just show one of them.
