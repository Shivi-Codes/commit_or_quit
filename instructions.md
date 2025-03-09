# Bootstrap Project Outline: 'Commit or Quit' Website

## Project Overview

Your task is to build a fully responsive website for a fictional web development business called **'Commit or Quit'** using **Bootstrap**. The website should include **three pages**: Home, Services, and Contact. You will also set up Git version control and deploy the site on **Netlify**.

---

## Step 1: Setup Project

1. Create a new project folder and navigate into it:
   ```sh
   mkdir commit-or-quit && cd commit-or-quit
   ```
2. Initialize a new Git repository (Git is already set up):
   ```sh
   git init
   ```
3. Create the basic project structure:
   ```sh
   mkdir css js img
   touch index.html services.html contact.html
   ```
4. Install Bootstrap via npm:
   ```sh
   npm init -y
   npm install bootstrap
   ```
5. Link Bootstrap in your HTML files (using local installation, not CDN):
   ```html
   <link
     rel="stylesheet"
     href="node_modules/bootstrap/dist/css/bootstrap.min.css"
   />
   <script src="node_modules/bootstrap/dist/js/bootstrap.bundle.min.js"></script>
   ```
6. Commit and push your setup:
   ```sh
   git add .
   git commit -m "Initial project setup with Bootstrap installed"
   git push
   ```

---

## Step 2: Build the Home Page (index.html)

### Structure:

- **Navigation bar** (Bootstrap Navbar)
- **Hero section** with a business tagline
- **About section** with a brief description
- **Call to Action (CTA)** leading to the Services page

1. Implement Bootstrap Grid for a responsive layout.
2. Customize Bootstrap styles
3. Add content using Bootstrap components like **buttons, cards, and containers**.

**Git commands:**

```sh
 git add .
 git commit -m "Added Home Page structure and styling"
 git push
```

---

## Step 3: Build the Services Page (services.html)

### Structure:

- **Header** with page title
- **Service descriptions** (use Bootstrap cards or grid)
- **Pricing section** (use Bootstrap tables or cards)

1. Ensure responsive layout with Bootstrap classes.
2. Add styling customization as needed.
3. Use Bootstrap icons if necessary.

**Git commands:**

```sh
 git add .
 git commit -m "Created Services Page with Bootstrap components"
 git push
```

---

## Step 4: Build the Contact Page (contact.html)

### Structure:

- **Header** with page title
- **Contact form** (Bootstrap form)
- **Business address and social links**

1. Create a form with **name, email, message fields**, and a submit button.
2. Research and wire up **Netlify Forms** so the form submits properly.
3. Add a confirmation message after submission.
4. Ensure proper form validation with Bootstrap.

**Git commands:**

```sh
 git add .
 git commit -m "Added Contact Page with Netlify Form support"
 git push
```

---

## Step 5: Customize Bootstrap

1. Customise bootsrap in the same way the Net Ninja showed you.

**Git commands:**

```sh
 git add .
 git commit -m "Customized Bootstrap styles"
 git push
```

---

## Step 6: Deploy on Netlify

1. Push all changes to GitHub (ensure a repository is created).
2. Go to [Netlify](https://www.netlify.com/) and connect your GitHub repo.
3. Set up automatic deployment.
4. Ensure the **Netlify form is functional**.
5. Get the **live site link**.

**Git commands:**

```sh
 git add .
 git commit -m "Finalized project and prepared for deployment"
 git push
```

---

## Step 7: Submit Your Work

1. Ensure all pages are responsive.
2. Confirm form submission works.
3. Submit the **Netlify live link**.
