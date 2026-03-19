1) CanteenHub – School Canteen Ordering System
This is a simple web application made for a school canteen system. It allows users to view snacks, place orders, and manage student details. The project is built using basic React concepts and simple HTML, CSS, and JavaScript.

2) About the Project

=> The main idea of this project is to create an easy-to-use canteen ordering system where students can order snacks and the system keeps track of orders and student data.

=> This project was made as a learning project to understand how React works without using complex tools like Node.js or any build setup.

3) Setup Instructions

=>No installation is required to run this project.

4) Steps to run:

=> Download all the project files into one folder

=> Open the index.html file in any browser (Chrome, Edge, Firefox)

=> The app will start running

Note: Internet is required the first time because React and other libraries are loaded using CDN.

5) File Structure

canteenhub/

index.html → main file that runs the app
style.css → contains all styling
data.js → stores mock data
store.js → manages global state
components.js → reusable components
pages.js → page-level components
app.js → main React app
README.md
PROMPTS_USED.md
Technologies Used
React (via CDN)
ReactDOM
Babel Standalone (to use JSX directly)
HTML, CSS, JavaScript
No npm or external setup is required.

6)How Data is Managed
All the data is stored in data.js as simple JavaScript arrays.

7)To make the app feel realistic:

A fake delay function is used to simulate loading time
React Context is used for managing global state
Some basic operations include
Viewing snacks
Viewing students
Creating new students
Placing orders
Features
View snacks with price and order count
Place orders using a simple modal
Select student and quantity while ordering
View list of students with search option
Add new students with auto-generated referral code
View student details and their order history
Quick order option for students
Loading indicators on pages
Basic form validation
Responsive design for mobile devices

9)What I Learned

While building this project, I learned:
Basics of React and components
How to manage state using Context API
Handling forms and user input
Creating reusable components
Managing data without a backend

10)Future Improvements

Some improvements that can be added:
Backend integration with database
Authentication system

Payment integration

Admin dashboard for canteen staff
