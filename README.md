<a name="readme-top"></a>

# Course Sharing Platform
![homePage](https://github.com/chayaleA/Courses-server-client/assets/150287616/f4bf8585-5dbb-4dbb-90eb-92c1ce3175a3)

<details>
  <summary>Table of Contents</summary>
  <ol>
    <li><a href="#description">Description</a></li>
    <li><a href="#setup-instructions">Setup Instructions</a></li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#developers">Developers</a></li>
  </ol>
</details>

<!-- DESCRIPTION -->
## Description

Welcome to the Course Sharing Platform!
This application allows users to manage and share courses. Users can register, upload their own courses, and also view and learn from courses uploaded by others.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- TECHNOLOGIES USED -->
## Technologies Used

- **Frontend:** Angular
- **Backend:** NodeJS
- **Database:** MongoDB

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- SETUP INSTRUCTIONS -->
## Setup Instructions

This guide will walk you through setting up the project locally. Follow these steps to get a local copy up and running.

### Prerequisites

Before you begin, make sure you have the following installed:
- Node.js and npm. You can install them from here.
- Angular CLI. You can install it globally using npm with the following command:
  
  ```sh
  npm install -g @angular/cli
  ```

- MongoDB: Download and install MongoDB Community edition.

### Installation

1. Clone the Repository: Open your terminal and run the following command to clone the repository to your local machine:
    ```
   git clone https://github.com/chayaleA/Courses-server-client.git
   ```
    
4. Navigate to the client directory:
   ```
   cd Courses-server-client/Angular-Courses
   ```
5. Install Angular dependencies:
   ```
   npm install
   ```
6. Navigate to the Server Directory: Move to the server directory:
   ```
   cd ../NodeJS-Server-Courses
   ```
7. Install Node.js Dependencies: Install the necessary Node.js dependencies:
    ```
   npm install
   ```
Database Setup:
- Create a MongoDB Database: Set up a new MongoDB database.
- Update Connection String: Modify the connection string in the server's configuration file with your MongoDB database details.

1. Start the Server: Launch the server by running:
   ```
   npm start
   ```
2. Return to the Client Directory: Navigate back to the client directory:
   ```
   cd ../Angular-Courses
   ```
3. Start the Angular Development Server: Start the Angular development server by running:
   ```
   ng serve
   ```
Open your web browser and navigate to http://localhost:4200 to view the application.
Now you have the project set up locally and ready for development.
<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- USEAGE -->
## Usage

1. Navigate to the login page.
![connect](https://github.com/chayaleA/Courses-server-client/assets/150287616/572c56b3-df53-44b7-8d06-45c4a13cf039)

3. Enter your username and password to access the application.

   ![Login](https://github.com/chayaleA/EmployeesApp/assets/150287616/705c9092-ba36-47d2-9f96-a1bf2c616df7)
   
   If you don't have one, navigate to the registration page.
   
   ![register](https://github.com/chayaleA/EmployeesApp/assets/150287616/971a7415-cc0d-42ee-b612-cf54b9b03148)
   
   Enter your details there and you will receive an email to continue the process.
   
   ![sign up](https://github.com/chayaleA/EmployeesApp/assets/150287616/384b1d19-1c4f-46da-b8b2-a965f563bfa0)
   
6. Use the various features such as add course, search for course and watch it.

### Courses view
You can see the courses in the "All courses" page.
![All courses](https://github.com/chayaleA/Courses-server-client/assets/150287616/37368d70-e240-4c23-9c81-2aa7fa0d3f09)

To watch vidio, Hover over the course card and click on the "Start learn" button.
![start learn](https://github.com/chayaleA/Courses-server-client/assets/150287616/143248b9-9372-4923-b50d-d0be342f65e5)

And start watching.
![start watching](https://github.com/chayaleA/Courses-server-client/assets/150287616/62c3b948-743e-4fef-b50d-d387cd9069eb)

### Editing a course
You can edit a course only if you own it. Hover over the course card and click on the edit icon. 
![edit](https://github.com/chayaleA/Courses-server-client/assets/150287616/c92a0cff-4f42-4cfc-aa74-478e3067db95)

In the form that opens, update the course's details as you wish.
![update](https://github.com/chayaleA/Courses-server-client/assets/150287616/2af2f6ac-1aa0-48da-9dfe-51bd8e348164)

### Add a course.
Navigate to the "Add course" page.
![add course](https://github.com/chayaleA/Courses-server-client/assets/150287616/6f12b21a-1e42-4969-8666-d5a2d7a2b75d)

In the form that opens, insert the course's details as you wish.
![add course](https://github.com/chayaleA/Courses-server-client/assets/150287616/99695e8e-d62c-4ff4-aa99-700df04307a0)

You can also add vidio or delete once:

![add vidio](https://github.com/chayaleA/Courses-server-client/assets/150287616/a0ab151b-4e17-403e-ba56-13df3717f376)

### Search
You can search for a course easily, enter the name of the course you want to search for in the search box.
![search](https://github.com/chayaleA/Courses-server-client/assets/150287616/491f174f-a414-495f-812c-7d17d7bb9f33)

If you search for a course that does not exist, a notification will be displayed
![search not found](https://github.com/chayaleA/Courses-server-client/assets/150287616/3dd0266d-3883-4f72-a691-37bbd22a009e)

### Responsiveness
You can display the application even on a small screen and the display will change accordingly.
For example:
![sign up](https://github.com/chayaleA/EmployeesApp/assets/150287616/a02f0e60-b374-4c5b-981b-f044e73a0ae9)

### Navigation to page does not exist
In case you navigate to a page that does not exist, you will receive a 404 error.

![Page not found](https://github.com/chayaleA/EmployeesApp/assets/150287616/87a14a52-e8f0-40fb-ba18-38f59197d8ab)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- LICENSE -->
## License

This project is licensed under the MIT License.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- DEVELOPERS -->
## Developers

Chayale Avramovitz
<p align="right">(<a href="#readme-top">back to top</a>)</p>
