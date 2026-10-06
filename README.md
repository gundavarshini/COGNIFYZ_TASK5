
Employee Management Dashboard

Cognifyz Technologies — Full Stack Development Internship

Level 3 — Task 5

A professional Employee Management Dashboard developed as part of the Cognifyz Technologies Full Stack Development Internship – Level 3, Task 5.

The project demonstrates full-stack development concepts using Node.js, Express.js, RESTful APIs, HTML5, CSS3, and JavaScript. It provides an interactive dashboard for managing employee information with complete CRUD functionality.

Project Overview

The Employee Management Dashboard is a web-based application designed to manage employee records efficiently.

The application allows users to:

->View all employees

->Add new employees

->Edit existing employee information

->Delete employee records

->Search employees

->View employee statistics

->Track employee status

->Interact with a RESTful backend API

->Store employee information using a JSON data file

The project follows a structured frontend and backend architecture to demonstrate real-world web application development practices.

Features

Employee Management

->Add new employee records

->View employee information

->Edit employee details

->Delete employees

->Search employees by:
   1.Name
   2.Email
   3.Department
   4.Role
   5.Status
   
Dashboard Statistics

The dashboard provides real-time statistics including:

->Total Employees

->Active Employees

->Number of Departments

->System Status

RESTful API

The backend provides REST API endpoints for employee management.
| Method | Endpoint             | Description        |
| ------ | -------------------- | ------------------ |
| GET    |  /api/employees      | Get all employees  |
| GET    |  /api/employees/:id  | Get employee by ID |
| POST   |  /api/employees      | Add a new employee |
| PUT    |  /api/employees/:id  | Update employee    |
| DELETE |  /api/employees/:id  | Delete employee    |

Validation

The application includes validation for:

->Required fields

->Valid email format

->Duplicate employee email

->Employee existence

->API error handling

->Responsive Interface

The dashboard is designed to work across different screen sizes, including:

1.Desktop

2.Tablet

3.Mobile devices

Technologies Used

Frontend

1.HTML5

2.CSS3

3.JavaScript

4.Fetch API

Backend

1.Node.js

2.Express.js

Data Storage

1.JSON file

Development Tools

1.Visual Studio Code

2.Command Prompt

3.Git

4.GitHub

5.npm

Project Structure

Level3_Task5/
│
├── controllers/
│   └── employeeController.js
│
├── data/
│   └── employees.json
│
├── public/
│   ├── index.html
│   │
│   ├── css/
│   │   └── style.css
│   │
│   └── js/
│       └── app.js
│
├── routes/
│   └── employeeRoutes.js
│
├── node_modules/
│
├── package.json
├── package-lock.json
├── README.md
├── .gitignore
└── server.js

Application Architecture

The application follows a simple layered architecture:

                    Employee Management Dashboard
                              │
                              ▼
                         Frontend UI
                    HTML + CSS + JavaScript
                              │
                              ▼
                         Fetch API
                              │
                              ▼
                       Express.js Server
                              │
                              ▼
                         RESTful API
                              │
                              ▼
                    Employee Controller
                              │
                              ▼
                      employees.json

API Endpoints

Get All Employees

GET /api/employees

Returns all employee records.

Get Employee by ID

GET /api/employees/:id

Returns information about a specific employee.

Example:

GET /api/employees/1

Add Employee

POST /api/employees

Example request body:

JSON
{
  "name": "Priya Sharma",
  "email": "priya.sharma@example.com",
  "department": "Engineering",
  "role": "Software Developer",
  "status": "Active"
}

Update Employee

PUT /api/employees/:id

Example:

PUT /api/employees/1

Delete Employee

DELETE /api/employees/:id

Example:

DELETE /api/employees/1

Installation and Setup

1. Clone the Repository

git clone YOUR_GITHUB_REPOSITORY_URL

Navigate into the project:

cd Level3_Task5

2. Install Dependencies

Run:

npm install

This installs the dependencies specified in package.json.

3. Start the Application

Run:

node server.js

The server will start at:

http://localhost:5000

4. Open the Dashboard

Open the following URL in your browser:

http://localhost:5000

Available URLs

Employee Dashboard

http://localhost:5000

Employee API

http://localhost:5000/api/employees

API Health Check

http://localhost:5000/api/health

How the Application Works

1. Frontend

The frontend is built using HTML, CSS, and JavaScript.

The dashboard provides:

->Employee table

->Search functionality

->Statistics

->Add Employee form

->Edit functionality

->Delete functionality

2. Fetch API

JavaScript uses the browser's Fetch API to communicate with the Express backend.

For example:

fetch("/api/employees")

is used to retrieve employee records.

3. Express Server

Express handles incoming API requests and routes them to the appropriate controller.

4. Controller

The controller manages:

->Reading employee data

->Creating employees

->Updating employees

->Deleting employees

->Validating requests

->Sending API responses

5. JSON Storage

Employee information is stored in:

data/employees.json
CRUD Operations

The project demonstrates all four fundamental CRUD operations:

CREATE  →  POST
READ    →  GET
UPDATE  →  PUT
DELETE  →  DELETE

This makes the project a practical demonstration of RESTful API development.

User Interface

The dashboard includes:

->Professional navigation/header

->Dashboard statistics

->Employee directory

->Search functionality

->Status indicators

->Add Employee modal

->Edit Employee functionality

->Delete confirmation

->Success and error messages

->Responsive layout

Error Handling

The backend handles common API errors such as:

->Missing employee information

->Invalid employee ID

->Duplicate email address

->Employee not found

->Invalid requests

->API errors

Example response:

{
  "success": false,
  "message": "Employee not found"
}

Future Enhancements

The project can be further improved by adding:

1.MySQL or MongoDB database integration

2.User authentication and authorization

3.Admin and employee roles

4.Pagination

5.Advanced filtering

6.Employee profile pages

7.Department management

8.Sorting functionality

9.Export employee data to CSV

10.Cloud deployment

11.Dashboard charts and analytics

Learning Outcomes

Through this project, I gained practical experience in:

1.Full-stack web application development

2.Node.js and Express.js

3.RESTful API development

4.CRUD operations

5.Frontend and backend integration

6.JavaScript Fetch API

7.Form validation

8.JSON data handling

9.Responsive web design

10.Error handling

11.Project structure and organization

12.Git and GitHub workflow


Internship Task

Program: Full Stack Development Internship

Organization: Cognifyz Technologies

Level: Level 3

Task: Task 5 — Employee Management Dashboard

Developer: Varshini Reddy

Conclusion

The Employee Management Dashboard successfully demonstrates the integration of a responsive frontend with a Node.js and Express.js backend through RESTful APIs.

The project implements complete employee CRUD operations along with search, validation, statistics, error handling, and responsive UI design.

It serves as a practical demonstration of full-stack development concepts and REST API integration.

License

This project is developed for educational and internship purposes as part of the Cognifyz Technologies Full Stack Development Internship.
