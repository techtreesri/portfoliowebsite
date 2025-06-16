Sriparno Chakraborty's Portfolio Website
Overview
This is a personal portfolio website for Sriparno Chakraborty, a BCA student passionate about cybersecurity and data mining. The website features an aesthetic design with a soft, earthy color palette (terracotta, light beige, pale peach, sage green, and dark olive), elegant fonts, and a clean, minimal layout. It showcases Sriparno's background, research interests, and provides links to connect via LinkedIn, Gmail, and GitHub. The site also includes a profile picture and a section highlighting relevant research papers.
Features

Aesthetic Design: Uses a warm, earthy color palette with Playfair Display and Lora fonts for a calming, elegant look.
Profile Picture: Displays a circular profile photo with a terracotta border.
Research Papers Section: Features three clickable research paper titles linking to external sources (arXiv, IEEE, Springer).
Interactive Buttons: Links to LinkedIn, Gmail (Contact Me), and GitHub with hover effects.
Responsive Design: Optimized for both desktop and mobile devices.
Sections: Includes "About Me", "Research Papers", and "Connect with Me" sections with a cohesive design.

Setup Instructions
Follow these steps to run the website locally:

Clone or Download the Repository:

If using Git, clone the repository: git clone <repository-url>.
Alternatively, download the project files as a ZIP and extract them.


Open the Project in VS Code:

Launch Visual Studio Code.
Go to File > Open Folder and select the project folder (e.g., portfolio).


Install Live Server Extension:

In VS Code, go to the Extensions view (Ctrl+Shift+X or Cmd+Shift+X on Mac).
Search for "Live Server" by Ritwick Dey and install it.


Update Links and Photo:

Open index.html and script.js.
Replace the placeholder URLs for LinkedIn, Gmail, and GitHub with your actual profile links:
LinkedIn: https://www.linkedin.com/in/your-linkedin-username
Gmail: mailto:your-email@gmail.com?subject=Contact%20from%20Portfolio
GitHub: https://github.com/your-github-username


Replace the research paper URLs in index.html with the actual links to the papers you want to feature.
Update the profile picture in index.html by replacing src="my-picture.jpg" with the path to your photo (ensure the photo is in the portfolio folder).


Run the Website:

Right-click index.html in the Explorer pane and select "Open with Live Server".
Your default browser will open the website at http://127.0.0.1:5500 or a similar address.
Test the website by clicking the research paper links, hovering over buttons, and checking responsiveness.



Project Structure

index.html: The main HTML file containing the website structure.
styles.css: The CSS file with aesthetic styling and responsive design.
script.js: The JavaScript file handling button interactivity (opening links in new tabs).
my-picture.jpg: Your profile picture (replace with your actual photo file).
README.md: This documentation file.

Customization
To personalize the website further:

Add More Research Papers:Add new entries in the research section of index.html:<li>
    <a href="your-paper-url" target="_blank" class="research-link">
        Your Paper Title
    </a>
</li>


Change Colors:Modify the color palette in styles.css (e.g., change #B66A50 (terracotta) to another soft shade like #D4A5A5 for a pinker tone).
Adjust Photo Size:Modify the profile-pic img styles in styles.css to change the size:.profile-pic img {
    width: 200px;
    height: 200px;
    border-radius: 50%;
    border: 3px solid #B66A50;
    box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
    object-fit: cover;
}


Add a Projects Section:Add a new section in index.html:<section class="projects">
    <h2>My Projects</h2>
    <p>Phishing Shield: A browser extension to detect phishing websites.</p>
    <p>Data Mining Tool: Analyzed datasets to uncover user behavior patterns.</p>
</section>

Style it in styles.css:.projects {
    background: #F5E6E0;
    padding: 20px;
    border-radius: 10px;
    box-shadow: 0 4px 15px rgba(0, 0, 0, 0.1);
    margin-bottom: 40px;
}
.projects p {
    font-size: 1.1em;
    color: #4A5B4E;
}



Hosting
To host the website online:

GitHub Pages:
Push the project to a GitHub repository (git add ., git commit -m "Initial commit", git push).
Go to the repository settings on GitHub.
Enable GitHub Pages under the "Pages" section, selecting the main branch.
Access the site at https://your-username.github.io/repository-name.


Ensure your photo (my-picture.jpg) is included in the repository.


Netlify:
Drag and drop the project folder into Netlify's dashboard.
Deploy the site and get a live URL.


Ensure your photo is included in the folder.



Credits

Fonts: Uses Playfair Display and Lora from Google Fonts.
Design Inspiration: Aesthetic theme with a soft, earthy color palette.
Development: Created with assistance from Grok 3 by xAI.

License
This project is for personal use. Feel free to modify and share, but please give credit to the original creator.
