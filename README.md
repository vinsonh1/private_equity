Private Equity Investment Website
Overview
This is a static webpage for Privé Capital, a private equity and investment firm. The site showcases our investment philosophy, portfolio, team, and contact information, designed to provide a professional and user-friendly experience for potential investors and partners.
Features

Responsive Design: Optimized for desktop, tablet, and mobile devices.
Clean UI: Professional and modern layout with a focus on readability and navigation.
Sections:
Home: Introduction to the firm and its mission.
About: Details on the firm's investment philosophy and approach.
Portfolio: Highlights of current and past investments.
Team: Profiles of key team members.
Contact: Form and details for reaching out to the firm.


SEO Optimized: Includes meta tags and structured data for better search engine visibility.

Technologies Used

HTML5: For semantic structure.
CSS3: For styling, with Tailwind CSS for rapid development and responsiveness.
JavaScript: For interactive elements like form validation and smooth scrolling.
FontAwesome: For icons to enhance visual appeal.
GitHub Pages: For hosting the static site.

Installation
To run this project locally or deploy it on GitHub Pages:

Clone the Repository:
git clone https://github.com/your-username/your-repo-name.git


Navigate to the Project Directory:
cd your-repo-name


Open the Site:

Open index.html in a web browser to view the site locally.
Alternatively, use a local server like Live Server in VS Code for a better development experience.


Dependencies:

No external dependencies are required beyond a modern web browser.
If using Tailwind CSS, ensure the CDN link is included in index.html or build the CSS using:npm install
npx tailwindcss -i ./src/input.css -o ./dist/output.css --watch





Deployment
To deploy the site on GitHub Pages:

Ensure all files are in the main branch or a gh-pages branch.
Go to your repository on GitHub.
Navigate to Settings > Pages.
Select the branch (main or gh-pages) and the root directory.
Save, and your site will be live at https://your-username.github.io/your-repo-name.

Usage

Customize Content: Edit the HTML files in the src folder to update text, images, or portfolio details.
Update Styling: Modify the dist/output.css file or adjust the Tailwind classes in HTML for styling changes.
Add Analytics: Integrate tools like Google Analytics by adding the tracking script to index.html.
Form Handling: The contact form requires a backend service (e.g., Formspree or Netlify Forms) for submission handling. Update the form action in contact.html accordingly.

Directory Structure
/your-repo-name
├── src/                  # Source files
│   ├── index.html        # Homepage
│   ├── about.html        # About page
│   ├── portfolio.html    # Portfolio page
│   ├── team.html         # Team page
│   ├── contact.html      # Contact page
│   └── assets/           # Images, fonts, and other static assets
├── dist/                 # Compiled CSS and other build outputs
│   └── output.css        # Tailwind CSS output
├── README.md             # This file
└── package.json          # Node.js configuration (if using Tailwind CLI)

Contributing
Contributions are welcome! To contribute:

Fork the repository.
Create a new branch (git checkout -b feature/your-feature).
Make your changes and commit (git commit -m 'Add your feature').
Push to the branch (git push origin feature/your-feature).
Open a pull request.

Please ensure your changes align with the site's professional tone and design standards.
License
This project is licensed under the MIT License. See the LICENSE file for details.
Contact
For inquiries, please contact Vinson Hall at: Privé Capital

Email: hall.vinson1@gmail.com
Website: www.prive-capital.com

