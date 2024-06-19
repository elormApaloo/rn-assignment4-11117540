# rn-assignment4-11117540
## JOBIZZ APP
The JobizzApp is a React Native application designed to help users log in and view job listings. The application features a login screen that collects user details and a home screen that displays featured and popular job cards. This project is a part of an assignment to replicate a given UI mockup from figma and implement various functionalities.

# FEATURES
I) User Authentication: Users can log in using their name and email.
II) State Management: Passing user data between screens using React Navigation.
III) Job Listings: Displays featured and popular job cards.
IV) Reusable Components: JobCard component to display job details.
V) Styled UI: Application styled to match the provided Figma design closely.


APP SCREENSHOTS
![Jobiz1](https://github.com/elormApaloo/rn-assignment4-11117540/assets/128927771/6134c618-668a-44e3-9596-cee15e723f61)
![Jobiz2](https://github.com/elormApaloo/rn-assignment4-11117540/assets/128927771/0720602a-1105-4c05-9876-7dba5d4f00f7)
![Jobiz3](https://github.com/elormApaloo/rn-assignment4-11117540/assets/128927771/850cbaa0-ce50-4f39-9948-adae09c0fc5b)
![Jobiz4](https://github.com/elormApaloo/rn-assignment4-11117540/assets/128927771/8264e9ac-cb2a-48f6-89ca-d2e8899e9137)
![Jobiz5](https://github.com/elormApaloo/rn-assignment4-11117540/assets/128927771/c7f71044-1780-41e1-b5ce-660111f835c5)
![Jobiz6](https://github.com/elormApaloo/rn-assignment4-11117540/assets/128927771/0e45bd51-2573-4e41-959b-32f3397487ca)
![Jobiz7](https://github.com/elormApaloo/rn-assignment4-11117540/assets/128927771/08b65772-9229-48a1-a871-86ca32c938f2)

# COMPONENTS
i) App.js
The entry point of the application, which sets up the navigation stack. It includes the LoginScreen and HomeScreen components.

ii) screens/LoginScreen.js
A screen that allows users to input their name and email and log in. It navigates to the HomeScreen with the user's details.

iii) screens/HomeScreen.js
A screen that displays the user's name and email along with a list of featured and popular job cards. It uses the JobCard component to display each job.
