# Personal-portfolio-
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Name - Web Developer Intern Portfolio</title>
    <link rel="stylesheet" href="style.css">
</head>

<body>
    <header>
        <div class="container">
            <h1>Muqaddas Imtiaz</h1>
            <p class="subtitle">Web Developer Intern</p>
            <nav>
                <ul>
                    <li><a href="#about">About</a></li>
                    <li><a href="#projects">Projects</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <main>
        <section id="about" class="fade-in">
            <div class="container">
                <h2>About Me</h2>
                <div class="about-content">
                    <img src="pic.jpg" alt="Profile Image" class="profile-img">
                    <p>
                        👩‍💻 My name is Muqaddas Imtiaz, a passionate and hardworking 💪🎓 Data Science student from
                        Nawabshah, Pakistan 🇵🇰. I’m currently pursuing my Bachelor’s degree and have built a strong
                        foundation in web development, basic programming, video editing, and data science tools. I’ve
                        successfully completed internships in both Web Development (with CoreTech Innovations) and Video
                        Editing (with Digital Empowerment Pakistan), where I worked on real tasks and submitted complete
                        projects using platforms like GitHub and Google Drive.

                        💻 My technical skills include HTML, CSS, JavaScript for front-end design, and beginner-level
                        Python, Java, and C for programming. I also have experience working with MySQL databases and
                        tools like VS Code, Jupyter Notebook, Google Colab, and XAMPP. For data analysis, I’ve practiced
                        with Pandas, NumPy, and Matplotlib. In video editing, I use CapCut and InShot to create
                        educational and creative content, having completed weekly internship tasks. I’m also confident
                        in MS Word, PowerPoint, and Excel, and I type fluently in both Urdu and English.

                        🌟 I’ve worked on several mini-projects including a portfolio website, an e-commerce bakery
                        website, a Python logic game (Red Blue Nim), a login/registration system, and a food detection
                        AI project (in progress). I’m a self-motivated learner who loves using platforms like ChatGPT,
                        Gemini, YouTube, and Google to explore and grow my skills every day.

                        🧕 As a proud hijabi girl, I prefer to work behind the screen and protect my identity while
                        still proving my capability through my work. I don’t post pictures or personal content online,
                        but I let my skills speak for me. I believe in consistency, creativity, and helping others. My
                        dream is to become a confident Frontend Developer and contribute to the world of Artificial
                        Intelligence and Data Science, while inspiring other girls to join tech with values, skill, and
                        self-respect. 🤍

                    </p>
                </div>
            </div>
        </section>

        <section id="projects" class="fade-in">
            <div class="container">
                <h2>My Projects</h2>
                <div class="project-grid">
                    <div class="project-card">
                        <h3>AynaAIchatbot</h3>
                        <p>A responsive website built with HTML and CSS showcasing various design principles.</p>
                        <a href="https://github.com/Muqadas-g/AynaAIchatbot" class="btn" target="_blank">View
                            Project</a>
                    </div>
                    <div class="project-card">
                        <h3>Restaurant_menu</h3>
                        <p>An interactive web application developed using JavaScript for dynamic content display.</p>
                        <a href="https://github.com/Muqadas-g/Restaurant_menu" class="btn" target="_blank">View
                            Project</a>
                    </div>
                    <div class="project-card">
                        <h3>ApnaStore-</h3>
                        <p>A simple calculator application demonstrating basic DOM manipulation and event handling.</p>
                        <a href="https://github.com/Muqadas-g/ApnaStore-" class="btn" target="_blank">View Project</a>
                    </div>
                </div>
            </div>
        </section>

        <section id="contact" class="fade-in">
            <div class="container">
                <h2>Contact Me</h2>
                <form id="contactForm">
                    <div class="form-group">
                        <label for="name">Name:</label>
                        <input type="text" id="name" name="name" required>
                    </div>
                    <div class="form-group">
                        <label for="email">Email:</label>
                        <input type="email" id="email" name="email" required>
                    </div>
                    <div class="form-group">
                        <label for="message">Message:</label>
                        <textarea id="message" name="message" rows="5" required></textarea>
                    </div>
                    <button type="submit" class="btn">Send Message</button>
                </form>
            </div>
            </div>
        </section>
    </main>

    <footer>
        <div class="container">
            <p>&copy; 2025 High Tech Software House. All rights reserved.</p>
        </div>
    </footer>

    <button id="scrollToTopBtn" title="Go to top">Top</button>

    <script src="script.js"></script>
