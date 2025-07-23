# my-portfolio
Visual :-

<img width="513" height="1818" alt="Screenshot 2025-07-21 at 03-43-39 AZIUL HAKIM - Portfolio" src="https://github.com/user-attachments/assets/0f02002d-d17f-45be-8580-dab2d0f989fd" />




<img width="1818" height="549" alt="Screenshot 2025-07-21 at 03-44-09 AZIUL HAKIM - Portfolio" src="https://github.com/user-attachments/assets/09349983-3709-4601-a34a-77f83abf2fdc" />




<img width="1780" height="871" alt="Screenshot 2025-07-21 at 03-44-41 AZIUL HAKIM - Portfolio" src="https://github.com/user-attachments/assets/4325ac56-52b4-4466-941f-dfde7fea19fb" />




![photo_2025-07-21_04-08-12](https://github.com/user-attachments/assets/e67dffc9-8cfc-417b-8fc3-ce5f6666a5a7)





<img width="1357" height="754" alt="Screenshot 2025-07-21 at 03-46-30 AZIUL HAKIM - Portfolio" src="https://github.com/user-attachments/assets/571ce10b-8597-4bd8-ab49-3644afbd3dbd" />




<img width="1470" height="493" alt="Screenshot 2025-07-21 at 03-46-51 AZIUL HAKIM - Portfolio" src="https://github.com/user-attachments/assets/642c3d91-2dea-49c8-82ff-48398b50f3df" />


Explaination_

Welcome to my personal portfolio website! This is a showcase of my skills, projects, and passion for web development. Built with HTML and CSS, this portfolio features a sleek dark theme, responsive design, and engaging animations to highlight my work as a web developer. Whether you're a potential employer, collaborator, or just curious, I hope you enjoy exploring my projects and learning more about me!
Table of Contents

About the Project
Features
Technologies Used
Setup and Installation
How to Customize
Deploying the Portfolio
Troubleshooting
Contributing
Contact

About the Project
This portfolio is my digital space to showcase my skills in web development and my projects. It’s designed to be clean, modern, and responsive, ensuring it looks great on any device, from phones to desktops. The dark theme gives it a professional yet stylish vibe, with subtle animations like a typing effect in the hero section and hover effects on project cards to make the experience engaging.
The portfolio includes:

About Me: A brief introduction to who I am and my background.
Projects: A gallery of my projects with images and descriptions.
Skills: A visual representation of my technical skills using progress bars.
Contact: Links to connect with me via email, LinkedIn, and GitHub.

You can view the live site here: https://ahsumon77.github.io/my-portfolio/
Features

Responsive Design: Adapts seamlessly to mobile, tablet, and desktop screens.
Dark Theme: A modern, eye-friendly dark color scheme with a vibrant purple accent.
CSS Animations: Includes a typing effect in the hero section and hover effects on project cards.
Masonry Grid: Projects are displayed in a clean, responsive grid layout.
Accessible: Uses semantic HTML and descriptive alt text for images to ensure accessibility.
Easy to Customize: Simple structure for adding new projects or updating content.

Technologies Used

HTML5: For the structure and content of the portfolio.
CSS3: For styling, animations, and responsive design (using Flexbox, Grid, and media queries).
Google Fonts: For the "Roboto" font, giving the site a clean and professional typography.
GitHub Pages: For hosting the live website.

Setup and Installation
To run this portfolio locally or make changes, follow these steps:

Clone the Repository:
git clone https://github.com/ahsumon77/my-portfolio.git
cd my-portfolio


Check the File Structure:Ensure your project folder looks like this:

my-portfolio/
├── index.html

├── assets/

│   ├── my-photo.jpg

│   ├── project1.jpg

│   ├── project2.jpg

│   ├── project3.jpg

│   ├── my-project.jpg


Open Locally:

Open index.html in a browser to preview the site.
For a better local testing experience, use Visual Studio Code with the Live Server extension:
Install the Live Server extension in VS Code.
Right-click index.html and select “Open with Live Server” to view at http://localhost:5500.




Verify Images:

Ensure all images in the assets/ folder match the paths in index.html (e.g., assets/my-photo.PNG).
If images don’t load, check for case sensitivity (e.g., my-photo.PNG ≠ my-photo.jpg).



How to Customize
You can easily personalize this portfolio to reflect your own style and projects:

Update Personal Info:

Edit index.html to update your name, bio, and contact details:<p class="hero-subtitle">I'm [Your Name], a [Your Profession]</p>
<p>Email: <a href="mailto:your.email@example.com">your.email@example.com</a></p>
<p>LinkedIn: <a href="https://linkedin.com/in/yourprofile">linkedin.com/in/yourprofile</a></p>
<p>GitHub: <a href="https://github.com/yourusername">github.com/yourusername</a></p>




Add or Update Projects:
In the <section class="projects"> of index.html, add a new project block:<div class="project">
    <img src="assets/your-new-project.PNG" alt="Your Project Name">
    <div class="project-info">
        <h3>Your Project Name</h3>
        <p>Brief description of your project.</p>
        <a href="https://project-link.com">View Project</a>
    </div>
</div>


Place the new image in the assets/ folder and update the src and alt attributes.


Update Skills:
In the <section class="skills">, modify or add skill blocks:<div class="skill">
    <span>New Skill</span>
    <div class="progress-bar">
        <div class="progress" style="width: 75%;"></div>
    </div>
</div>


Adjust the style="width: X%" to reflect your skill level.


Change Colors or Fonts:

Edit the :root variables in the <style> section of index.html::root {
    --primary-color: #7a00ff; /* Change to your preferred accent color */
    --secondary-color: #1a1a1a; /* Dark background */
    --background-color: #121212; /* Main background */
    --text-color: #e0e0e0; /* Text color */
}


Change the font by updating the Google Fonts link in <head> 
(e.g., replace Roboto with another font from Google Fonts).


Add Images:

Place new images in the assets/ folder.
Update src attributes in index.html to match the exact file name (case-sensitive, e.g., my-photo.PNG).



Deploying the Portfolio
The portfolio is hosted on GitHub Pages at https://ahsumon77.github.io/my-portfolio/. To deploy or update it:

Push Changes to GitHub:

After making changes locally:git add .
git commit -m "Update portfolio content"
git push origin main


Or manually upload files via GitHub:
Go to https://github.com/ahsumon77/my-portfolio.
Click “Add file” > “Upload files” and upload updated index.html or assets/ files.
Commit changes.




Verify GitHub Pages:

Ensure GitHub Pages is enabled:
Go to “Settings” > “Pages” in your repository.
Confirm the source is set to the main branch and the root folder (/).


Wait 1-5 minutes for changes to reflect at https://ahsumon77.github.io/my-portfolio/.


Alternative: Deploy on Netlify:

Sign up at netlify.com.
Go to “Sites” > “Add new site” > “Import an existing project.”
Connect to your GitHub repository (ahsumon77/my-fortfolio) and deploy the main branch.
Netlify provides a unique URL (e.g., your-site-name.netlify.app).



Troubleshooting

Images Not Showing Online:
Issue: Images load locally but not on the live site.
Fix: Ensure src paths in index.html match file names exactly (e.g., assets/my-photo.PNG not my-photo.jpg). Check case sensitivity and upload missing images to the assets/ folder on GitHub.
Use browser developer tools (F12 > Network > Img) to check for 404 errors.


Changes Not Updating:
Fix: Clear your browser cache or use incognito mode. Wait 1-5 minutes for GitHub Pages to redeploy.


Responsive Issues:
Fix: Test on multiple devices. Adjust media queries in the <style> section if needed.



For more help, see GitHub Pages Troubleshooting.
Contributing

This is a personal portfolio, but I’m open to feedback or suggestions! Feel free to open an issue or submit a pull request if you have ideas to improve the design or functionality.
Contact
I’d love to connect! Reach out to me at:

Email: azizulhakimsumon@gmail.com

[LinkedIn:- linkedin.com/in/azizul-hakim-sumon]

[GitHub:- github.com/ahsumon77]

Thanks for visiting my portfolio! I’m excited to share my journey in web development and look forward to connecting with you.
