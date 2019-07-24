# gradebook.py
A Python-based gradebook where you can add students, teachers and manage various aspects of students.

I am currently learning Python, so this project is a way for me to expand on the language.

Down below goes into how I plan on setting up the project. This is likely to change as I learn Python more and want to implement/change various features of the application.

TO-DO | Database
I will need to store all data somewhere. I'm not sure what storage method I will use yet, but the to-do list down below is pretty ambiguous across storage methods.
- [ ] Implement a database/storage method
- [ ] Create CRUD methods for data storage

TO-DO | API
'This is a bit more in the future, but I could create a RESTful API with authentication. This way students and teachers alike can access various data from the database regarding a specific student, course or assignment.
- [ ] Implement a REST API
- [ ] Implement username and password for login
- [ ] Secure routes with proper authentication and limit what type of requests can be made to different routes

TO-DO | Classes
- [ ] Add User class
- [ ] Add Student class
- [ ] Add Teacher class
- [ ] Add Course class
- [ ] Add Assignment class

TO-DO | User Class (parent)
- [ ] Add properties
	- [ ] first_name
	- [ ] last_name
	- [ ] dob
	- [ ] id (student starts with `s_` and teacher starts with `t_`)
	- [ ] courses
- [ ] Add methods:
	- [ ] set_first_name
	- [ ] set_last_name
	- [ ] set_dob
	- [ ] set_id
	- [ ] add_course
	- [ ] remove_course

TO-DO | Student Class (inherits `User`)
- [ ] Add properties
	- [ ] assignments
- [ ] Add methods:
	- [ ] add_assignment
	- [ ] remove_assignment

TO-DO | Teacher Class (inherits `User`)
- [ ] Add properties:
	- [ ] certifications
- [ ] Add methods:
	- [ ] add_certification
	- [ ] remove_certification