</body>

</html>
/* Basic Reset & Base Styles */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

:root {
    /* Professional Color Palette */
    --primary-color: #007bff;
    /* Bright Blue */
    --secondary-color: #6c757d;
    /* Muted Gray */
    --accent-color: #28a745;
    /* Green (for success/buttons) */
    --dark-bg: #212529;
    /* Dark background for header/footer */
    --light-bg: #f8f9fa;
    /* Light background for sections */
    --text-color: #343a40;
    /* Dark text */
    --light-text-color: #e9ecef;
    /* Light text on dark backgrounds */
    --border-color: #dee2e6;
    /* Light border */
    --card-shadow: rgba(0, 0, 0, 0.08);
    --hover-shadow: rgba(0, 0, 0, 0.15);
}

body {
    font-family: 'Open Sans', sans-serif;
    /* Modern body font */
    line-height: 1.6;
    color: var(--text-color);
    background-color: var(--light-bg);
    overflow-x: hidden;
    /* Prevent horizontal scroll from animations */
}

.container {
    max-width: 1100px;
    /* Slightly wider container */
    margin: 0 auto;
    padding: 20px;
}

a {
    text-decoration: none;
    color: var(--primary-color);
    transition: color 0.3s ease;
}

a:hover {
    color: var(--dark-bg);
}

/* Header */
header {
    background-color: var(--dark-bg);
    color: var(--light-text-color);
    padding: 25px 0;
    text-align: center;
    position: sticky;
    top: 0;
    z-index: 1000;
    box-shadow: 0 4px 10px var(--card-shadow);
}

header h1 {
    font-family: 'Raleway', sans-serif;
    /* Distinct heading font */
    margin-bottom: 8px;
    font-size: 2.8em;
}

header .subtitle {
    font-size: 1.2em;
    color: var(--secondary-color);
    margin-bottom: 20px;
    font-weight: 300;
}

header nav ul {
    list-style: none;
    padding: 0;
}

header nav ul li {
    display: inline-block;
    margin: 0 20px;
}

header nav ul li a {
    color: var(--light-text-color);
    padding: 10px 18px;
    border-radius: 5px;
    transition: background-color 0.3s ease, color 0.3s ease, transform 0.2s ease;
    font-weight: 400;
    font-size: 1.05em;
}

header nav ul li a:hover {
    background-color: var(--primary-color);
    color: #fff;
    transform: translateY(-2px);
    /* Subtle lift on hover */
}

/* Sections */
section {
    padding: 80px 0;
    /* More vertical padding */
    margin-bottom: 0;
    /* Remove margin, use padding for spacing */
    background-color: #fff;
    box-shadow: 0 2px 8px var(--card-shadow);
    /* Animation base */
    opacity: 0;
    transform: translateY(30px);
    transition: opacity 0.8s ease-out, transform 0.8s ease-out;
}

section.active {
    opacity: 1;
    transform: translateY(0);
}

section:nth-child(even) {
    background-color: var(--light-bg);
}

h2 {
    font-family: 'Raleway', sans-serif;
    text-align: center;
    margin-bottom: 50px;
    /* More space below heading */
    color: var(--dark-bg);
    font-size: 2.8em;
    position: relative;
    padding-bottom: 10px;
}

h2::after {
    content: '';
    position: absolute;
    left: 50%;
    bottom: 0;
    transform: translateX(-50%);
    width: 60px;
    height: 4px;
    background-color: var(--primary-color);
    border-radius: 2px;
}

/* About Section */
.about-content {
    display: flex;
    flex-direction: column;
    align-items: center;
    text-align: center;
    max-width: 800px;
    margin: 0 auto;
}

.profile-img {
    border-radius: 50%;
    width: 180px;
    height: 180px;
    object-fit: cover;
    margin-bottom: 30px;
    border: 6px solid var(--primary-color);
    box-shadow: 0 0 15px rgba(0, 0, 0, 0.15);
    transition: transform 0.4s ease;
}

.profile-img:hover {
    transform: scale(1.05);
    /* Zoom effect */
}

.about-content p {
    font-size: 1.1em;
    color: var(--text-color);
    line-height: 1.8;
}


/* Projects Section */
.project-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 35px;
    /* Increased gap */
}

