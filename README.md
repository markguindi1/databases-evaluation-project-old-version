# databases_evaluation_project_old

This project is an older version of a class evaluation system, which was an academic project for a Databases course.

This project was built using the Python programming language (version 3), and the Django Web Framework (version 2). The database backend used was MySQL. The frontend was built using plain HTML. 

This system allows both students and professors to log in to access the system. For all of the courses they are enrolled in, students can view already-closed evaluations on their homepage, as well as complete or edit evaluations that are still currently open. 

Professors can add evaluation sessions for a course, as well as see the data for each evaluation session. Student evaluations are anonymous, so the Professor cannot see who submitted the evaluations. 

The ability for a Professor to create a course and add students to the course, has not been implemented, as the project requirements have changed during project development, which resulted in the project being rebuilt from scratch (hence the "old" at the end of this project name). For testing purposes, courses and students were managed using the built-in Django shell, or the built-in Django admin panel.

I am aware that the way user authentication is done in this project lacks basic security concerns (storing plaintext passwords, checking raw user input, etc.), but the focus of this project was not as concerned with security as much as with learning the basics of web frameworks. In my future projects, I plan on taking the basic security of my applications seriously, and using basic security features that come with the framework used. 
