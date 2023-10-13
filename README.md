# HabitTracker

A web application which help you to create, update, delete and track your habit on daily basis. 
It is user specific app, which mean a user can track their habit, and mark it as done , or not done. 
The project is built using a tech stack consisting of Node.js for the server-side scripting.
Express for handling HTTP requests and routing.
MongoDB for storing and managing the data and EJS for rendering the views and templates.

## Installation
To run this application on your local machine, please follow these steps:

Clone this repository using the following command:
```
$ git clone https://github.com/priyamprakash/Habit_Track.git
```
Install the required dependencies using the following command:
```
$ npm install 
```
Start the application using the following command:
```
$ npm start 
```
Open the application in your web browser by visiting the following URL:
```
$ http://localhost:8000 
```

## Usage
Once you have the application up and running, you can start using it by following these steps:
* Sing-up/Sign-in into your account.
* Click on the "Add Habit" button to create a new habit.
* Enter the name of the habit you want to track.
* Click on the "Save" button to save the habit.
* To mark a habit as complete/incomplete for the day, simply click on the corresponding icon.
* To delete a habit, click on the "Delete" icon next to it.
* To see today's habits, click on "Show Daily" button.
* To edit a habit, click on the "Edit" icon next to it.

## Folder Structure
```
Habit Tracker
    |
    |               |--->css
    |--->assets---->|--->img
    |               |---> js
    |
    |               |--->flashMiddleware.js
    |--->config---->|--->mongoose.js
    |               |--->passport_local.js
    |
    |                  |-->habit_controller.js
    |--->controllers-->|-->home_controller.js
    |                  |-->user_controller.js
    |
    |               |-->habit.js
    |--->models---->|
    |               |-->user.js
    |
    |              
    |               |-->habit.js
    |--->routes---->|-->index.js
    |               |-->user.js
    |
    |              
    |              |--->_header.ejs
    |              |--->404.ejs
    |              |--->daily_view.ejs
    |              |--->forget_password.ejs
    |--->views---->|--->home.ejs
    |              |--->layout.ejs
    |              |--->user_sign_in.ejs
    |              |--->user_sign_up.ejs
    |              |--->weekly_view.ejs
    |
    |-->node_modules
    |-->.gitignore
    |--> index.js
    |--> package-lock.json
    |-->package.json
    
 ````

## Screenshots
### Home Page
![Screenshot (422)](https://github.com/priyamprakash/Habit_Tracker_CN/assets/65361533/8a570aee-27b9-4e68-a819-0c169b4bdfc7)

### Sign-up Page
![Screenshot (420)](https://github.com/priyamprakash/Habit_Tracker_CN/assets/65361533/0e005fc1-1f6c-434c-ad70-0be7c763bfa8)

### Sign-in Page
![Screenshot (421)](https://github.com/priyamprakash/Habit_Tracker_CN/assets/65361533/43a27510-ee40-4dd4-96e6-1b309fc47b17)

### Weekly View Page
![Screenshot (424)](https://github.com/priyamprakash/Habit_Tracker_CN/assets/65361533/0c4a4e7f-3604-4b53-8d5f-2d53993bbee2)


## Contributing
Contributions are always welcome! If you have any suggestions for improving this application, please feel free to create a pull request or open an issue.