.project-card {
    background-color: #fff;
    border: 1px solid var(--border-color);
    border-radius: 10px;
    /* More rounded corners */
    padding: 30px;
    text-align: center;
    box-shadow: 0 6px 15px var(--card-shadow);
    transition: transform 0.4s cubic-bezier(0.25, 0.8, 0.25, 1), box-shadow 0.4s cubic-bezier(0.25, 0.8, 0.25, 1);
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    align-items: center;
}

.project-card:hover {
    transform: translateY(-10px);
    /* More pronounced lift */
    box-shadow: 0 12px 25px var(--hover-shadow);
    /* Stronger shadow */
}

.project-card h3 {
    font-family: 'Raleway', sans-serif;
    margin-bottom: 12px;
    color: var(--primary-color);
    font-size: 1.6em;
}

.project-card p {
    margin-bottom: 25px;
    font-size: 1em;
    color: var(--secondary-color);
    flex-grow: 1;
    /* Allows description to take up available space */
}

.btn {
    display: inline-block;
    background-color: var(--accent-color);
    /* Green button */
    color: #fff;
    padding: 12px 25px;
    border-radius: 5px;
    transition: background-color 0.3s ease, transform 0.2s ease, box-shadow 0.3s ease;
    border: none;
    cursor: pointer;
    font-weight: 600;
    letter-spacing: 0.5px;
    text-transform: uppercase;
}

.btn:hover {
    background-color: #218838;
    /* Darker green */
    transform: translateY(-2px);
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
}

/* Contact Section */
#contactForm {
    max-width: 700px;
    /* Wider form */
    margin: 0 auto;
    background-color: #fff;
    padding: 40px;
    border-radius: 10px;
    box-shadow: 0 6px 15px var(--card-shadow);
    border: 1px solid var(--border-color);
}

.form-group {
    margin-bottom: 25px;
}

.form-group label {
    display: block;
    margin-bottom: 10px;
    font-weight: 600;
    color: var(--dark-bg);
    font-size: 1.05em;
}

.form-group input[type="text"],
.form-group input[type="email"],
.form-group textarea {
    width: 100%;
    padding: 14px;
    border: 1px solid var(--border-color);
    border-radius: 6px;
    font-size: 1em;
    background-color: var(--light-bg);
    transition: border-color 0.3s ease, box-shadow 0.3s ease;
}

.form-group input:focus,
.form-group textarea:focus {
    outline: none;
    border-color: var(--primary-color);
    box-shadow: 0 0 0 3px rgba(0, 123, 255, 0.25);
    background-color: #fff;
}

textarea {
    resize: vertical;
    min-height: 120px;
}

/* Footer */
footer {
    background-color: var(--dark-bg);
    color: var(--secondary-color);
    text-align: center;
    padding: 30px 0;
    font-size: 0.9em;
    border-top: 1px solid rgba(255, 255, 255, 0.1);
}

footer p {
    margin: 0;
}


/* Scroll to Top Button */
#scrollToTopBtn {
    display: none;
    /* Hidden by default */
    position: fixed;
    /* Fixed position */
    bottom: 30px;
    /* Place at the bottom */
    right: 30px;
    /* Place at the right */
    z-index: 999;
    /* Make sure it does not overlap with sticky header */
    border: none;
    /* Remove borders */
    outline: none;
    /* Remove outline */
    background-color: var(--primary-color);
    /* Set a background color */
    color: white;
    /* Text color */
    cursor: pointer;
    /* Add a mouse pointer on hover */
    padding: 15px;
    /* Some padding */
    border-radius: 50%;
    /* Rounded corners */
    font-size: 20px;
    /* Increase font size */
    box-shadow: 0 4px 10px var(--card-shadow);
    transition: background-color 0.3s ease, transform 0.2s ease, box-shadow 0.3s ease;
}

#scrollToTopBtn:hover {
    background-color: #0056b3;
    /* Add a darker background on hover */
    transform: translateY(-2px);
    box-shadow: 0 6px 12px rgba(0, 0, 0, 0.3);
}

/* Fade-in Animation for sections (already present, adjusted timing) */
/* .fade-in styles moved into main section styles for brevity and clarity */


/* Mobile Responsiveness */
@media (max-width: 992px) {
    header h1 {
        font-size: 2.2em;
    }

    header .subtitle {
        font-size: 1em;
    }

    header nav ul li {
        margin: 0 10px;
    }

    header nav ul li a {
        padding: 8px 12px;
        font-size: 0.95em;
    }

    h2 {
        font-size: 2.2em;
        margin-bottom: 40px;
    }

    .about-content {
        flex-direction: column;
    }

    .profile-img {
        width: 150px;
        height: 150px;
        margin-bottom: 25px;
    }

    .project-grid {
        grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
        gap: 25px;
    }

    .project-card {
        padding: 25px;
    }

    #contactForm {
        padding: 30px;
    }
}

