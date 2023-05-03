Download Link: https://assignmentchef.com/product/solved-cs3431-project-phase-2-sql-design-and-queries
<br>
<h1>SQL Design and Queries</h1>

In this phase you are required to convert the model you created for a <strong><em>Hospital System </em></strong>to a working relational model using the Oracle system.

Instructions to access Oracle (the pdf posted in Canvas System)

Important Note

Make sure to store the statements you write, e.g., CREATE TABLE statements, or SELECT queries in a file because you may need to re-use them multiple times.

<h2>Part 1 : Create the tables</h2>

Given the ER diagram and the initial relational model that you created in Phase 1, you are required to do the following:




<ul>

 <li>Build the tables in Oracle that reflect the given requirements in Phase 1. When converting from the ERD to the relational tables, you must follow the rules given in class to create a good design.</li>

</ul>




<ul>

 <li><strong>DO NOT use the create database command</strong>; instead use the create table command and make sure that your resulting work includes:</li>

</ul>




<ul>

 <li>All tables with descriptive names and fields.</li>

 <li>For the fields, choose the appropriate data types o Add the appropriate constraints, which must include (you may add more):</li>

</ul>

&#x25aa; Primary Keys and Unique constraints

&#x25aa; Foreign Key constraints

&#x25aa; Not Null constraints

&#x25aa; Domain constraints




<strong><em>Note: It is up to each team, to either keep using your own ER design from Phase 1, or you may use the design given in the posted solution of Phase 1. Both are accepted as long as your design is correct and captures all the requirements. Therefore, the solution to the queries (Part 2 below) may differ based on your design.</em></strong><em>  </em>

<h2>Part 2 : SQL Queries</h2>

Write SQL queries against the tables you created above to answer the following queries:




Q1: Report the id, specialty, gender and school of graduation for doctors that have graduated from WPI (“WPI”).

Q2: For a given division manager (say, ID = 10), report all regular employees that are supervised by this manager. Display the employees ID, names, and salary.

Q3: For each patient, report the sum of amounts paid by the insurance company for that patient, i.e., report the patients SSN, and the sum of insurance payments over all visits.  <strong>Note: If you keep the insurance coverage as a percentage, then compute this percentage before getting the sum. </strong>

Q4: Report the number of visits done for each patient, i.e., for each patient, report the patient SSN, first and last names, and the count of visits done by this patient.




Q5: Report the room number that has an equipment unit with serial number ‘A01-02X’.




Q6: Report the employee who has access to the largest number of rooms. We need the employee ID, and the number of rooms they can access.

<strong>Note: If there are several employees with the same maximum number, then report all of these employees.</strong>




Q7: Report the number of regular employees, division managers, and general managers in the hospital. The output should look like:

Type                         Count

——————————————

Regular employees        10

Division managers           5

General managers           2




Q8: For patients who have a scheduled future visit (which is part of their most recent visit), report that patient’s SSN, first name, and last name, and the visit date. Do not report patients who do not have a scheduled visit.

Q9: Report all equipment types that have less than two technicians that can maintain them.

Q10: Report the date of the coming future visit for patient with SSN = 111-22-3333. <strong>Note: This date should exist in the last (most recent) visit of that patient.  </strong>

Q11: For patient with SSN = 111-22-3333, report the doctors (only ID) who have examined this patient more than 2 times.

Q12: Report the equipment types (only the ID) for which the hospital has purchased equipment (units) in both 2010 and 2011. Do not report duplication.

<strong><u>Part 3 : Populate the Tables</u></strong> Insert records in the tables such that:

<ol>

 <li>All the constraints that you defined in Part 1 will be obeyed 2. Each of the above queries must return some records in their results 3. Insert information for at least:</li>

</ol>

<ol>

 <li>10 Patients</li>

 <li>10 Rooms, at least 3 of these rooms have 2 or more services</li>

 <li>3 Equipment types</li>

 <li>3 Equipment units of each type</li>

 <li>At least 5 patients have 2 or more admissions (visits)</li>

 <li>15 regular employees, 4 division managers, and 2 general managers</li>

 <li>Within the regular employees ensure that 5 are doctors and 5 are equipment technicians</li>

</ol>

<strong> </strong>

<strong>Test your queries against the data that you will insert and make sure they return the expected results. </strong>

<strong> </strong>

<strong> </strong>


