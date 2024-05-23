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
- Select Install Ubuntu then Click Noraml Installation.
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
- PHP, Perl, and Python are programming languages are used to create web applications.
- Installing lamp on Ubuntu System.
- Verifying by run LAMP on localhost.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 3-Feb-2024**
<h3 align='center'>Run Cgi Script</h3>

<p align="justify">CGI stands for Common Gateway Interface. CGI defines a standard way in which information may be passed to and from the browser and server. Any program or script that can process information according to the CGI specification can, in theory, be used to code a CGI script.</p>

- Create a cgi scirpt.
- Run it on Localhost using Apache Server.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 4-Feb-2024**
<h3 align='center'>Image to video</h3>

- Create a python Script.
- install pip,Image-MagicK on your system.
- goto ---- /etc/ImageMagick-6/policy.xml file. 
- Comment out line "policy domain="path" rights="none" pattern="@*" 
- Run the script by using python3 filename.py.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 5-Feb-2024**
<h3 align='center'>Introduction to frappe</h3>

<p align="justify">Frappe, pronounced fra-pay, is a full stack, batteries-included, web framework written in Python and Javascript with MariaDB as the database. It is the framework which powers ERPNext, is pretty generic and can be used to build database driven apps.</p>

#### Why Frappe?

<p align="justify">The key difference in Frappe compared to other frameworks is that meta-data is also treated as data. This enables you to build front-ends very easily. We believe in a monolithic architecture, so Frappe comes with almost everything you need to build a modern web application. It has a full featured Admin UI called the Desk that handles forms, navigation, lists, menus, permissions, file attachment and much more out of the box.</p>

