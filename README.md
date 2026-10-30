# Ex01 Portfolio
## Date:30-10-2026

## AIM
To create a Portfolio using HTML and CSS.

## ALGORITHM
### STEP 1
Create an HTML file (index.html)

### STEP 2
Create a CSS file (style.css)

### STEP 3
Include a navigation bar with links to different sections.

### STEP 4
Add structured sections for introduction, about, projects, and contact details.

### STEP 5
Define global styles for fonts, colors, and layout.

### STEP 6
Style the header, navigation bar, and sections.

### STEP 7
Use Flexbox or CSS Grid for layout design.

### STEP 8
Add hover effects and transitions for interactivity.

### STEP 9
Add Images and Media.

### STEP 10
Use optimized images for a professional look.

### STEP 11
Open the HTML file in a browser to check layout and functionality.

### STEP 12
Fix styling issues and refine content placement.

### STEP 13
Deploy the Portfolio.

### STEP 14
Upload to GitHub Pages for free hosting.

## PROGRAM
index.html
```

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Advanced Portfolio</title>
</head>

<body>

    <header>
        <center>
            <h1>WELCOME TO MY PORTFOLIO</h1>
            <h2>Vaideeshwaran</h2>
            <p>Student | Programmer | Web Developer</p>
            <hr>

            <nav>
                <a href="#home">Home</a> |
                <a href="#about">About</a> |
                <a href="#skills">Skills</a> |
                <a href="#education">Education</a> |
                <a href="#projects">Projects</a> |
                <a href="#contact">Contact</a>
            </nav>
        </center>
        <hr>
    </header>

    <main>

        <section id="home">
            <center>
                <h2>HOME</h2>
                <h1>Hello! I'm Vaideeshwaran</h1>
                <h3>Welcome to My Personal Website</h3>
                <p>
                    I am passionate about technology, programming,
                    innovation and creating digital experiences.
                </p>
                <img src="photo.jpeg" alt="My Profile Photo"
                     width="180" height="180">
                <br><br>
                <a href="#projects">Explore My Projects</a> |
                <a href="#contact">Hire Me</a>
            </center>
        </section>

        <hr>

        <section id="about">
            <h2>ABOUT ME</h2>
            <p>
                Hello! I am Vaideeshwaran, a college student
                interested in computer science and technology.
                I enjoy learning programming languages,
                developing websites and exploring new technologies.
            </p>

            <h3>Personal Interests</h3>
            <ul>
                <li>Web Development</li>
                <li>Programming</li>
                <li>Gaming</li>
                <li>Travelling</li>
                <li>Creative Thinking</li>
            </ul>
        </section>

        <hr>

        <section id="skills">
            <h2>MY TECHNICAL SKILLS</h2>

            <table border="1" cellpadding="10">
                <tr>
                    <th>Skill</th>
                    <th>Level</th>
                </tr>
                <tr>
                    <td>HTML</td>
                    <td>Advanced</td>
                </tr>
                <tr>
                    <td>CSS</td>
                    <td>Intermediate</td>
                </tr>
                <tr>
                    <td>JavaScript</td>
                    <td>Beginner</td>
                </tr>
                <tr>
                    <td>Python</td>
                    <td>Intermediate</td>
                </tr>
                <tr>
                    <td>C Programming</td>
                    <td>Beginner</td>
                </tr>
            </table>
        </section>

        <hr>

        <section id="education">
            <h2>EDUCATION</h2>

            <table border="1" cellpadding="10">
                <tr>
                    <th>Qualification</th>
                    <th>Institution</th>
                    <th>Status</th>
                </tr>
                <tr>
                    <td>Higher Secondary</td>
                    <td>School</td>
                    <td>Completed</td>
                </tr>
                <tr>
                    <td>College Degree</td>
                    <td>College</td>
                    <td>Currently Studying</td>
                </tr>
            </table>
        </section>

        <hr>

        <section id="projects">
            <h2>MY PROJECTS</h2>

            <article>
                <h3>1. Personal Portfolio Website</h3>
                <p>A personal portfolio developed using HTML.</p>
                <a href="#home">View Project</a>
            </article>

            <article>
                <h3>2. Smart Calculator</h3>
                <p>A calculator application for mathematical operations.</p>
            </article>

            <article>
                <h3>3. Student Management System</h3>
                <p>A project for maintaining student information.</p>
            </article>

            <article>
                <h3>4. Bike Taxi Booking System</h3>
                <p>A website concept for booking bike taxi services.</p>
            </article>
        </section>

        <hr>

        <section id="contact">
            <h2>CONTACT ME</h2>

            <form>
                <label>Name:</label><br>
                <input type="text" placeholder="Enter your name" required>
                <br><br>

                <label>Email:</label><br>
                <input type="email" placeholder="Enter your email" required>
                <br><br>

                <label>Subject:</label><br>
                <input type="text" placeholder="Enter subject">
                <br><br>

                <label>Message:</label><br>
                <textarea rows="5" cols="35"
                placeholder="Enter your message"></textarea>
                <br><br>

                <button type="submit">Send Message</button>
                <button type="reset">Clear</button>
            </form>
        </section>

        <hr>

        <section>
            <h2>SOCIAL MEDIA</h2>
            <p>
                <a href="https://github.com/">GitHub</a> |
                <a href="https://www.linkedin.com/">LinkedIn</a> |
                <a href="https://www.instagram.com/">Instagram</a>
            </p>
        </section>

    </main>

    <hr>

    <footer>
        <center>
            <h3>Thank You for Visiting My Portfolio!</h3>
            <p>© 2026 Vaideeshwaran. All Rights Reserved.</p>
            <a href="#home">Back to Top ↑</a>
        </center>
    </footer>

</body>
</html>
```




## OUTPUT
<img width="1862" height="791" alt="Screenshot 2026-10-30 101515" src="https://github.com/user-attachments/assets/c367387e-7575-40cc-9907-7128879f356c" />

<img width="1887" height="711" alt="Screenshot 2026-10-30 101522" src="https://github.com/user-attachments/assets/97a08a46-36fe-4e7f-8f34-963add478e05" />

<img width="1897" height="753" alt="Screenshot 2026-10-30 101529" src="https://github.com/user-attachments/assets/8a2bdde0-7443-4905-968a-a3cbbf7ebe10" />

<img width="1890" height="765" alt="Screenshot 2026-10-30 101539" src="https://github.com/user-attachments/assets/f09b2929-fe16-48af-b831-1125cfee1aa7" />

## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
