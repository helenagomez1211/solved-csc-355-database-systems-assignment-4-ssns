Download Link: https://assignmentchef.com/product/solved-csc-355-database-systems-assignment-4-ssns
<br>
<table class="highlight tab-size js-file-line-container" data-tab-size="8">

 <tbody>

  <tr>

   <td id="L6" class="blob-num js-line-number" data-line-number="6"></td>

   <td id="LC6" class="blob-code blob-code-inner js-file-line"><h6>Reading: The posted Lecture 7 and 8 Slides, and Sections 6.2-6.4 of Ullman/Widom. (For next week: Sections 6.6 and 3.1-3.2 of Ullman/Widom.)</h6></td>

  </tr>

  <tr>

   <td id="L7" class="blob-num js-line-number" data-line-number="7"></td>

   <td id="LC7" class="blob-code blob-code-inner js-file-line"></td>

  </tr>

  <tr>

   <td id="L8" class="blob-num js-line-number" data-line-number="8"></td>

   <td id="LC8" class="blob-code blob-code-inner js-file-line">Your task in this assignment is to write a set of SQL queries on a set of tables I supply.</td>

  </tr>

  <tr>

   <td id="L9" class="blob-num js-line-number" data-line-number="9"></td>

   <td id="LC9" class="blob-code blob-code-inner js-file-line"></td>

  </tr>

  <tr>

   <td id="L10" class="blob-num js-line-number" data-line-number="10"></td>

   <td id="LC10" class="blob-code blob-code-inner js-file-line">1. First, download the script file company.sql from the course web site and run it in SQLDeveloper to construct a database instance containing five tables: EMPLOYEE, DEPARTMENT, PROJECT, WORKSON, and DEPENDENT.</td>

  </tr>

  <tr>

   <td id="L11" class="blob-num js-line-number" data-line-number="11"></td>

   <td id="LC11" class="blob-code blob-code-inner js-file-line"></td>

  </tr>

  <tr>

   <td id="L12" class="blob-num js-line-number" data-line-number="12"></td>

   <td id="LC12" class="blob-code blob-code-inner js-file-line">Inspect the tables and their schemas in SQLDeveloper so that you understand the structure of the database. I recommend that you sketch the schema of the database, including all primary keys and foreign keys, before you write any queries.</td>

  </tr>

  <tr>

   <td id="L13" class="blob-num js-line-number" data-line-number="13"></td>

   <td id="LC13" class="blob-code blob-code-inner js-file-line"></td>

  </tr>

  <tr>

   <td id="L14" class="blob-num js-line-number" data-line-number="14"></td>

   <td id="LC14" class="blob-code blob-code-inner js-file-line">2. In a separate .sql file (do not modify company.sql), write a script that contains the following eight SQL queries (in this order):</td>

  </tr>

  <tr>

   <td id="L15" class="blob-num js-line-number" data-line-number="15"></td>

   <td id="LC15" class="blob-code blob-code-inner js-file-line"></td>

  </tr>

  <tr>

   <td id="L16" class="blob-num js-line-number" data-line-number="16"></td>

   <td id="LC16" class="blob-code blob-code-inner js-file-line">1. Give the names of all male employees whose direct supervisor has SSN 333445555.</td>

  </tr>

  <tr>

   <td id="L17" class="blob-num js-line-number" data-line-number="17"></td>

   <td id="LC17" class="blob-code blob-code-inner js-file-line"></td>

  </tr>

  <tr>

   <td id="L18" class="blob-num js-line-number" data-line-number="18"></td>

   <td id="LC18" class="blob-code blob-code-inner js-file-line">2. Give the SSNs of all employees in who work at least 12 hours per week on some project located in Houston.</td>

  </tr>

  <tr>

   <td id="L19" class="blob-num js-line-number" data-line-number="19"></td>

   <td id="LC19" class="blob-code blob-code-inner js-file-line"></td>

  </tr>

  <tr>

   <td id="L20" class="blob-num js-line-number" data-line-number="20"></td>

   <td id="LC20" class="blob-code blob-code-inner js-file-line">3. Give the average salary of all employees in the Research department</td>

  </tr>

  <tr>

   <td id="L21" class="blob-num js-line-number" data-line-number="21"></td>

   <td id="LC21" class="blob-code blob-code-inner js-file-line"></td>

  </tr>

  <tr>

   <td id="L22" class="blob-num js-line-number" data-line-number="22"></td>

   <td id="LC22" class="blob-code blob-code-inner js-file-line">4. For each project, give the project name and the total hours per week (by all employees) spent on that project. List the projects in descending order by the total hours per week spent on the project.</td>

  </tr>

  <tr>

   <td id="L23" class="blob-num js-line-number" data-line-number="23"></td>

   <td id="LC23" class="blob-code blob-code-inner js-file-line"></td>

  </tr>

  <tr>

   <td id="L24" class="blob-num js-line-number" data-line-number="24"></td>

   <td id="LC24" class="blob-code blob-code-inner js-file-line">5. Give the SSNs and names of all employees who do not work on any project.</td>

  </tr>

  <tr>

   <td id="L25" class="blob-num js-line-number" data-line-number="25"></td>

   <td id="LC25" class="blob-code blob-code-inner js-file-line"></td>

  </tr>

  <tr>

   <td id="L26" class="blob-num js-line-number" data-line-number="26"></td>

   <td id="LC26" class="blob-code blob-code-inner js-file-line">6. Give the first names only of all employees in department 4 who have at least one dependent.</td>

  </tr>

  <tr>

   <td id="L27" class="blob-num js-line-number" data-line-number="27"></td>

   <td id="LC27" class="blob-code blob-code-inner js-file-line"></td>

  </tr>

  <tr>

   <td id="L28" class="blob-num js-line-number" data-line-number="28"></td>

   <td id="LC28" class="blob-code blob-code-inner js-file-line">7. Give the last names of all employees whose supervisor’s supervisor has SSN 121231234. List the last names in alphabetical order.</td>

  </tr>

  <tr>

   <td id="L29" class="blob-num js-line-number" data-line-number="29"></td>

   <td id="LC29" class="blob-code blob-code-inner js-file-line"></td>

  </tr>

  <tr>

   <td id="L30" class="blob-num js-line-number" data-line-number="30"></td>

   <td id="LC30" class="blob-code blob-code-inner js-file-line">8. For each department whose average salary is more than $33,000, give the department name, how many employees are in that department, and the average salary for the department.</td>

  </tr>

  <tr>

   <td id="L31" class="blob-num js-line-number" data-line-number="31"></td>

   <td id="LC31" class="blob-code blob-code-inner js-file-line"></td>

  </tr>

 </tbody>

</table>


