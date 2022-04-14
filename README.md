

### Features
- Fully Functional Admin Panel
- Quiz Website with awesome UI
- Admin (teacher) can add class and students from admin panel
- Admin can create new quiz tests and add quiz questions in the test
- Option to add the Quiz questions from a spreadsheet (.xls, .xslx, .ods)
- Admin can view the statistics of the tests such as score of the students and quiz questions tests
- Generate run-time random passwords for users to give test
- Generate pdf option so that admin can directly print the student login credentials for the test



### Steps
1. Copy the whole project into your WAMP/LAMP/XAMPP folder.
2. Now create the database and import the script.sql file present in the database folder.
    1. If you want some sample data run the import the sampleData.sql file instead.
    2. Sample admin username:password for sampleData is admin:nimda
3. Modify the database credentials config.php file present in the database folder.
4. Now run the project to enjoy the Awesome Quiz System.

### Project Overview
**The website generates random passwords for students for each test.**
1. Dashboard
    1. Create new tests
    2. See previously created tests
2. New Test ( Needs class data first )
    1. Create new test for a class
    2. Test status:
      2.1 Pending - test won't be shown to students
      2.2 Running - test will be shown and students can give test
3. Add class / student
    1. Add a new class
    2. Add a new student to the class
4. View Data
    1. Shows student user id / roll numbers given a class
5. Test Details ( on clicking a previously created test from dashboard )
    1. Change status of Quiz ( PENDING / RUNNING )
    2. Complete / delete test
    3. Add new student explicitly for the test
    4. Add questions to the test

### Technology Stack
- HTML, CSS, BOOTSTRAP (Front-end)
- PHP (Backend)
- MYSQL Database
  