Xolani Mti - Personal Portfolio Website

This repository contains the source code for my personal portfolio website, designed to be hosted on GitHub Pages. It's a clean, single-page, responsive website built to showcase my skills, experience, and projects as a Senior Data Engineer.
Features

    Single-Page Layout: All information is presented on a single, easy-to-navigate page.

    Responsive Design: Looks great on all devices, from mobile phones to desktops.

    Dark Mode: Includes a toggle for a user-friendly dark theme that respects system preferences.

    Smooth Scrolling: Clicking navigation links smoothly animates to the corresponding section.

    Built with Tailwind CSS: Utilizes a modern utility-first CSS framework for rapid UI development.

Deployment with GitHub Actions

This project uses a GitHub Actions workflow to automatically deploy the website to GitHub Pages.
How it Works

    Any push to the main branch triggers the workflow.

    The workflow takes the contents of the repository (your index.html file).

    It pushes these contents to a special deployment branch called gh-pages.

    GitHub Pages serves the website from this gh-pages branch.

Setup Instructions

    Create Repository:

        Create a new public repository on GitHub named your-username.github.io.

    Upload Files:

        Upload your index.html file.

        Create a directory named .github/workflows.

        Inside that directory, create a new file named deploy.yml and paste the contents of the workflow file into it.

    Set Deployment Branch:

        In your repository's Settings tab, go to the Pages section in the sidebar.

        Under "Build and deployment", for the Source, select "Deploy from a branch".

        Under "Branch", select main as the source branch and / (root) as the folder. Click Save.
Under Actions view the build of the pages
After a minute or two, your website will be live at https://your-username.github.io. From now on, any changes you push to the main branch will automatically be deployed to your live site.

Customization

To make this website your own, you'll need to edit the index.html file.

    Personal Information:

        Search for "Xolani Earl Mti" and replace it with your name.

        Update the email address earl4xolani@gmail.com to your own.

        Change the professional summary and "About Me" text to reflect your own story.

    Update Links:

        In the header, contact section, and footer, you will find links with href="#". Replace the # with your actual URLs for:

            GitHub profile

            LinkedIn profile

            Project details and research papers

    Update Photo:

        Find the <img> tag in the "About/Hero Section".

        Replace the src URL (https://placehold.co/...) with a direct link to a professional photo of yourself.

    Edit Content:

        Go through the "Skills", "Experience", and "Projects" sections and replace the content with your own details.

Tech Stack

    HTML5

    Tailwind CSS

    Font Awesome (for icons)

    Google Fonts