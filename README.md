# LogBook
#### Video Demo:  <https://youtu.be/fsAZ_-YTxFI>
#### Description: I developed this logbook based on my professional experience in a large company that had more than 2,000 employees.
#### In companies with a large number of employees, one of the biggest difficulties is communicating what and how each activity should be carried out. Therefore, the objective of this logbook is to facilitate the management of activities carried out by employees from different sectors within the company. Here the manager and employees can register on the application where the manager will have the authorization to add tasks and set a deadline for their completion and both manager and employee will be able to complete them, being reminded daily if the task is on time or late. The program also records which employee was responsible for completing the tasks, keeping the manager informed about the productivity of his staff.

### Templates Folder

#### apology.html: Inspired by Finance, apology.html returns to application users the possible errors highlighted when using the program.

#### approval_result.html: Just a template that directs the person responsible for the server and informs them of their decision to approve or not the registration of a new user as an administrator.

#### description.html: Shows the most specific description of the activities to be carried out, such as what and how it should be done.

#### history.html: Shows the history of activities already carried out, whether they were carried out on time or not and also who was responsible for carrying them out.

#### index.html: The homepage displays tasks in progress, that is: tasks that have not yet been completed and can be followed by everyone, so it is easy to know what needs to be done.

#### layout.html: Layout supported by Bootstrap and used for all other templates.

#### leader.html: Page restricted to administrators. It is possible to add tasks and their respective deadlines, in addition to informing in the description what and how should be done in more detail.

#### login.html and register.html: Templates for user registration and login. When registering, you will have the option to request registration as an administrator by sending an email to the person responsible for the server requesting your release so you can add tasks.


### Static folder: Contains the style.css file that takes care of the application's style and also the books icon used in the layout header.


### database.db: database containing the 3 tables used to store the data provided by the user and which guarantee the operation of the application. It contains information such as the users' ID, their username, their password (obviously encrypted), the description of the tasks, their title, the deadlines required by the administrator, etc.


### app.py: file where our code was written and which guarantees the dynamism and functioning of the page through its functions that allow registration, login, storage of information, sending emails, links, etc. It was described in Python with the help of the Flask framework and the import of other libraries.
