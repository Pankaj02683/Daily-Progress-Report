# Daily-Progress-Report
<head>
<link rel="stylesheet" href="github.css">
 </head>
 
<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 1-Feb-2024** 
<h3 align='center'>Introduction to Linux & Installing Ubuntu</h3>

<p align="justify">Linux is an open-source operating system like other operating systems such as Microsoft Windows, Apple Mac OS, iOS, Google android, etc. An operating system is a software that enables the communication between computer hardware and software. It conveys input to get processed by the processor and brings output to the hardware to display it. This is the basic function of an operating system.</p>

- Download the linux distribution of your choice.
- Creating Boot pendrive using rufus.exe in windows.
- Restart the system and open boot menu using boot key. (Eg.- F8, F2 etc.)
- Select your boot device in boot menu.
- Select Install Ubuntu then Click Normal Installation.
- Select where to install alongside window or Erase disk or something else.
- Then Click next and start ubuntu installation.
- For More detail about Installation Guide [Click here](https://phoenixnap.com/kb/install-ubuntu-20-04)
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 2-Feb-2024** 
<h3 align='center'>Introduction to LAMP Stack</h3>

<p align="justify">The LAMP stack is a popular open-source solution stack used primarily in web development.LAMP consists of four components necessary to establish a fully functional web development environment. The first letters of the components' names make up the LAMP acronym:</p>

- Linux is an operating system used to run the rest of the components.
- Apache HTTP Server is a web server software used to serve static web pages.
- MySQL is a relational database management system used for creating and managing web databases, but also for data warehousing, application logging, e-commerce, etc.
- PHP, Perl, and Python are programming languages used to create web applications.
- Installing lamp on Ubuntu System.
- Verifying by run LAMP on localhost.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 3-Feb-2024**
<h3 align='center'>Run CGI Script</h3>

<p align="justify">CGI stands for Common Gateway Interface. CGI defines a standard way in which information may be passed to and from the browser and server. Any program or script that can process information according to the CGI specification can, in theory, be used to code a CGI script.</p>

- Create a CGI script.
- Run it on Localhost using Apache Server.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 4-Feb-2024**
<h3 align='center'>Image to Video</h3>

- Create a Python Script.
- Install pip, ImageMagick on your system.
- Go to ---- /etc/ImageMagick-6/policy.xml file. 
- Comment out line "policy domain="path" rights="none" pattern="@*" 
- Run the script by using python3 filename.py.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 5-Feb-2024**
<h3 align='center'>Introduction to Frappe</h3>

<p align="justify">Frappe, pronounced fra-pay, is a full stack, batteries-included, web framework written in Python and Javascript with MariaDB as the database. It is the framework which powers ERPNext, is pretty generic and can be used to build database driven apps.</p>

#### Why Frappe?

<p align="justify">The key difference in Frappe compared to other frameworks is that meta-data is also treated as data. This enables you to build front-ends very easily. We believe in a monolithic architecture, so Frappe comes with almost everything you need to build a modern web application. It has a full featured Admin UI called the Desk that handles forms, navigation, lists, menus, permissions, file attachment and much more out of the box.</p>

- Install Frappe-bench and its required tool. For more info [Click here](https://frappeframework.com/docs/v13/user/en/installation).
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 7-Feb-2024**
<h3 align='center'>Creating App and Site & Run on Local Server in Frappe</h3>

- Start Bench in one Terminal.
- In Second Terminal.
- Create App by using **bench new-app library_management** inside Frappe-bench Directory.
- Create site by using **bench new-site library.test** inside Frappe-bench Directory.
- Run Site on Localhost by using library.test custom port name.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 8-Feb-2024**
<h3 align='center'>Introduction to GitHub Pages</h3>

- Getting Information What is GitHub Pages.
- Create a New Repository on GitHub.
- Setting Repository as the main branch and setting a theme for GitHub pages.
- "policy domain="path" rights="none" pattern="@*"- Learning about Personal access tokens for push Local Repository on GitHub.
- Learning Syntax of Markdown Language in GitHub.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 9-Feb-2024** 
<h3 align='center'>Introduction to Reveal.JS, Pandoc, Use of Markdown in Reveal.js</h3>

- What is Reveal.JS, Pandoc, Use Markdown in Reveal.js.
- Creating Presentation in Reveal.JS using Markdown only.
- Learn how to show presentation on Local machine.
- Converting .md file into .pdf file using Pandoc.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 10-Feb-2024** 
<h3 align='center'>Introduction to Docker, Virtual Machine and ERPNext</h3>

**What is Docker?**
<p align="justify">Docker is popular virtualization software that helps its users in developing, deploying, monitoring, and running applications in a Docker Container with all their dependencies (frameworks, libraries, etc.) to run an application in an efficient and bug-free manner.Docker Containers are Light-weight, Applications run in isolation,Occupies less space, Easily portable and highly secure, Short boot-up time.</p>

- It can run multiple containers on a system.
- It can start multiple containers at a time on the Docker engine.
<br>

**What is Virtual Machine?**
<p align="justify">A Virtual Machine (VM) is a compute resource that uses software instead of a physical computer to run programs and deploy apps. One or more virtual “guest” machines run on a physical “host” machine. Each virtual machine runs its own operating system and functions separately from the other VMs, even when they are all running on the same host. This means that, for example, a virtual MacOS virtual machine can run on a physical PC.</p>

- It can start only a single VM on a VMX.
- It can run only a limited number of VMs on a system.
<br>

**What is ERPNext?**
<p align="justify">ERPNext is a full-featured business management solution that helps SMEs to record all their business transactions in a single system. With ERPNext, SMEs can make informed, fact-based, timely decisions to remain ahead in the competition. It serves as the backbone of a business adding strength, transparency, and control to your growing enterprise.</p>
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 11-Feb-2024** 
<h3 align='center'>Installing ERPNext in Frappe-bench</h3>

- If Frappe-bench installed in system follow second method otherwise you will get error.
- Installation done with two manner 
- By Adduser in linux
- And create Erpnext app and site in frappe-bench Directory.
- For installation steps [Click here](https://github.com/D-codE-Hub/ERPNext-installation-Guide/blob/main/README.md). 
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 12-Feb-2024** 
<h3 align='center'>Introduction to Selenium, Budibase, Coding Standard for Program</h3>

- Selenium is browser automation tool by which you can create a script which automatically done task like fill credential and click for search.
- Budibase is a development platform designed for speed and productivity. 
- With Budibase, developers no-longer experience repetition, long-dev cycles, and frustration. Instead, developers are more productive, happier, and can deliver applications they're proud of in minutes.
- How to write code in Any script so that it can easily read by other programmer who contribute to your project, take variable name which should be relevant with its function.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 14-Feb-2024** 
<h3 align='center'>Try to Solve Error Redis-Server During Installation</h3>

**Error while loading shared libraries: libatomic.so.1: cannot open shared object file: No such file or directory**

- sudo apt purge libatomic1.
- Install houncho if file is missing.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 15-Feb-2024** 
<h3 align='center'>Introduction to Education Module in ERPNext</h3>

The Education domain in ERPNext is designed to meet requirements of any organization which imparts knowledge and believe in doing so in an organized fashion. It has already been used at schools, colleges and even in private firms.

It helps you to effectively manage administration and allows you to focus on what is most important for your institute, to educate!
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 17-Feb-2024** 
<h3 align='center'>Introduction to Jinja Templating</h3>

<p align='justify'>Jinja is a fast, expressive, extensible templating engine. Special placeholders in the template allow writing code similar to Python syntax. Then the template is passed data to render the final document.</p>
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 18-Feb-

2024** 
<h3 align='center'>Trying to Fetch Data from Database Using Jinja Templating</h3>

- Write a Python Script for establishing connection with Mariadb.
- If it still gives permission error try to solve it.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 19-Feb-2024** 
<h3 align='center'>Working with Server</h3>

- Resetting the password of server.
- Trying to install Erpnext on server.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 21-Feb-2024** 
<h3 align='center'>MySQL Administration, Converting PDF to MD File</h3>

- Today I created a new doctype in ERPNext with different options.
- Then learned about the administration concept of database.
- Converting pdf file to md and applying changes using markdown.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 22-Feb-2024** 
<h3 align='center'>Introduction to Vue.js Basics</h3>

<p align="justify">Vue.js is a progressive framework for building user interfaces. It is designed to be incrementally adaptable and can easily integrate with other projects and libraries. Vue.js is versatile and can be used to create simple components for existing projects or to build complex single-page applications when used in combination with modern tooling and supporting libraries.</p>

- Setting up a basic Vue.js project.
- Understanding the core concepts such as components, data binding, and events.
- Creating a simple application to demonstrate the basic functionalities of Vue.js.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 23-Feb-2024**
<h3 align='center'>How to Use SSH</h3>

- Login to Server, Try to help other member to install LDAP on server.
- Apply different permission-related queries on database for different users.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 24-Feb-2024**
<h3 align='center'>Learning About How to Import Data in ERPNext from CSV File</h3>

- Try to import data in ERPNext app through CSV file.
- Apply pagination in ERPNext webpage.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 25-Feb-2024**
<h3 align='center'>Import Data in MySQL</h3>

- Try to import data in MariaDB through CSV file.
- Learning the concept of permissions on Server.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 28-Feb-2024**
<h3 align='center'>Creating Webpage in ERPNext</h3>

- Creating static webpage on ERPNext.
- Learning Frappe School Module.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 2-Mar-2024**
<h3 align='center'>Learning Module from Frappe School</h3>

- Creating new site with new app.
- Creating Doctype and linking Doctype with others.
- Learning Jinja Script for Frappe doctypes.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 3-Mar-2024**
<h3 align='center'>Learning Meeting App</h3>

- Understanding the structure of the meeting app.
- Understanding the JavaScript code and Python code of the meeting app.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 4-Mar-2024**
<h3 align='center'>Presentation and Discussion of Meeting App</h3>

- Discussing the importance of Doctype in Frappe-Framework.
- Discussing with the team how it works and how to create a new custom app.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 5-Mar-2024**
<h3 align='center'>Creating Own Noticeboard App</h3>

- First, create the app and install it on the website.
- Create Doctype according to the structure discussed in the team.
- Provide it web view.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 7-Mar-2024**
<h3 align='center'>Customize Noticeboard App</h3>

- Writing code to show the correct date format e.g., March 7, 2024.
- Writing code to show the name of the user who uploaded the notice.
- Making its view user-friendly in both form and webpage.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 8-Mar-2024**
<h3 align='center'>Learning About Built-in Note Doctype</h3>

- Differentiating between Noticeboard app and the built-in note app.
- Understanding Note Doctype functionality.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 9-Mar-2024**
<h3 align='center'>Learning About Workflow</h3>

- Learning Workflow in ERPNext.
- Understanding how to pass control to different managers.
- Trying to implement the Purchase Order List and getting it approved by the purchase manager and material manager.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 11-Mar-2024**
<h3 align='center'>Working with Dynamic Pages in Frappe</h3>

- First, create the www directory in any Frappe app.
- Create two files: a Python file for fetching data from the database and an HTML file using Jinja template to show records on the webpage.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 12-Mar-2024**
<h3 align='center'>Trying to Add Pagination on Dynamic Page</h3>

- First, try to control sending data to the Python file from the HTML file.
- When this doesn't work, create a post on discuss.erpnext and try using JavaScript based on the answers received.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 14-Mar-2024**
<h3 align='center'>Learning About Fee Module in ERPNext</h3>

- Learning how to create new fees for students.
- Understanding different prerequisites before creating new fees, such as Student, Fee Category, Fee Structure, etc.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 15-Mar-2024**
<h3 align='center'>Creating Fees in ERPNext on Server</h3>

- Creating different fee categories available in school like Tuition Fee, Hostel Fee, etc.
- Searching how to add bus fees based on their route.
- Creating students, enrolling them in programs, creating courses, etc.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 16-Mar-2024**
<h3 align='center'>Creating Fee Structure</h3>

<p align="justify">Creating new fee structures. When creating new fees, fees should be added automatically by selecting the Fee Structure. We are trying to add an admission fee in the Student form along with exploring where all the records are saved to keep track of how many fees are paid or pending. We track this record in the 'Report Student Fee Collection' doctype. We are also trying to add a penalty on overdue fees but find this feature is not currently available in ERPNext.</p>
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 17-Mar-2024**
<h3 align='center'>Solve Problem While Deleting Records</h3>

<p align="justify">Exploring how to delete such payment entries that are linked with GL Entry. For this, we need to go to Account Settings and enable the checkbox "Delete Accounting and Stock Ledger Entries on the deletion of Transaction" and then all such canceled entries delete normally.</p>
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 19-Mar-2024**
<h3 align='center'>Add Frappe App in Repository</h3>

- First, go through the git documentation to ensure everything is done properly.
- Finding the command to add a repository from the terminal to GitHub.
- After completing the task, made documentation on GitHub pages to help other team members.
- For Documentation [Click here](https://vishal78626.github.io/Add-Frappe-app-in-GitRepo/)
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 21-Mar-2024**
<h3 align='center'>Understand the Code Available in Frappe</h3>

<p align="justify">Understanding the code available in all-products, then adding items to item lists, facing some problems initially, but eventually adding items to (item lists), then (website item), and setting up e-commerce settings. Successfully using search, prev & next, and trying to apply it in a pagination file.</p>
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 22-Mar-2024**
<h3 align='center'>Installing New ERPNext on Server</h3>

- First, install the Frappe framework, then install ERPNext with the education domain.
- Collecting student and teacher data from Nankana Sahib Public School.
- Arranging data according to Doctype in ERPNext.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 23-Mar-2024**
<h3 align='center'>Arrange Naming Series Company-Wise</h3>

<p align="justify">When a new applicant is registered in the system, the default system generates a naming series. Trying to change it company-wise, e.g., if a member of company A, then naming series includes A-2024-00001. Followed the official ERPNext tutorial [More Detail](https://docs.erpnext.com/docs/v13/user/manual/en/customize-erpnext/articles/company-wise-naming-series#:~:text=The%20need%20is%20to%20create,be%20SINV%2DB%2D0001.), faced some issues, but resolved them using (.abbr.-.YYYY.-) in the Naming Series option.</p>
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 24-Mar-2024**
<h3 align='center'>Arranging Student Data</h3>

- As there is a large amount of student data in school, we need to correct it.
- Divided work among team members and understood the concept of filter, concatenate, etc., in Excel.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 25-Mar-2024**
<h3 align='center'>Learning Employee Salary Module</h3>

- Learning Payroll module in ERPNext for Employee or Teacher salary.
- Understanding Payroll Period, Income Tax Slab, Salary Component and Structure, and Generating Salary Receipts.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 26-Mar-2024**
<h3 align='center'>Introduction to Vue.js Basics</h3>

<p align="justify">Vue.js is a progressive framework for building user interfaces. It is designed to be incrementally adaptable and can easily integrate with other projects and libraries. Vue.js is versatile and can be used to create simple components for existing projects or to build complex single-page applications when used in combination with modern tooling and supporting libraries.</p>

- Setting up a basic Vue.js project.
- Understanding the core concepts such as components, data binding, and events.
- Creating a simple application to demonstrate the basic functionalities of Vue.js.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 28-Mar-2024** 
<h3 align='center'>Payroll Entry in Erpnext</h3>

- In payroll entry we can create salary for bulk of employee.
- For payroll entry we have an attendance of employees, only then we can create payroll entry for employee.  
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 29-Mar-2024**
<h3 align='center'>Web Manager Vs Website Manager</h3>

- For new users we create web manger who has permission to create webpage,See on website, Search box, can't create webform.
- Website Manager can delete webpage, read webpage but cannot create, Search bar not shown.
- We assign new user web user so that they can access gne11 website with some restriction.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 30-Mar-2024**
<h3 align='center'>Adding New role and Give Permission to new Users</h3>

- When we got new user for allow them to create Library Management System we need to give them the access of doctype modules.
- For this we go to doctype list and create new role where new user create doctype by can't delete doctype.
- Similarly for Module we use select permission where user can select module but can't read module.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 1-Apr-2024**
<h3 align='center'>Working with Client Script in Form</h3>

- Client Script is script in which we add some action on form so that we validate data or do other function.
- Webform script is which is done in webform while creating new webform.
- For Reference we use Web form Scripting Documentation [Click here](https://frappeframework.com/docs/v13/user/en/api/form) 
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 2-Apr-2024**
<h3 align='center'>Sending Daily report to Student Group</h3>

- For Sending daily report in student group First we add student and Intructor in student group with batch name.
- Then we create email group and add students email where we send them email at same time.
- In Student group on view option we create new newsletter with content and add email group then we are able to send email to group of Student. 
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 5-Apr-2024**
<h3 align='center'>Trying to create Daily Daity without using email</h3>

- For this first we create a doctype.
- Trying to add permission in doctype so that only student group can access these Dairy.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 6-Apr-2024**
<h3 align='center'>Creating Library Management System</h3>

- As per official documentation I create Library Management App.
- Install app on site then creating doctype.
- Use Features like Naming Series, Permission Rules.
- Learn Controller methods, Doctype Features, Form Scripts.
- Adding Web view for preview Articles on web.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 7-Apr-2024**
<h3 align='center'>Trying to make pagination and filter on webpage</h3>

- First we are's trying to read built-in frappe file so that we can use it in webpage.
- Make changes in built in files to apply it on global in frappe.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 8-Apr-2024**
<h3 align='center'>Making Questions based on Library Management Tutorial</h3>

- The Topics for preparing questions for trainee are Creating Apps, Sites & Doctype.
- Making mcq question's based on steps followed when creating Library management system.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 9-Apr-2024**
<h3 align='center'>Learning bash script</h3>

- As per Questions Created for Trainee it contain different format.
- Then I need to create bash script using sed to find and replace the wrong format symbols.
- The example of sed command is 'sed 's/$ //gI' filename'. 
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 11-Apr-2024**
<h3 align='center'>Learning Human Resource Module</h3>
<p align='justify'>The Human Resources (HR) module covers the processes related to the HR department of a company. It maintains a complete employee database including contact information, salary details, attendance, performance evaluation, leaves, and appraisal records.The most important feature here is processing the payroll by using Payroll Entry to generate Salary Slips. Most countries have complex tax rules stating which expenses the company can make on behalf of its Employees.</p>
<p align='justify'>There are a set of rules for the company to deduct taxes and social security from employee payroll. ERPNext accommodates all types of taxes and their calculation.</p>
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 12-Apr-2024**
<h3 align='center'>Learning Permission for Human Resource & Payroll</h3>

- For Finding permission rule of HR Role we create a user in Erpnext.
- Then assign HR User role to new user and find what permissions are available.
- After this we use HR manager Role and learn its role for Human Resource & Payroll.
- We find that HR manager has more power than HR user in some case like to delete and cancel records etc. 
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 13-Apr-2024**
<h3 align='center'>Email Notification for every push operation</h3>

- For this we need to go inside the repository settings.
- Go to Integration section, Add email address the limitation is only two email address are used there.
- To solve this notification, We find one more solution where in commit section optional description.
- We can add the user profile name where we want to send email notification. 
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 16-Apr-2024**
<h3 align='center'>Working on Daily Dairy as per new specification</h3>

- First we create new app named Daily Dairy.
- Create new doctype under new app Daily Dairy Class1.
- Creating fields and write some code for add fields automatically.
- Now we are working on permission how to show it to only specific group.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 18-Apr-2024**
<h3 align='center'>Creating Daily Diary module in Notification App</h3>

- Installing Notification app on local system.
- Creating module named Daily Diary save it on notification app.
- Then push app on other team-mate github repository. 
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 19-Apr-2024**
<h3 align='center'>Adding app on friend Repository</h3>

- First I fork Repository in my Repository.
- Install App on another local system then made changes on notification app like adding some code and fields.
- Then again push code in my github Repository.
- Create new pull request for Repository where I Frok Repository & Merge changes in main Repository.
- But when we use desk there is no changes in desk as per changes on git, then we check the local directory changes must there but it can't refelect in frappe.
- So here we again remove app and again install app & this time chnages work properly.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 20-Apr-2024**
<h3 align='center'>Adding Filters on doctype as per requirement</h3>

- As per requirement changes for achieve this we add filter in list-view like class-wise, subject-wise, date-wise filter.
- For creating filters on desk we need to go to Doctype.
- On click edit we need check option In List View, In Standard Filter.
- Then on save changes filters are available on desk list-view of doctype.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 21-Apr-2024**
<h3 align='center'>Adding Role and permission to Users</h3>

- When all the task done then we find Roles and permission for Daily Diary Doctype.
- For this we add new user whom we give role Student and create new role under Doctype named DocPerm Who has permission to read.
- In Daily Diary Doctype we give read permission to Student and all permission to Instructor.
- Then assign Two Role to new user 'Student' + 'Docperm' for student & 'Instructor' + 'Docperm' for Instructor.
- Also we restrict user from Modules.       
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 22-Apr-2024**
<h3 align='center'>Creating web template for display Diary using Bootstrap-4</h3>

- Learn how to use bootstrap in frappe web template.
- By using Bootstrap class create web page which is responsive and give good look to our template.
- Apply different designing like borders, text color classes, actions on link.  
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 23-Apr-2024**
<h3 align='center'>Making new specification and Flow for Noticeboard App</h3>

- Notice will be created by CLERK then it will be in draft state.
- CLERK and HOD can create notice no one else from other department able to create notice for their department.
- Another requirement when notice is created by clerk It will be in Draft state when Hod Submit Notice only then it would be published.
- Naming Series of notice maintained department wise eg: Notice-CSE/2024/00001, Notice-CIVIL/2024/00001.
- If HOD Cancel the notice then Clerk is able to make changes then again send it to HOD.  
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 25-Apr-2024**
<h3 align='center'>Creating doctype in Existing Noticeboard App</h3>

- In First approach we decide to use create doctype and apply workflow on it.
- Where all states are defined like Approve by hod, Draft etc.
- We allote Department to their Respective Hod and Clerk  So that they are able to create notice.
- Every thing Works fine but When we apply some code then workflow states create problem. eg data is saved but changes apply with delay.
- We find workflow also make task for app difficult because its file is not created inside the app that why it portability is difficult.
- So we decide to work without workflow also learn new things from mistakes.   
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 26-Apr-2024**
<h3 align='center'>Naming Series as Department wise</h3>

- Assigning department to Hod & Clerk to one department in User Permission List.
- We use condition like cse = department_name.
- Department_name is fetched from doctype use function self.fieldname.
- After apply such condition we use make_autoname function.
- self.name = make_autoname('NOTICE-'+'CSE'+'/'+'.YYYY.'+'/'+'.#####')
- This function return series 'NOTICE-CSE/2024/00001'
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 27-Apr-2024**
<h3 align='center'>Fetching HOD by using variables in query</h3>

- First we use Simple Frappe query "frappe.db.get_value('User', 'hodcse@gmail.com', 'full_name')".
- But this depends upon the email of hod if email will change in future then we need to change it.
- Also we have to wrote this many times.
- So we use another optimized version of query.
<br>

```py
department = self.department
requiredRole = "Hod" 
		
		self.hod = frappe.db.sql(f""" select full_name 
			from `tabUser` 
			where `email` IN (select user 
			from `tabUser Permission` 
			where `for_value`="{department}" AND `user` IN (select parent 
			from `tabHas Role` 
			where `role`="{requiredRole}" )) """)
```

- By using this query with variable we are able to use this for all departments.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 28-Apr-2024**
<h3 align='center'>New Fee requirent</h3>

- First we Create Fee Categories Like Development Fee, Tutuion Fee, Transportation fee.
- Creating Fee Structure For Different Classes and it depends on siblings fee.
- Like If a Student has one sibling than Tution fees would be 50% discount, If there are two Siblings than Tution Fee would be 25%.
- Transportation Fee depends on various routes eg Bus Fee for Route1 : 500/- than Fee for Route2 : 400/-.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 29-Apr-2024**
<h3 align='center'>Implementing Fee on local server</h3>

- First we import data like Program, student, courses.
- Creating Fee category as per requirement Development Fee, Tution Fee, Transporatation Fee.
- Finding a way how to link siblings of same school using minimal customization.
- We set up students who have siblings but when we select option siblings studying in the same school then we are able to select students from available students but the program is not fetched.
- Along with this We find the received income cost center is also set in schedule. We can find all the income in the Fee cost center.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 30-Apr-2024**
<h3 align='center'>Try to optimize Notice.py Code</h3>

- As we use department for naming series so for this we have to change code when department and its abbrivation changed.
- To Remove this we add department abbrivation field in doctype.
- With following query abbr depends upon the department abbrivation also we haven't make changes in code also code become more simple than previous code. 
<br>

```py
department=self.department
abbr=frappe.db.get_value( 'Department' , department ,'department_abbreviation' )
self.name=make_autoname( 'NOTICE-' + abbr + '/' + '.YYYY.' + '/' + '.#####' )
```
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 2-May-2024**
<h3 align='center'>Creating Roles and permissions</h3>

- Creating Director Role and add permission for Viewing accounts, payroll, Employee details etc.
- Customize Deskview for Director Role.
- Creating Principal Role and add all academic views for Principal.
- Creating Instructor Role and allow all permissions needed to do their tasks.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 3-May-2024**
<h3 align='center'>Learn Different Salary component for Employee Salary</h3>

- Basic Pay of employee as per college pay scale.
- Add 5% Interim Relief in Basic pay.
- Adding Dearness allowance 142% in Basic Pay.
- Medical Allowance,CCA,PF(10%),HRA.
- These all are Earning in salary.
- Then we add Deduction component like PF(20%),Development tax, GI, SML, SMAF.
- By calculating all Earning & Deduction, we get Net Paid Amount. 
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 4-May-2024**
<h3 align='center'>Creating Salaries</h3>

- First we create salary component which are fixed these are declared in Salary Component.
- Next Create Salary Structure in which we group all Salary Component which are earning and deduction components.
- Setting up formula on Basic Pay like calculate IR(5%), ADA(142%) etc.
- After Successfully creating salary structure assigning it to employee where we define the Basic pay of Employee.
- At last in Salary Slip we select employee to whom we assign salary then salary structure automatically fetched and calculate base salary.    
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 5-May-2024**
<h3 align='center'>Creating Presentation with Other Team-mates in Reveal.JS</h3>

- Review all work which is done by us.
- Creating presentation add all Salary Components required.
- Add how Desk is visible for different Roles.
- What is visible to all student.
- Explaing other modules like Accounts, Assets, Payroll, Human Resource, Education Domain.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
Certainly! Let's adapt the entries for your product recommendation project in QuasarJS with a Node.js backend and a SPARQL database.

**Date: 6-May-2024**
<h3 align='center'>Setting up SPARQL Database for Product Recommendation</h3>

- Created a new database consisting of three tables: Products, Users, and Recommendations.
- Imported data into these tables using CSV files via terminal commands.
- Established a connection between the database and the Node.js file.

**Date: 7-May-2024**
<h3 align='center'>Integrating QuasarJS with Flask</h3>

- Chose QuasarJS as the frontend framework to display recommendations.
- Implemented Flask as a backend framework to handle API requests securely. 
- Stored sensitive credentials in a separate configuration file to avoid exposure on version control.
- Initialized a basic API route to serve data to the QuasarJS frontend.

**Date: 9-May-2024**
<h3 align='center'>Displaying Product Details on QuasarJS</h3>

- Created a dedicated folder named "views" within the Quasar app to organize HTML files.
- Developed a function to query and retrieve product names from the Products table.
- Rendered a template in QuasarJS to display the fetched data from the backend.

**Date: 10-May-2024**
<h3 align='center'>Rendering Product Data on the QuasarJS Interface</h3>

- Utilized Jinja templating within QuasarJS to dynamically populate product details.
- Incorporated Bootstrap code for styling the QuasarJS interface and ensuring responsiveness.

**Date: 11-May-2024**
<h3 align='center'>Enhancing Recommendation Logic</h3>

- Modified the recommendation algorithm to accommodate user preferences and product attributes.
- Leveraged JavaScript to calculate and update recommendation scores based on user interactions.

**Date: 12-May-2024**
<h3 align='center'>Implementing Backend Logic for Saving User Interactions</h3>

- Extended the API endpoint in Flask to handle POST requests for saving user interactions.
- Updated the SPARQL database schema to store user feedback and interactions efficiently.

**Date: 13-May-2024**
<h3 align='center'>Refining User Feedback Mechanism</h3>

- Collaborated with the frontend team to design intuitive user feedback mechanisms.
- Implemented logic to capture user ratings, reviews, and preferences for products.

**Date: 14-May-2024**
<h3 align='center'>Optimizing Product Recommendation Engine</h3>

- Fine-tuned the recommendation algorithm to improve accuracy and relevance.
- Conducted performance testing and optimization to ensure efficient retrieval of recommendations.

**Date: 16-May-2024**
<h3 align='center'>Scaling the System for Increased User Traffic</h3>

- Evaluated system architecture for scalability and resilience under high user loads.
- Implemented caching mechanisms and load balancing strategies to handle increased traffic.

**Date: 17-May-2024**
<h3 align='center'>Ensuring Data Security and Compliance</h3>

- Conducted security audits and vulnerability assessments to identify and mitigate potential risks.
- Ensured compliance with data protection regulations and industry standards.

**Date: 18-May-2024**
<h3 align='center'>Monitoring System Performance and Analytics</h3>

- Integrated monitoring tools to track system performance, usage metrics, and user feedback.
- Utilized analytics dashboards to gain insights into user behavior and preferences.

**Date: 19-May-2024**
<h3 align='center'>Continuous Improvement and Maintenance</h3>

- Established processes for ongoing maintenance, bug fixes, and feature enhancements.
- Conducted regular reviews and retrospectives to identify areas for improvement and innovation.
<!----------------------------------------------------------------------------------------------------------------------------->