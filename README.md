# Project-01
Portfolio Website – MyGruham

This is a static portfolio website hosted under portfolio.mygruham.com, designed to showcase personal skills, projects, testimonials, and work terms in a professional and minimal style.

The site is built with HTML, CSS, and a little JavaScript, making it fast, lightweight, and easy to maintain.

🌟 Features

About Me Section – Simple introduction with profile image.

Skills Section – Resume-style skills with progress bars.

Projects Showcase – Filterable projects gallery.

Social Links – Buttons (Fiverr, Upwork, LinkedIn, GitHub, Instagram, WhatsApp, Telegram) with icons.

Contact Form – Integrated with Google Forms (easy form submissions without backend).

Testimonials – Space to collect and display short client feedback.

Terms of Work – Separate page outlining scope, payment, timelines, and revision policy, with an agreement checkbox.

Responsive Design – Optimized for desktop, tablet, and mobile.

🛠️ Tech Stack

Frontend: HTML5, CSS3, JavaScript (vanilla)

Icons: FontAwesome / Icons8

Forms: Google Forms integration

Hosting: GoDaddy (current) → Can be migrated to AWS S3 + CloudFront later

Version Control: Git (recommended)

📂 Folder Structure
portfolio/
│── index.html          # Main portfolio page
│── about.html          # About me (optional separate page)
│── projects.html       # Projects showcase
│── testimonials.html   # Client feedback
│── terms.html          # Terms of Work (with agreement checkbox)
│── assets/
│    ├── css/
│    │    └── style.css
│    ├── js/
│    │    └── script.js
│    ├── img/
│    │    └── profile.jpg (and other images)

How to Run

Clone the repository:

git clone https://github.com/Theramya10/Project-01.git
cd dist

Open index.html in a browser.

To host:

Upload files to GoDaddy File Manager (or via cPanel).

Alternatively, host on AWS S3 + CloudFront for scalability.

📬 Contact Form Setup

A Google Form link is embedded in the Contact Me section.

When a user clicks “Send Message”, it opens the form in a new tab.

Responses are collected directly in Google Sheets (no backend required).

💬 Testimonials

Keep testimonials short (1–2 lines).
Example:

“Delivered high-quality work ahead of schedule. Highly recommended!” – John D.

“Very professional and clear communication. Will work again.” – Sarah K.

📜 Terms of Work (Example Draft)

Scope: Work will be defined clearly before starting.

Payment: 50% advance, 50% upon completion.

Timeline: Agreed project duration will be followed.

Revisions: Up to 2 rounds of revisions included. Extra revisions may cost extra.

Agreement: Client must agree to these terms before work begins.

Checkbox: ✅ I agree to the terms.

🌍 Future Improvements

Migrate hosting from GoDaddy → AWS S3 + CloudFront for better scalability.

Add CMS (Contentful / Sanity) for easier testimonial & project updates.

Expand with blog/articles section.

📌 License
This project is for personal portfolio use. Free to reuse the design structure, but content (text, images, testimonials) belongs to the author.


