# Erick Michael Conklin – Financial Advisor Website

## Description

This project is a professional single-page website for Erick Michael Conklin, a Financial Advisor. It aims to provide visitors with information about his services, experience, qualifications, and an easy way to get in touch. The website is designed to be responsive, modern, and informative.

## Features

* **Hero Section:** Welcoming message and a call-to-action for a detailed report.
* **About Me:** Summary of qualifications, experience, registrations, and key statistics.
* **Services:** Overview of financial services offered (Investment Planning, Retirement Planning, Stock Market Advisory, Wealth Management).
* **Licenses:** List of states and territories where licensed.
* **Experience:** Work history timeline.
* **FAQ:** Answers to frequently asked questions.
* **Contact Form:** Allows visitors to send a message to book a session or make inquiries (currently configured to use Formspree).
* **Responsive Design:** Adapts to various screen sizes (desktop, tablet, mobile).
* **Smooth Scrolling:** For navigation links.
* **Animations:** Subtle animations on scroll using AOS (Animate On Scroll).

## Technologies Used

* **HTML5:** For the basic structure of the website.
* **Tailwind CSS:** For styling and responsive design (loaded via CDN).
* **JavaScript:** For interactive elements like the mobile navigation, experience timeline scroller, dynamic copyright year, and scroll animations.
* **Google Fonts:** For typography (`Playfair Display` and `Roboto`).
* **Font Awesome:** For icons (loaded via CDN).
* **AOS (Animate On Scroll):** For scroll animations (loaded via CDN).
* **Formspree:** For handling contact form submissions.
* **Git & GitHub:** For version control and as a deployment source.
* **Vercel:** For hosting the live website (deployed from GitHub).

## Setup (Viewing Locally)

1.  Clone the repository (if it's on GitHub) or ensure you have the project files in a folder on your computer.
2.  Open the `index.html` file directly in a web browser.
    * *Note: The contact form submission via Formspree will only work correctly when the site is accessed via HTTP/HTTPS (i.e., when deployed or if you run a local server), not always when opening `index.html` directly from the file system (`file:///...`). For full functionality including form testing, view the deployed site.*

## Deployment

This website is configured for deployment on **Vercel** via **GitHub**.
1.  Push your local Git repository to a GitHub repository.
2.  Connect your GitHub repository to a new project on Vercel.
3.  Vercel will automatically build and deploy the site. Subsequent pushes to the production branch (e.g., `main`) on GitHub will trigger automatic re-deployments.

## Contact Form

The contact form in the "Book a Session" section (`id="book-call"`) is configured to send submissions to an endpoint provided by **Formspree**.
* The form's `action` attribute in `index.html` should point to your unique Formspree endpoint URL.
* Submissions will be forwarded to the email address associated with your Formspree account and can be viewed in the Formspree dashboard.

## Key Files & Folders

* `index.html`: The main HTML file containing all website content and structure.
* `images/`: Folder containing portrait images and potentially other site graphics.
    * `Professional Financial Advisor Headshot.png`
    * `Professional Portrait in Office Setting.png`
* `README.md`: This file, providing information about the project.
* *(Optional) `thank-you.html` / `error.html`: If you configure Formspree to redirect to custom success/error pages hosted on your site.*
* *(Optional) `.gitignore`: To exclude unnecessary files from Git tracking.*

## Image Credits

* Placeholder images for services are sourced from Unsplash. Ensure actual service-related images are used for the final version.
* Portrait images should be professional photos of Erick Michael Conklin.

---

This `README.md` should give a good overview. You can customize it further as needed! For instance, if you set up a custom domain on Vercel, you might want to add the live URL to the description."# eric-website" 
"# eric-website" 
