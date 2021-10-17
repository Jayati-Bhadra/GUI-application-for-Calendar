# GUI-application-for-Calendar
In Python, we can make GUIs using Tkinter. If you are very imaginative and creative you can do amazing stuff with Tkinter. Here, we will make a Python Calendar GUI application using Tkinter. In this app, the user has to enter the year for which he wants to view the calendar, and then the calendar will appear.

Install Tkinter first using this command: pip install tk

We would also need a Calendar package, but we don’t have to install it. It is a default package that automatically comes with python.

ShowCalender function is displaying the calendar. You enter a year in the search box and when enter is pressed, how the calendar should be displayed is managed here. You set the background color which is grey here and can be changed in code as per your need. You also set the dimension of the calendar which is 550×600 here. Then you ask for input year in integer form. Once the user enters the year calendar content is fetched from the calendar module of python by passing the year as an argument.

In the driver code, firstly we are giving background color to the left part of the screen(as shown in the image below).  Since it is a small window to give input year so we set its dimension as 250×140. In the button line below year_field, we call showCalendar function that we made above. This function shows us the full calendar for an input year.

Now, we need to adjust the widgets in the calendar also, for that we define the location in the grid for everything. You can play by changing grid row and column parameters to explore more.
