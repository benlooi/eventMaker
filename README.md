# eventMaker
A community portal for users to create and manage events.

# Purpose
For learning how to build web apps with frameworks such as Angular JS and Semantic UI for front-end, and CodeIgniter for PHP backend.


# Database Design
You can use MySQL to connect to CodeIgniter and write APIS that you can call from Angular.  Here is the suggested Database structure:

## Tables
### Users
- user_id (Primary, A.I index)
- username (varchar 50)
- password (varchar 50)
- first_name (varchar 50)
- last_name (varchar 50)
- email (varchar 100)
- avatar (varchar 50)

### Events 
- event_id (Primary, A.I index)
- event_name (varchar 100)
- event_description (varchar 100)
- date (varchar 100)
- time (varchar 100)
- location (varchar 50)
- no_participants (varchar 50)
- image (varchar 50)
- creator (varchar 50)
-likes (varchar 1000)
- join (varchar 1000)

### Feedback
- feedback_id (Primary, A.I index)
- event_id
- user_id
- comments (varchar 2000)
- timestamp 

This is the basic template baseline. Feel free to add more tables and fields to suit your needs

References:
CodeIgniter User guide - http://www.codeigniter.com/user_guide/
Semantic UI - http://semantic-ui.com/
AngularJS 
- http://www.w3schools.com/angular/angular_intro.asp
- https://angularjs.org/

# Flow
1) Visitor will land on a log-in page
2) Once logged in, he/she will see a wall of events created. Past events and future events. User can choose to like or join event. Or click to find out more.
3) User can also create an event via a side menu, and fill up an online form.
4) After the event, user can leave feedback for the event.