@media (max-width: 768px) {
    header {
        padding: 20px 0;
    }

    header nav ul {
        display: flex;
        flex-wrap: wrap;
        justify-content: center;
        margin-top: 15px;
    }

    header nav ul li {
        margin: 5px 8px;
    }

    section {
        padding: 60px 0;
    }

    h2 {
        font-size: 2em;
    }

    .profile-img {
        width: 120px;
        height: 120px;
    }

    .btn {
        padding: 10px 20px;
        font-size: 0.9em;
    }
}

@media (max-width: 480px) {
    header h1 {
        font-size: 2em;
    }

    header .subtitle {
        font-size: 0.85em;
    }

    header nav ul li a {
        padding: 6px 10px;
        font-size: 0.85em;
    }

    h2 {
        font-size: 1.8em;
        margin-bottom: 30px;
    }

    .about-content p {
        font-size: 1em;
    }

    .project-grid {
        grid-template-columns: 1fr;
        gap: 20px;
    }

    .project-card {
        padding: 20px;
    }

    #contactForm {
        padding: 20px;
    }

    .form-group label {
        font-size: 1em;
    }

    .form-group input,
    .form-group textarea {
        padding: 10px;
        font-size: 0.9em;
    }

    #scrollToTopBtn {
        bottom: 20px;
        right: 20px;
        padding: 12px;
        font-size: 16px;
    }
}
document.addEventListener('DOMContentLoaded', () => {
    // Smooth Scroll Navigation
    document.querySelectorAll('nav ul li a').forEach(anchor => {
        anchor.addEventListener('click', function (e) {
            e.preventDefault();

            document.querySelector(this.getAttribute('href')).scrollIntoView({
                behavior: 'smooth'
            });
        });
    });

    // Form Validation
    const contactForm = document.getElementById('contactForm');
    if (contactForm) {
        contactForm.addEventListener('submit', function (e) {
            e.preventDefault(); // Prevent default form submission

            const name = document.getElementById('name').value.trim();
            const email = document.getElementById('email').value.trim();
            const message = document.getElementById('message').value.trim();

            if (name === '') {
                alert('Please enter your name.');
                return;
            }

            if (email === '') {
                alert('Please enter your email address.');
                return;
            }

            // Basic email format validation
            const emailRegex = /^[^\s@]+@[^\s@]+\.[^\s@]+$/;
            if (!emailRegex.test(email)) {
                alert('Please enter a valid email address.');
                return;
            }

            if (message === '') {
                alert('Please enter your message.');
                return;
            }

            // If all validations pass
            alert('Form submitted successfully! (Note: This is a basic client-side validation. No actual submission is happening.)');
            contactForm.reset(); // Clear the form after successful submission
        });
    }

    // Scroll to Top Button
    const scrollToTopBtn = document.getElementById('scrollToTopBtn');

    window.onscroll = function () {
        if (scrollToTopBtn) {
            if (document.body.scrollTop > 200 || document.documentElement.scrollTop > 200) {
                scrollToTopBtn.style.display = "block";
            } else {
                scrollToTopBtn.style.display = "none";
            }
        }
    };

    if (scrollToTopBtn) {
        scrollToTopBtn.addEventListener('click', () => {
            window.scrollTo({
                top: 0,
                behavior: 'smooth'
            });
        });
    }

    // Fade-in Animation for Sections
    const sections = document.querySelectorAll('.fade-in');

    const observerOptions = {
        root: null, // relative to the viewport
        rootMargin: '0px',
        threshold: 0.1 // 10% of the section must be visible
    };

    const sectionObserver = new IntersectionObserver((entries, observer) => {
        entries.forEach(entry => {
            if (entry.isIntersecting) {
                entry.target.classList.add('active');
                // Removed unobserve here if you want the animation to re-trigger on scroll back
                // For a one-time fade-in when entering viewport, keep observer.unobserve(entry.target);
            } else {
                // Optional: Remove 'active' class when out of view to re-trigger on scroll back
                // entry.target.classList.remove('active');
            }
        });
    }, observerOptions);

    sections.forEach(section => {
        sectionObserver.observe(section);
    });
});
