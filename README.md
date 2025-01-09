# Register User Project 📝

This project shows how to create a simple user registration system using JSP (JavaServer Pages) and Servlets. Users can fill in their details through a form, and the information is saved in a MySQL database.

## Project Files 📂

- **JSP File**: A web page with a form for users to enter their details.
- **Servlet (`Register.java`)**: Handles the form submission and saves the data to the database.

## Features ✨

- **Registration Form**: Users can enter their Name, Email, Password, Gender, and City.
- **Data Handling**: The data from the form is sent to the server.
- **Database Storage**: Saves the user details in a MySQL database.
- **Feedback Messages**: Shows a message to the user whether the registration was successful or not.

## Files Included 🗂️

### 1. `Register.jsp`
This is the form where users enter their details:
- **Fields**: 
  - Name
  - Email
  - Password
  - Gender (Male/Female)
  - City (Dropdown selection)
- **Submit Button**: Sends the form data to the `regForm` servlet.

### 2. `Register.java` (Servlet)
This file processes the form data:
- **Gets User Data**: Takes the details entered in the form.
- **Connects to Database**: Uses `JDBC` to connect to a MySQL database.
- **Saves Data**: Inserts the user’s information into the database.
- **Shows Messages**: 
  - **Success**: If the registration is successful, it shows a success message.
  - **Failure**: If there’s an error, it shows an error message.

## How to Use 🚀

1. **Set Up the Database**:
   - Create a database called `yt_demo`.
   - Create a table `register` with columns: `name`, `email`, `password`, `gender`, `city`.

2. **Run the Project**:
   - Copy the JSP and Servlet files to your server (e.g., Apache Tomcat).
   - Open the form in a web browser, fill in the details, and submit.

3. **See the Results**:
   - A message will appear saying if the registration was successful or if there was an error.

## Requirements 📋

- Java Development Kit (JDK).
- A web server like Apache Tomcat.
- MySQL database installed.
- Basic understanding of JSP, Servlets, and JDBC.


