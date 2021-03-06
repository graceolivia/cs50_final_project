# cs50_final_project
For my CS50 Web Track Final Project, I'm attempting to create a very simplified Ravelry-inspired clone. I'll use Flask and SQL, as we learned in our Finance app.

<h3>Functionality</h3>

You can register or login to a soothing dark-mode interface with some particles.js for spice.

![Login Screen](https://github.com/graceolivia/cs50_final_project/blob/master/preview%20gifs/loginknittery.gif?raw=true)

You  can browse other profiles, see what other users have been knitting, and add friends.

![Add friend](https://github.com/graceolivia/cs50_final_project/blob/master/preview%20gifs/addfriend.gif?raw=true)

Update your Profile with personal info or new projects.

![Profile](https://github.com/graceolivia/cs50_final_project/blob/master/preview%20gifs/updateprofile.gif?raw=true)


<h3>Plan</h3>

The Ravelry clone should allow users to register, login, logout, log projects and yarn in their stash, and view their profile. They should also be able to link projects to patterns and yarn to projects. Different users should have pages to show their profiles, which will also display their friends

<h5>References/Resources Used</h5>

<a href="https://www.ravelry.com/api">Ravelry API</a> has a lot of cool information about the kinds of databases that the information is stored in. Obviously, I'm not able to take on anything this complex.
<br>
<a href="https://pythonise.com/series/learning-flask/flask-session-object">This tutorial on Flask Sessions</a> was very helpful.
<br>
<a href="https://cs50.harvard.edu/x/2020/">And of course, Harvard CS50.</a>

<h5>To-Do<h5>:

- [x] Create Pages and Databases for Projects, Yarn, and Patterns
- [x] Enable Login, Register, and Logout
- [x] hash passwords
- [x] Create Profile Pages that show User info and their Projects
- [x] Figure out how to create automatic individual user pages
- [x] Make Tag Databases to hold Friendships
- [x] Make search function to find users, projects, patterns, yarn
- [ ] Make it look cool
- [ ] redo layout without bootstrap - use grid and flexbox
- [ ] make sidebar
