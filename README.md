## Sprint 5 Content - BOOTCAMP TRIPLETEN
### Basic Database Concepts

#### 1. Command Line Basics
- **Introduction**: Understanding the basic principles of interacting with operating systems via the command line.
- **Operating Systems**: Differentiating between operating systems and their interfaces.
- **Command Line**: Using the command line to manage systems and files.
- **Connecting to a Remote Server**: Methods and commands for accessing servers via SSH.
- **Displaying Directory Contents**: Commands for listing files and folders in a directory.
- **Navigating Directories**: Moving between directories using the command line.
- **Managing Files and Directories**: Creating, deleting, and manipulating files and directories.
- **Working with Text Files**: Editing and viewing text files in the command line.
- **Copying and Moving**: Commands for copying and moving files and directories.

#### 2. Basic SQL Concepts
- **Introduction**: Fundamentals of SQL and its importance for data management.
- **Database Testing**: Importance of testing to ensure data integrity in databases.
- **Relational Database**: Concept of relational databases and how they organize data in tables.
- **Data Slicing**: Extracting subsets of data from tables.
- **Aggregation Functions**: Using functions like `SUM`, `COUNT`, and `AVG` to perform operations on data sets.
- **Data Type Conversion**: Changing data types in SQL queries.
- **Data Grouping**: Using the `GROUP BY` clause to organize data into groups.
- **Data Sorting**: Applying the `ORDER BY` clause to classify query results.
- **Database and Console**: Interacting with databases through SQL consoles.
- **Data Manipulation**: SQL commands to modify data in tables:
  - **INSERT**: Adding new records.
  - **UPDATE**: Updating existing records.
  - **DELETE**: Removing records.
- **Database Dump**: Creating backups of the data stored in databases.


# Urban.Scooter - Application Testing

## Project Description
Urban.Scooter is a service that allows users to rent electric scooters for a few days. This project aims to conduct thorough testing of the application to ensure its functionality and performance. In addition to testing, we will also cover fundamental concepts of databases, which are essential for understanding how data is stored and manipulated within the application.

## Testing Objectives
The focus of the tests will be on specific functionalities of the application, as detailed in the documentation. The main objectives include:

- **Verify functionalities**: Test the main functionalities of the application to ensure they meet the specified requirements.
- **Field validation**: Test the fields on the "Place Order" screen and other relevant forms.
- **API testing**: Evaluate the resources of the application’s API to ensure that interactions with the server work as expected.


## Testing Methodology

### 1. Preparation and Analysis
- **Documentation Study**: Examine the application documentation, which contains lists of requirements and designs, as well as the URLs to which the application sends data.
- **Mind Map Creation**: Develop a mind map to visualize the requirements and organize testing information.
- **Resource Division**: Break down application resources into atomic blocks and define test objects.

### 2. Test Design
- **Test Planning**: Design tests to cover all identified requirements.
- **Application of Testing Techniques**: Use equivalence classes, boundary values, and decision tables as needed.
- **Test Optimization**: Minimize the number of tests performed, focusing on UI tests and resource logic.

### 3. Test Execution
- **Test Execution**: Conduct the tests and record the results as **PASSED** or **FAILED**.
- **Bug Reporting**: If a test fails, create a bug report in Jira and enter the ID in the results table.

### 4. Request Verification
- **Use of Tools**: Utilize tools such as DevTools or Postman to verify requests to specific URLs.

## Project Structure
The final project result should include:

- **Google Spreadsheet**: Link to the spreadsheet with test results.
- **Mind Map**: Image of the mind map created during the analysis.
- **Bug Reports**: Links to the bug reports in Jira.

### Results Preparation
Attach the test checklists in the following tabs of the template:

- **Task 2: Checklist**: Containing results from the tests executed and bug reports.
- **Task 2: Validation Data**: For validating fields on the "Place Order" screen.
- **Task 3: API Checklist**: Results from API tests and bug reports.

## Tasks

### Task 1: Theoretical Testing
The first task is a large theoretical test that can be performed in several stages. You can complete part of it, move on to another task, and return to the test later. This will help to alternate between theory and practice.

### Task 2: Web Application Testing
The second task involves testing a web application. This is the largest of the tasks and requires careful analysis of all functionalities.

### Task 3: API Testing
The third task consists of testing an API. First, study the requirements, and if anything is unclear, ask your tutor. After that, begin the testing process.

## Specific Tests

### Application Functionality
- **"Order Status" Screen**: Create a checklist of functional requirements.
- **"Place Order" Screen**: Create tests to validate the fields, filling them in a table according to the model.

### Urban.Scooter API
- **Back-end Requirements**: Examine the requirements and API documentation.
- **API Checklist**: Create a checklist to test the API against the specified requirements.

## Conclusion
The tests conducted will ensure that Urban.Scooter operates effectively and meets user expectations. Through detailed documentation and bug reports, we aim to continuously improve user experience and application functionality.
