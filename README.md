# Hosting an HTML, CSS Website on Netlify

This guide will walk you through the steps to host your HTML and CSS website on Netlify. Netlify is a powerful platform for deploying static websites with ease.

## Prerequisites

1. A GitHub, GitLab, or Bitbucket account (for linking your repository to Netlify).
2. A completed HTML and CSS website.
3. A Netlify account (sign up [here](https://www.netlify.com/)).

## Step-by-Step Guide

### 1. Prepare Your Project

Ensure your project is organized with all HTML files, CSS files, and other assets (like images, fonts, etc.) properly structured. The main entry point for your website should be an `index.html` file in the root of your project directory.

### 2. Push Your Project to a Git Repository

1. **Initialize a Git Repository** (if not already done):
   ```bash
   git init
2. **Add Your Files**:
   ```bash
   git add .
3. **Commit Your Changes**:
   ```bash
   git commit -m "Initial commit"
4. **Push to GitHub** (or your preferred Git provider):
   ```bash
   git remote add origin https://github.com/yourusername/your-repo-name.git
   git push -u origin master
### 3. Deploy on Netlify

1. **Sign in to Netlify**: Go to [Netlify](https://www.netlify.com/) and sign in with your account.
    
2. **New Site from Git**:
   - Click on the "New site from Git" button on your Netlify dashboard.

3. **Link to Your Git Provider**:
   - Choose your Git provider (GitHub, GitLab, or Bitbucket).
   - Authorize Netlify to access your repositories.
   - Select the repository you want to deploy.

4. **Configure Your Build Settings**:
   - For a basic HTML/CSS site, there is no need for a build command or publish directory. Netlify automatically detects and sets these for you.
   - Ensure the "Publish directory" is set to the folder containing your `index.html` file. For most simple HTML/CSS projects, this should be the root directory (`/`).

5. **Deploy**:
   - Click the "Deploy site" button.
   - Netlify will start the deployment process. You can see the progress in the deploy log.

### 4. Access Your Site

Once the deployment is complete, Netlify will provide you with a unique URL for your site. You can access your site immediately via this URL.


