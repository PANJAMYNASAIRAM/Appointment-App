

##Project Description

The Appointments App is a React-based task management application that allows users to create, organize, and manage their appointments efficiently. Users can add new appointments with a title and date, mark important appointments as starred, and filter the list to view only starred items.

This project is designed to demonstrate how modern web applications handle user input, dynamic data updates, and conditional rendering using React.

The application provides a form where users can enter appointment details such as title and date. Once submitted, the appointment is added to the list with a uniquely generated ID. The entered date is formatted into a human-readable format using a date utility library, enhancing the user experience.

Each appointment can be marked as starred (important) by clicking a star icon. The app includes a filter feature that allows users to toggle between viewing all appointments and only starred ones. This demonstrates efficient handling of state-based filtering logic.

The project follows a component-based architecture, where each appointment is rendered using a reusable AppointmentItem component. This improves code organization, reusability, and scalability.

Additionally, the app uses external libraries like UUID for generating unique IDs and date formatting utilities for better date presentation, reflecting real-world development practices.

Overall, this project is a great example of building an interactive and user-friendly application with React state management, event handling, list rendering, and third-party integrations. 

##Features

Add Appointment
Users can add appointments with title and date.

⭐ Mark as Starred
Highlight important appointments.

🔍 Filter Starred Appointments
Toggle to view only starred items.

📅 Formatted Date Display
Dates are shown in a readable format.

⚡ Real-time UI Updates
Instant updates without page reload.

🧩 Reusable Components
Uses AppointmentItem component.

🆔 Unique ID Generation
Each appointment has a unique ID using UUID.

##Technologies Used

React JS

JavaScript (ES6+)

HTML5

CSS3

JSX

Class Components

UUID (v4) – for unique IDs

date-fns – for date formatting 

##Installation Steps

1. Clone the repository git clone https://github.com/PANJAMYNASAIRAM/Appointment-App.git
2. Go to project folder "cd Appointment-App"
3. Install dependencies "npm install"
4. Start the project "npm start"

##Live Demo

https://PANJAMYNASAIRAM.github.io/Appointment-App


##How It Works

User enters title and date.

On clicking Add:

A new appointment object is created.

Date is formatted using date-fns.

Appointment is added to the list.

User can click ⭐ to mark/unmark as important.

Clicking Starred filter:

Shows only starred appointments.

UI updates instantly based on state changes.



# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)
