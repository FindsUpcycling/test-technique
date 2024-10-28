# test-technique# Technical Assignment - Full stack

Your assignment is to develop a simple single-page application that presents a weekly calendar.

The application should simply be two views along with a dialog :

- The register user view 
- The weekly calendar page
- The event dialog

## Register 

It should have the following features : 
- A simple form with a firstname, lastname and password fields 
- Once the user is registered he should be able to access the calendar view

## Calendar

The calendar should have the following features :

- It should present a week view of the current date where each day of week the can be seen along with its hours in a simple UI
- It should have a datepicker that will change the calendar's date
- It should have a picker that can switch between calendar users and load theirs events accordingly 
- It should display all the events of the selected user
- It should display a form when the user click on an empty time slot and allow him to create an event in the calendar
- It should display a logout button so we can register another user and do the process again and swithc between users
## Event

The event dialog / popup will just display the details of the selected event along with 2 actions :

- delete the selected event
- edit the selected event

## Back end 

You can spawn any kind of database to store your data even use solutions like back end as a service.
- The informations of the user should be saved and the password hashed / encrypted.
- The events should be saved and linked to a given user.
- A simple CRUD should be implemented for the event entity in order to update / delete them.

### Bonuses :

- Implement a montly view 
- Implement a daily view
- Show a preview of the to-be-created event on the calendar while creating / editing an event
- Detect collision when trying to create an event on a non-empty timeslot and display an error message / toast.
- Load the calendar of 2 users side by side to prevent collisions when creating an event 
- Allow drag and drop while selecting an event in the calendar to pass events from one day to another
- Load your own personal calendar from google-calendar in the calendar
- Persist the data of your personal calendar into the database
- Persist the auth state of the app so we have a behavior when the logged in user does not have to log again once he is logged on a given browser.

Bonuses are just here to give you ideas of what can be achieved if you enjoy this little project but are ABSOLUTELY NOT mandatory

## Requirements

- Use typescript programming language and a modern front end / back end / fullstack  framework (react is best suited for front end).
- Your repository should include a `README` file that describes the steps to run your project.
- The rest of the stack is up to you.

Once you are done, please share a link to your repository

We will also take the following into consideration :

- Maintainability of the code
  - Code linting, test coverage..
  - Documentation
  - Clean code
- User Experience
- Creativity
