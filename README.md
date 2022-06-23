# Personal Expenses App

So this is the third Flutter app I've made. The topic concerns the user's personal expenses. On the main page of the application
there is a graph showing the values of expenses from a week ago and a list of expenses. This page looks like this:

<img src="https://user-images.githubusercontent.com/68535467/175183221-203e87b8-70ac-4b8d-bf17-d7fba01b2925.jpg" width="320" height="720">

The user can add new expenses by pressing the button at the bottom or in the application bar. Then the 'form' is pulled out. 
The user must then enter the title, amount and select a date from the calendar to add this expense. Of course, you cannot select a date 
from the future or send the amount as a string. It looks like this:

<img src="https://user-images.githubusercontent.com/68535467/175183246-3a782657-fdc8-45a6-96d5-b48ddb50e96e.jpg" width="320" height="720">     <img src="https://user-images.githubusercontent.com/68535467/175183226-927a65f1-c444-4d84-942f-46b2cb7324f6.jpg" width="320" height="720">     <img src="https://user-images.githubusercontent.com/68535467/175183224-7260442f-3074-49c5-a5c8-af7f513752b3.jpg" width="320" height="720">

Let's add more expenses. Now, as you can see in the graph, you can see the expenses of the various days of the last week. 
The amount spent on one day is rounded to the full value. The amount of the painted strip depends on the proportion of all expenses of the last week on a particular day. Of course, the list of expenses can be scrolled. The user can also remove an expense from the list. It looks like this:

<img src="https://user-images.githubusercontent.com/68535467/175183234-0d2f5c31-18a6-4091-af9c-28a532883c01.jpg" width="320" height="720">     <img src="https://user-images.githubusercontent.com/68535467/175183230-9f92ab3b-70f9-4e82-b8c6-7461131956fe.jpg" width="320" height="720">

However, when the user turns the phone, the application will adjust and a switch will be shown, which can show the graph or hide it, and thus show the list of expenses:

<img src="https://user-images.githubusercontent.com/68535467/175183242-98153ed6-58ae-4755-a7b4-8de772caceff.jpg" width="720" height="320">     <img src="https://user-images.githubusercontent.com/68535467/175183236-97cad5ef-264c-4fe8-ac87-b34a422b639d.jpg" width="720" height="320">

In addition, the application is responsive, so it should look the same on every device. And that's the app. Now let's move on to the downsides of the app and what I learned while creating it.

Cons of the application:

- expenses are removed when the application is turned off (no server or SharedPreferences)
- no exact validation as it is not a form

What have i learned:
- select and use a calendar with dates
- creating a responsive application and adjusting it depending on whether the phone is turned or not

and a lot of different less important things ...

Next applications (already cooler) will be posted in the coming days.
