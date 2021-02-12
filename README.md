# [Intention Timer](https://codo-baggins.github.io/intention-timer/)

### Developers ::

-   [Bruce Gordon](https://github.com/bruce-gordon)
-   [Joe Lopez](https://github.com/Codo-Baggins)
-   [Demaceo Howard](https://github.com/demaceo)
    ### Project Links ::
-   [Repo](https://github.com/Codo-Baggins/intention-timer)
-   [Deployed Page](https://codo-baggins.github.io/intention-timer/)
    ## Set-up ::
-   Create repository and clone to personal computer
-   Open in text editor
-   Read the README.md
-   In terminal, run command "open index.html" to interact with app.
    ## Overview & Learning Goals ::
    For our Mod 1 group project, Intention Timer, the goal of the assignment is to create an application with operational functionality according to the rubric and provided composition.
    Our learning goals are to better understand local storage as well as the Git collaborative workflow. Additionally, we would like to utilize this time to obtain better practice at writing code that is not only dynamic and efficient but also user- and developer-friendly.

## Progression ::

9/8: Completed DTR, made GitHub repository, and familiarized ourselves with the given rubric. We then began constructing and designing our application as outlined in Iteration 0 within the rubric. Once that was completed, we moved onto Iteration 1 by creating an Activity class with a set of properties and methods to be utilized in future iterations of the project. We then made some progress on Iteration 2. The first goal of Iteration 2 is to provide specific functionality for when the “Study”, “Meditate” and “Exercise” activities are clicked.
9/9: Tightened up some of our styling to make the app match the composition more closely. We began giving functionality to the application so that it captures information from the user input fields to then eventually display it on the Current Activity page.  
9/10: Today we finished up Iteration 2 by creating fail-safes to prevent users from logging information that is not relevant to the app.  We designed it so that error messages will appear if a user attempts to advance onto the Current Activity page while a field is incorrectly entered. The error messages disappear only once acceptable information has been entered into those input fields. In addition, we cleaned up some of our CSS stylings.  
9/11: Built a functioning countdown timer that applies the minutes and seconds inputs entered by the user from the New Activity page. Once this was completed we began refactoring our work from Iteration 3.
9/12: Began working on Iteration 4.  Layed out a plan of attack and started creating features to allow activities to be logged after the timer reached "00:00".  Started building the framework styling for the individual logged activities.  
9/13: On this day, we rested.
9/14: Finished up Iteration 4. Established ability to log multiple events and have those events be displayed in the Past Activities section. Made the webpage more aesthetically pleasing.
9/15: Started and finished Iteration 5. Created functionality within our Acticity class that utilizes local storage to save logged activities. Ensured that those logged activities would persist on page reload. More refactoring to cut down on “WET” and confusing code.  
9/16: Refactor, refactor, refactor.  Removed unused and commented out code.  

## Showcase ::

<p align="left">New Activity page</br>
 <img width="1000" height="500" src="./showcase/new-activity.jpg">
</p>

<p align="left">New Activity page: displaying "Warning Message" underneath invalid "Seconds" input</br>
 <img width="1000" height="500" src="./showcase/new-activity-warning.jpg">
</p>
<p align="left">Current Activity page: displaying user input with color coordinated Start button</br>
 <img width="1000" height="500" src="./showcase/current-activity.jpg">
</p>
<p align="left">Current Activity page: displaying active start timer of minutes and seconds</br>
 <img width="1000" height="500" src="./showcase/current-activity-start-click.jpg">
</p>
<p align="left">Current Activity page: displaying once the user input time has reached 00:00</br>
 <img width="1000" height="500" src="./showcase/current-activity-complete.jpg">
</p>
<p align="left">Completed Activity page: displaying updated Past Activities section with recent logged activity, as well as a Create A New Activity button</br>
 <img width="1000" height="500" src="./showcase/completed-activty-logged.jpg">
</p>
<p align="left">New Current Activity page: (displayed after clicking "Create A New Activity" button) with new user activity input fields</br>
 <img width="1000" height="500" src="./showcase/new-activity-exercise.jpg">
</p>
<p align="left">Current Activity page: displaying completed activity</br>
 <img width="1000" height="500" src="./showcase/current-activity-exercise-log.jpg">
</p>
<p align="left">Completed Activity page: displaying updated Past Activities section</br>
 <img width="1000" height="500" src="./showcase/complete-activity-exercise.jpg">
</p>

<p align="left">New Current Activity page: displaying new user activity input fields</br>
 <img width="1000" height="500" src="./showcase/new-activity-study.jpg">
</p>
<p align="left">Current Activity page: displaying completed activity</br>
 <img width="1000" height="500" src="./showcase/current-activity-study.jpg">
</p>
<p align="left">Completed Activity page: displaying updated Past Activities section</br>
 <img width="1000" height="500" src="./showcase/completed-activity-study-logged.jpg">
</p>

Project spec & rubric can be found [here](https://frontend.turing.io/projects/module-1/intention-timer-group.html).
