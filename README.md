🌐 Static Website - Hosted on GitHub Pages (Portfolio Website) 

🎯 Objective
This project demonstrates how to deploy a simple static website using **GitHub Pages**. It includes the creation of a personal portfolio in **HTML** and **CSS**, which is then hosted and served directly from GitHub.

🛠️ Tools Used
- **GitHub Pages**: For hosting the static website.
- **HTML**: To structure the content.
- **CSS**: For styling and layout of the website.
- **FontAwesome**: For icons and enhanced UI components.

🚀 Deliverables
- A **live website link** hosted on GitHub Pages.
- **GitHub repository** containing the source code of the website.

📖 Mini Guide
Follow the steps below to host a static website using GitHub Pages:

1. Create index.html file
The main HTML file (`index.html`) is the entry point of your website. Below is the structure of the portfolio used for this project:

## html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Soneeya S S - Portfolio</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap" rel="stylesheet">
  <script src="https://kit.fontawesome.com/a076d05399.js" crossorigin="anonymous"></script>
  <style>
    /* Custom CSS for styling the portfolio */
    :root {
      --bg-light: #f4f6f9;
      --bg-dark: #1e1e2f;
      --text-light: #333;
      --text-dark: #f1f1f1;
      --accent: #0077b6;
    }

    /* Additional styles here... */
  </style>
</head>
<body>
  <header>
    <h1>Soneeya S S</h1>
    <p>Contact: soneeyasubramanian@gmail.com</p>
  </header>

  <section class="section">
    <h2>Professional Summary</h2>
    <p>Aspiring DevOps Engineer with expertise in cloud infrastructure, AWS, and automation.</p>
  </section>

  <!-- More sections as required -->

  <script>
    function toggleDarkMode() {
      document.body.classList.toggle('dark-mode');
    }
  </script>
</body>
</html>

2. Push to GitHub Repository
Create a new repository on GitHub.

Push the index.html file (and any additional files such as CSS if required) to the repository.

3. Enable GitHub Pages
--Go to the Settings of your GitHub repository.
--Scroll down to the Pages section.
--Under Source, select the main branch and the root folder as the source for the Pages.
--Click Save.

4. Select Main Branch and Root Folder
--After saving the settings, GitHub Pages will deploy the site from the main branch.
--Make sure that your index.html is in the root directory of your repository.

5. Access Live Website
Once GitHub Pages has deployed the site (usually within a few minutes), you will receive a live URL link to access the website.

Example:
https://<your-github-username>.github.io/<repository-name>/

6. Customization with CSS
You can modify the index.html file and the CSS to match your branding, including changes to fonts, colors, layouts, and more. To switch to dark mode, the portfolio includes a button to toggle between light and dark modes.

📝 License
This project is licensed under the MIT License - see the LICENSE file for details.

📧 Contact
Email: soneeyasubramanian@gmail.com
LinkedIn: Soneeya S S LinkedIn


