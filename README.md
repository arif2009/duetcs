### DUET Computer Society Management Application
---
It manages information and different activities of society member’s.

#### Development Tools & Technology :
---
* [CodeIgniter 2.0.3 Framework](https://www.codeigniter.com/)
* [MySQL 5 +](https://www.mysql.com/)
* [CSS(960 Framework)](http://960.gs/)
* [JQuery](https://jquery.com/)
* [JqueryUI](https://jqueryui.com/)

#### Installation
---
Create a database named **duetcs** and import duetcsor_cs.sql into database which in(beyond_the_project directory).

In this project index.php file was removed, 
so if wampServer
needs mod_rewrite enabled.
Left-Click the system tray icon -> Apache -> Apache Modules -> rewrite_module

if XAMPP no need to change.

#### Database table and their relationship :
---
![alt text](https://i.imgur.com/aGhugq0.png "Database design")


#### Some screenshots to understand this application
---
**Home page:**
![alt text](https://i.imgur.com/99Bd8GA.png "Landing page")


**Registration page:**
![alt text](https://i.imgur.com/qsv2Gl2.png "Registration page")


**Update user information page:**
![alt text](https://i.imgur.com/43DpXk8.png "Update")


**Member management page:**
![alt text](https://i.imgur.com/knxKslf.png "Member selection")

Using this page, admin can assign different types of responsibility to the member.


**Old member management:**
![alt text](https://i.imgur.com/SKjkM1I.png "x-student")

Using this panel admin can easily assign as batch as an old student.


**View all member according to their batch/group:**
![alt text](https://i.imgur.com/sNuRbab.png "previous student group")


**Current executive body of the organization:**
![alt text](https://i.imgur.com/YIsYZqL.png "Current executive body")


**Photo gallery:**

![alt text](https://i.imgur.com/Z3FwoND.png "Photo gallery of different activities")


#### Developers Guide :
---
- **Admin panel**
    - Add / Remove Admin: It will show all the students of executive body who have *President, GeneralSecretary, Finance  and SectionChief* role/responsibility.
    - Manage X-Student: If admin move the last batch of **member** table as x-student, then all the student of that batch in member table will set Year=no and Semister=no.
    - Member Management: Here we can Add/remove member to different department. In that context we can add only one *GeneralSecretary, FinanceDirector, SectionChief*.
    - Requested Student: In the member table the user who has level=0 they are shown as requested student.
- **About Computer Society**
    - Show all member: Show all members from all groups.
    - Executive Body: Show all members from **executive_body** table.
    - X-student body member: Show the user whose year=no and Semester=no.

---

#### License
This application is released under the [GPL-3.0](https://github.com/arif2009/DuetCs/blob/master/LICENSE) License.

Copyright (c) 2018 [Arifur Rahman.](https://arif2009.github.io/)