- Install Frappe-bench and its required tool. For more info [Click here](https://frappeframework.com/docs/v13/user/en/installation).
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 7-Feb-2024**
<h3 align='center'>Creating App and Site & run on local server in Frappe</h3>

- Start Bench in one Terminal.
- In Second Terminal.
- Creating App by using **bench new-app library_management** inside Frappe-bench Directory.
- Creating site by using **bench new-site library.test** inside Frappe-bench Directory.
- Run Site on Localhost by using library.test custom port name.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 8-Feb-2024**
<h3 align='center'>Introduction to Github Pages</h3>

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
<p align="justify">Docker is popular virtualization software that helps its users in developing, deploying, monitoring, and running applications in a Docker Container with all their dependencies (frameworks, libraries, etc.) to run an application in an efficient and bug-free manner.Docker Containers are Light-weight, Applications run in isolation,Occupies less space, Easily portable and highly secure, Short boot-up
time.</p>

- It can run multiple containers on a system.
- It can start multiple containers at a time on the Docker engine.
<br>

**What is Virtual Machine?**
<p align="justify">A Virtual Machine (VM) is a compute resource that uses software instead of a physical computer to run programs and deploy apps. One or more virtual “guest” machines run on a physical “host” machine.  Each virtual machine runs its own operating system and functions separately from the other VMs, even when they are all running on the same host. This means that, for example, a virtual MacOS virtual machine can run on a physical PC.</p>

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
- Installion done with two manner 
- By Adduser in linux
- And create Erpnext app and site in frappe-bench Diretory.
- For installation steps [Click here](https://github.com/D-codE-Hub/ERPNext-installation-Guide/blob/main/README.md). 
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 12-Feb-2024** 
<h3 align='center'>Introduction to Selenium, Budibase, Coding standard for program</h3>

- Selenium is browser automation tool by which you can create a script which automatically done task like fill credential and click for search.
- Budibase is a development platform designed for speed and productivity. 
- With Budibase, developers no-longer experience repetition, long-dev cycles, and frustration. Instead, developers are more productive, happier, and can deliver applications they're proud of in minutes.
- How to write code in Any script so that it can easily read by other programmer who contribute to your project, take variable name which should be relevant with its function.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 14-Feb-2024** 
<h3 align='center'>Try to Solve error redis-server during Installation</h3>

**Error while loading shared libraries: libatomic.so.1: cannot open shared object file: No such file or directory**

- sudo apt purge libatomic1.
- install houncho  if file is missing.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 15-Feb-2024** 
<h3 align='center'>Introduction to Education module in Erpnext</h3>

The Education domain in ERPNext is designed to meet requirements of any organization which imparts knowledge and believe in doing so in an organized fashion. It has already been used at schools, colleges and even in private firms.

It helps you to effectively manage administration and allows you to focus on what is most important for your institute, to educate!
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 17-Feb-2024** 
<h3 align='center'>Introduction to Jinja Templating</h3>

<p align='justify'>Jinja is a fast, expressive, extensible templating engine. Special placeholders in the template allow writing code similar to Python syntax. Then the template is passed data to render the final document.</p>
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 18-Feb-2024** 
<h3 align='center'>Trying to fetch data from database using Jinja Templating</h3>

- Write a Python Script for establish connection with Mariadb.
- Still it gives permission error try to solve it.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 19-Feb-2024** 
<h3 align='center'>Working with server</h3>

- Resetting the password of server.
- Trying to install Erpnext on server.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 21-Feb-2024** 
<h3 align='center'>Mysql Administration, Converting pdf to md file</h3>

- Today I created a new doctype in erpnext with different options
- then learned about the administration concept of database
- Converting pdf file to md and applying changes using markdown.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 22-Feb-2024** 
<h3 align='center'>Add new user in ubuntu</h3>

- Add new user in ubuntu.
- trying to give access of database to other user.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 23-Feb-2024** 
<h3 align='center'>How to use ssh</h3>

- Login to Server, Try to help other member to install ldap on server.
- Apply different permission related queries on database for different user.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 24-Feb-2024** 
<h3 align='center'>Learning about how to import data in erpnext from csv file</h3>

- Try to import data in erpnext app throught csv file.
- Apply pagination in erpnext webpage.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 25-Feb-2024** 
<h3 align='center'>Import Data in Mysql</h3>

- Try to import data in MariaDB throught csv file.
- Learning the concept of permission on Server.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 28-Feb-2024** 
<h3 align='center'>Creating Web page in ErpNext</h3>

- Creating Static Webpage on Erpnext.
- Learning Frappe School Module.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 2-Mar-2024** 
<h3 align='center'>Learn Module from Frappe School</h3>

- Creating new site with new app.
- Creating Doctype and linking doctype with other.
- Learn Jinja Script for frappe doctypes. 
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 3-Mar-2024** 
<h3 align='center'>Learn Meeting App</h3>

- Understand the structure of meeting app.
- Understand the javascript code and python code of meeting app.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 4-Mar-2024** 
<h3 align='center'>Presentation and discussion of meeting app</h3>

- Telling about the importance of doctype in Frappe-Framework.
- Discuss with all team how it works and how we create new custom app.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 5-Mar-2024** 
<h3 align='center'>Creating own Noticeboard app</h3>

- First create App and install it on website.
- Create Doctype according to structure discussed in team.
- Provide it web view.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 7-Mar-2024** 
<h3 align='center'>Customize Noticeboard app</h3>

- Writing code to show correct date format eg. March 7, 2024.
- Writing code to show the name of user who upload the notice.
- Making its view user friendly in form and webpage both.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 8-Mar-2024** 
<h3 align='center'>Learning about built in Note Doctype</h3>

- Today I'm Differentiate between Noticeboard app and inbuilt note app.
- Trying to understand note doctype functionality.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 9-Mar-2024** 
<h3 align='center'>Learning about Workflow</h3>

- Today I'm learning Workflow in ErpNext.
- Understand how to pass control to different manager.
- Trying to implement Purchase order list and trying to approve it from purchase manager and material manager.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 11-Mar-2024** 
<h3 align='center'>Working with Dynamic pages in Frappe</h3>

- First I need to create www directory in any Frappe app.
- Then I need to create two files Python file for fetching data from database.
- Other file is html file in which i use jinja template to show record on webpage.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 12-Mar-2024** 
<h3 align='center'>Trying to add pagination on Dynamic page</h3>

- First try to control send data to python file from html file.
- But this won't work then i create post on discuss Erpnext where i get answer and trying to use javascript.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 14-Mar-2024** 
<h3 align='center'>Learning about Fee Module in Erpnext</h3>

- Here I get details how to create new fees for student.
- Learning Different prerequisites before creating new fees.
- Like Student, Fee Category, Fee Structure etc.
 <br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 15-Mar-2024** 
<h3 align='center'>Creating Fees in Erpnext on server</h3>

- Creating Different Fees Categories available in school like Tution Fee, Hostle Fee etc.
- Searching how to add bus fees based on their route.
- Creating student, Enroll them in a program, Creating courses etc. 
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 16-Mar-2024** 
<h3 align='center'> Creating Fee Structure</h3>
<p align="justify">Creating  new Fees structures. So while creating new fees, fees should be added automatically by selecting Fee Structure. We are trying to add an admission fee in Student form along with this we are exploring where all the records are saved so that we keep track how many fees are paid or pending. We track this record in 'Report Student fee collection' doctype. We are also trying to add a penalty on overdue fees but we find this feature is not currently available in erpnext.</p>
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 17-Mar-2024** 
<h3 align='center'>Solve Problem While deleting records</h3>
<p align="justify">I'm exploring how to delete such payment entries which are linked with GL Entry. For this we need to go to Account Settings and Enable a checkbox Delete Accounting and Stock Ledger Entries on the deletion of Transaction and then all such Cancelled entries deleted normally.</p>

<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 19-Mar-2024** 
<h3 align='center'>Add Frappe app in repository</h3>

- First I go through the git documentation, so that every thing done properly.
- In add on I'm finding a command how to add repositiory from terminal to github.
- After doing task completely I made documentation on github pages so that it help other team-members
- For Documentation [Click here](https://vishal78626.github.io/Add-Frappe-app-in-GitRepo/) 
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 21-Mar-2024** 
<h3 align='center'>Understand the code available in Frappe</h3>
<p align="justify">Understanding the code available in all-products, then we are trying to add items in item lists, then we face problem after few search then we add items in (item lists), then add item in (website item), then setting up e-commerce settings now we successfully use search, prev & next. Now we are trying to apply it in a pagination file.</p>
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 22-Mar-2024** 
<h3 align='center'>Installing new Erpnext on server</h3>

- First we install frappe framework then install erpnext with education domain.
- After this we are collecting students and teachers data from Nankana Sahib Public School.
- Arranging data according to doctype in erpnext.  
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 23-Mar-2024** 
<h3 align='center'>Arrange naming series company wise</h3>
<p align="justify">While new applicant is registered in system by default system generate naming series. We are trying to change it company wise For eg. if we are member of company A, then naming series include A-2024-00001.</p>
For this we follow official erpnext tutorial [More Detail](https://docs.erpnext.com/docs/v13/user/manual/en/customize-erpnext/articles/company-wise-naming-series#:~:text=The%20need%20is%20to%20create,be%20SINV%2DB%2D0001.)
Using this we get error the we take reference from other discuss.erpnext where we use (.abbr.-.YYYY.-) in option of Naming Series. 
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 24-Mar-2024**
<h3 align='center'>Arranging Student data</h3>

- As there are large data of students in school we need to make it correct.
- so we all divide work in team and understanding the concept of filter, concatinate etc. in excel.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 25-Mar-2024** 
<h3 align='center'>Learning Employee Salary module</h3>

- For Employee or Teacher salary I need to lean Payroll module in Erpnext.
- In this I learn Payroll Period, Income Tax Slab, Salary Component and Structure, Generating Salary Recipt.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 26-Mar-2024** 
<h3 align='center'>Implementing Payroll in Erpnext</h3>

- First Create Salary Component where i create New Component type as Earning and create PF as Deduction and add base amount in condition section.
- Create Salary Structure with Earning and Deduction, Selecting account,Payroll Frequency as montly, daily, weekly etc.
- In New Salary Structure Assignment we assign employee to Salary Structure.
- After this we go to Salary slip here i need to create holiday list and assign holiday to company then we successfully generate salary slip.
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
**Date : 6-May-2024**
<h3 align='center'>Working on Mentor-Mentee Task without erpnext</h3>

- Creating new database in which three tables Mentor, Mentee & Relation.
- Import data in these tables using csv files through terminal.
- Make connection of database with python file.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 7-May-2024**
<h3 align='center'>Install and use Flask</h3>

- As we need to show detail on webpage using jinja templating.
- After few searches we decide to use flask as a framework which render jinja template for html file.
- Again Make connection with database, but this time as adviced by teacher. we need to hide credential from public so that we push it on git.
- For hiding credentials we load details from another python file.
- Write basic hello world program and render it using jinja templating.
<br>


<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 9-May-2024**
<h3 align='center'>Showing detail in html file using jinja</h3>

- Creating a templates folder inside flask app where all the html files put together
- Make a funtion in which we put query select Mentor name from mentor table.
- Then render template with data and file name in which template is shown
```py
@app.route('/')
def example():
    cur.execute("SELECT Name FROM Mentor")
    data = cur.fetchall()
    return render_template('index.html', output = data)
```
- cur.execute is used for query and cur.fetchall() fetch all names from mentor table.
- And at the end funtion return render template in which filename, and assign data to output variable.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 10-May-2024**
<h3 align='center'>Showing Data on Webpage with Jinja and Bootstrap code</h3>

- Jinja template code for showing data on webpage. 
- In the below code under block content section we run a loop which fetch data from flask app.
- row[0] is used for show data without braces.
- jinja template code with Bootstrap

```jinja
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@4.0.0/dist/css/bootstrap.min.css" integrity="sha384-Gn5384xqQ1aoWXA+058RXPxPg6fy4IWvTNh0E263XmFcJlSAwiGgFAW/dAiS6JXm" crossorigin="anonymous">

    <title>Hello, world!</title>
  </head>
  <body>
    <div class="container">
    <table class="table">
      <thead class="thead-dark">
        <tr>
          <th scope="col">Mentor Name</th>
          <th scope="col">Mentee Name</th>
        </tr>
      </thead>
      <tbody>
        <tr rowspan="4">
          <td class="border">{{ mentor }}</td>          
          <td class="border">
          {% for row in output1 %}         
            {{ row[0] }}              
            <br>
          {% endfor %}
        </td>
        </tr>
        
        </tbody>
      </table>
    </div>

    <script src="https://code.jquery.com/jquery-3.2.1.slim.min.js" integrity="sha384-KJ3o2DKtIkvYIK3UENzmM7KCkRr/rE9/Qpg6aAZGJwFDMVNA/GpGFF93hXpG5KkN" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/popper.js@1.12.9/dist/umd/popper.min.js" integrity="sha384-ApNbgh9B+Y1QKtv3Rn7W3mgPxhU9K/ScQsAP7hUibX39j7fakFPskvXusvfa0b4Q" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@4.0.0/dist/js/bootstrap.min.js" integrity="sha384-JZR6Spejh4U02d8jOt6vLEHfe/JQGiRRSQQxSfFWpi1MquVdAyjUar5+76PVCmYl" crossorigin="anonymous"></script>
  </body>
</html>
```
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 11-May-2024**
<h3 align='center'>Adding bus Fee in Fee doctype of erpNext</h3>

- By default we have Fee component in which all fee categories are fetched but as per our requirement we need to add bus fee which is different for each student.
- For which First we create two doctype one in which Route detail with Fees is stored and second is child doctype called Bus component which is fetched in Fee doctype.
- Then Apply changes in Bus component like fetch value from Route detail doctype.
- For calculating total bus component and fee component we have to write some code in fee.js file.

```js
calculate_total_amount: function(frm) {
	var grand_total0 = 0, grand_total1 = 0, grand_total = 0;

	for(var i=0;i<frm.doc.components.length;i++) {
		if( frm.doc.components[i].amount >= 0){
			grand_total0 += frm.doc.components[i].amount;
		}
		else{
			grand_total0 = 0;
		}
	}

	if(frm.doc.bus_components.length == 0)
	{
		grand_total1 = 0;
	}
	if(frm.doc.bus_components.length >= 1)
	{
	for(var i=0;i<frm.doc.bus_components.length;i++) {
		if( frm.doc.bus_components[i].amount > 0){
			grand_total1 += frm.doc.bus_components[i].amount;
		}
		else{
			grand_total1 = 0;
		}
	}
	}
	grand_total = grand_total0 + grand_total1;
	console.log(grand_total)
	frm.set_value("grand_total", grand_total);
}

frappe.ui.form.on("Bus Component", {
	amount: function(frm) {
		frm.trigger("calculate_total_amount");
	}
});
```
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 12-May-2024**
<h3 align='center'>Make changes for in fee files to save data at backend</h3>

- First write code in api.py file create whitelist() where we use condition if bus component available.
- Then use it in Javascript file as function where we call api.py and sending data field data to function.
- Now in fee.py we calculate the bus component in loop and send grand total in database throught which we succesfully generate receipt with correct calculations.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 13-May-2024**
<h3 align='center'>Understand the Salary Structure of different employees</h3>

- We are going to Accounts Department for understanding Salary structure of different employees.
- Understand their requirement related to salary like for different employee, there should be different grade pay.
- So they want they have customize option to add grade pay or not.
- They want also seprate record file for provident fund record of employees, provident fund loan record file.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 14-May-2024**
<h3 align='center'>Learning Salary Component for New Requirement</h3>

- First when we change our company from NSPS to GNDEC.
- Then all the Salary Components of employee are visisble in Salary Components but are not shown in Salary structure.
- After that we are finding some other solution so that we can use same structure in two companies. 
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 16-May-2024**
<h3 align='center'>Creating Salary Component</h3>

- According to new requirement different category employees have different components.
- Now same salary component can have different value for two employees like SML for accounts employee and teaching employee are different.
- We are creating all Salary Components without any value so that we can modifying it later in Salary Structure.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 17-May-2024**
<h3 align='center'>Creating Salary Structure</h3>

- After Creating all Salary components which are combined for all the employees.
- Now we are creating Salary Structure which is the combination of Salary Components in which we list all Earning and deduction components.
- In this we set formula that if basic pay is assigned to employee during the assignment of Salary Structure and Grade pay is added to employee when generating Salary Slip only then all the Earning and deduction components are calculated.
- The calculation is done when we save the salary slip in draft state after submit we can't modify it but in draft state we can made any changes at any time like adding or deleting components.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 18-May-2024**
<h3 align='center'>Display General ledger entry for Fee Record</h3>

- Goto Accounting Module then goto General Ledger section.
- Select your Company, Select from date, to date for which you want to show Entries.
- Select Group by Account, Group by Party, Group by Voucher view.
- Now you are able to view all the record here you have all debit, credit and balance record.  
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 19-May-2024**
<h3 align='center'>Collecting Fees in one Fee Cost Center</h3>

- For creating new Fee collection head Create new Account.
- Add account name, Select Company name, Currency type.
- Select Balance type (Debit or Credit), Select Parent account type (Income account or Expenses account).
- After Creating head verify it in Company Cost center, while creating new Fee slip under Accounting Section select income account in which you want to add new fees.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 21-May-2024**
<h3 align='center'>Displaying Fees different head-wise like tution fee, Development fee</h3>

- Goto Fee list under Education domain.
- Under list view option select report view, Select Add group option here select Fee Category under Fee Component
- Then Add sum Filter and in third field Select Amount or grand total or outstanding.
- Now you are able to see all fee collected head wise like Tution Fee, Development Fee, Bus Fee.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 23-May-2024**
<h3 align='center'>Generating School Leaving Certificate</h3>

For creating new school leaving certificate format goto print format. For Adding new print format select student doctype for which you want to create school leaving certificate, Select education module select format as standard format or not we use 'NO' option because this format is only used when we want to generate school leaving certificate. Use custom css for designing logo of company for fetching student name we use doc.first_name. For fetching class name we use frappe function, frappe.db.get_value('Program Enrollment', doc.student, 'program'). 
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 24-May-2024**
<h3 align='center'>Sending Messages to specific Students using ERPNext</h3>

- Creating New Email Group Add Subscribers to whom we want to send emails.
- We can them in a bluk by writing their emails.
- After adding subscriber Create New newsletter in which we have to add email group which is created.
- Then add Subject and Message also we have option to test this message by sending to only one specific user.
- Save the newsletter we have another option schedule sending mail automatically.  
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 25-May-2024**
<h3 align='center'>Creating Collapse view without using ErpNext Desk using Bootstrap</h3>

- First we create collapse multiple tab effect with bootstrap and html.
- In which we use bootstrap classes with html tags.
- Then our next task is to put in erpnext directory and run it with jinja templating.
- For this we remove all html starting tags and bootstrap cdn links because frappe also uses Bootstrap-4 classes.
- Replace Html starting tags with jinja starting template and trying to fetch data from database.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 26-May-2024**
<h3 align='center'>Automation of Fee Creation of the Students</h3>

Once we created the fee of teh student for a single month now we have a problem is that we have to repeat the task again for every month so we need to automate this process in order to provide the clean and efficient approach.So we automate this process with auto-repeat tool and makes evry student fee on repeat once it created. It will automatically created after every month and we set the due date 15 days ahed of the date of creation of the fee so the status of the fee will be changes to overdue after due date.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 27-May-2024**
<h3 align='center'>Bank account which holds all the records of collection of fees</h3>
For creating new Fee collection head Create a new Account. Add account name, Select Company name, Currency type. Select Balance type (Debit or Credit), Select Parent account type (Income account or Expenses account). After Creating head verify it in Company Cost center, while creating new Fee slip under Accounting Section select income account in which you want to add new fees.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 28-May-2024**
<h3 align='center'>Enable Disable Students on the basis of their Fee Status</h3>

Requirement is that we need  to remove the access from those students whose Fee satatus is overdue For this purpose First of all we fetched all the students from the fee list whose status is unpaid.

```py
@frappe.whitelist()
def get_over_due():
    due = frappe.db.sql(f""" SELECT name,student,student_name,academic_year,due_date,outstanding_amount  FROM `tabFees` where due_date <= '{today()}' and outstanding_amount > 0 """,as_dict = True)
    return due

@frappe.whitelist()
def get_paid():
    paid = frappe.db.sql(f""" SELECT name,student,student_name,academic_year,due_date,outstanding_amount  FROM `tabFees` where  outstanding_amount = 0 """,as_dict = True)
    return paid
```

and then use this fetched data to make the students disable the access from the LMS systm.
```js
frappe.listview_settings["Student"] = {
  add_fields: ["title", "name", "gender"],
  // set default filters

  before_render(doc) {
    console.log("y");

    // triggers before every render of list records
  },
  get_indicator(doc, frm) {

    if (doc.enabled == 1) {
      frappe.call({
        method: "ERPGuru.education.api.get_over_due",
        callback: function (r) {
          if (r) {
            $.each(r.message, function (i, d) {
              if ((i, d.student === doc.name)) {
                frappe.call({
                  method: "frappe.client.set_value",
                  args: {
                    doctype: "Student",
                    name: doc.name,
                    fieldname: "enabled",
                    value: 0,
                  },
                  freeze: true,
                  callback: function (r) {
                    frappe.msgprint(
                      __(
                        `Student ${doc.title} has been Disable from Access because of overdue fee`
                      )
                    },
        
```

<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 30-May-2024**
<h3 align='center'>Dashboard for ERPGURU</h3>

- Now we have to create a new dashboard page according to the rquirement specified by Mentor.
- There should be links of Student, Program, Fee, Attendance etc. After clicking, it would ask for login.
- So we explored about this and create a new webpage. (Go to Website > Webpage then create new webpage)
- Enter Title, Route etc. Select HTML in Content Type.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 31-May-2024**
<h3 align='center'>Exploring OAuth 2 </h3>

OAuth 2.0, which stands for “Open Authorization”, is a standard designed to allow a website or application to access resources hosted by other web apps on behalf of a user. OAuth 2.0 provides consented access and restricts actions of what the client app can perform on resources on behalf of the user, without ever sharing the user's credentials. Although the web is the main platform for OAuth 2, the specification also describes how to handle this kind of delegated access to other client types (browser-based applications, server-side web applications, native/mobile apps, connected devices, etc.)
<br>