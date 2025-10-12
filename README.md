PricePilot.ai - AI-Powered Car Price Predictor
PricePilot.ai is a modern, responsive, and user-friendly web application designed to provide instant and accurate price valuations for used cars. It leverages a sophisticated, multi-step form and integrates with Google's Gemini AI to offer users a comprehensive understanding of their car's market value.

1. Project Information
Project Name: PricePilot.ai

Description: A free tool that uses real-time market data and AI to provide transparent, hyper-local car valuations. It includes unique features powered by the Gemini API, such as an AI Sales Pitch Generator and an AI Maintenance Advisor.

Live URL: You can view a live version of the project here: https://g.co/gemini/share/c32bedeee517

2. How to Edit the Code
Editing this project is straightforward because the entire website is contained within a single file (index.html).

Download the Code: Make sure you have the index.html file on your computer.

Open in an Editor: Open the index.html file in any text editor. For the best experience with syntax highlighting, use a code editor like Visual Studio Code, Sublime Text, or Atom.

Make Your Changes:

HTML: The structure and content of the website are defined by the standard HTML tags (e.g., <div>, <h1>, <p>, <form>).

CSS/Styling: All visual styles are located within the <style> tags in the <head> section. The project uses Tailwind CSS classes directly in the HTML for styling.

JavaScript/Functionality: All the interactive logic, form handling, price calculations, and API calls are located within the <script> tags at the bottom of the file.

Save and Preview: After making changes, simply save the file and open it in your web browser to see the results instantly.

3. Technologies Used
This project is built as a single, self-contained frontend application, making it lightweight and easily portable.

Frontend:

HTML5: For the core structure and content.

Tailwind CSS: For modern, utility-first styling and a responsive layout (loaded via a CDN).

JavaScript (ES6): To handle all the application logic, including the multi-step form, dynamic content, price calculations, and API calls.

AI & APIs:

Google Gemini API: The gemini-2.5-flash-preview-05-20 model is used for the "AI-Powered Insights" features.

4. How to Deploy the Project
Since this is a static website, you can deploy it for free on various platforms.

Deploying with GitHub Pages (Recommended)
Create a GitHub Repository: Push your index.html file to a new or existing repository on GitHub.

Navigate to Settings: In your repository, click on the "Settings" tab.

Go to Pages: In the left-hand sidebar, click on "Pages".

Configure Source: Under the "Build and deployment" section, select "Deploy from a branch" as the source.

Select Branch: Choose the branch where your code is located (usually main or master) and keep the folder as / (root).

Save: Click "Save".

Done! Your site will be live in a few minutes at the URL provided in the green banner (e.g., https://<your-username>.github.io/<your-repo-name>/).

5. Connecting a Custom Domain
Yes, you can absolutely connect a custom domain to your project after deploying it. The process depends on your deployment provider (e.g., GitHub Pages, Netlify, Vercel).

For a Site Deployed on GitHub Pages:
Purchase a Domain: Buy a domain name from a registrar like GoDaddy, Namecheap, or Google Domains.

Add Custom Domain in GitHub:

Go to your repository's Settings > Pages.

In the "Custom domain" section, type your custom domain (e.g., www.pricepilot.ai) and click "Save".

Configure DNS Records:

Go to your domain registrar's website (e.g., GoDaddy).

Find the DNS management settings for your domain.

You will need to add A records and a CNAME record to point your domain to GitHub's servers.

Create four A records pointing to GitHub's IP addresses:

185.199.108.153

185.199.109.153

185.199.110.153

185.199.111.153

Create a CNAME record for www that points to your default GitHub Pages URL (e.g., <your-username>.github.io).

After you configure the DNS records, it may take a few hours for the changes to take effect. GitHub will then automatically provision an SSL certificate for your custom domain, making it accessible via https://.
