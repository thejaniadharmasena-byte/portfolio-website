PORTFOLIO WEBSITE + EDITING DASHBOARD
=====================================

WHAT'S IN THIS FOLDER
  index.html        the website (design unchanged)
  content/          the text and project lists the dashboard edits (don't edit these by hand)
  admin/            the dashboard, lives at  yourwebsite.netlify.app/admin
  images/           your project images
  netlify.toml      tells Netlify to publish this folder as it is

ONE-TIME SETUP (about 20-30 minutes)
  Step 1. Create a free GitHub account at github.com (this is where your site files are stored).
  Step 2. Install the free "GitHub Desktop" app from desktop.github.com and sign in with your GitHub account.
  Step 3. In GitHub Desktop choose File > Add local repository and pick this folder (the one containing
          index.html). It will say the folder is not a repository: click "create a repository", then
          "Create repository". Then click "Publish repository" in the top bar. Keeping the code private
          or public both work. Your files are now on GitHub.
  Step 4. In Netlify open your site (thejanidharmasena) > Project configuration > Build & deploy >
          Continuous deployment > Repository > "Link repository". Choose GitHub and the repository from
          Step 3. Leave "Build command" empty and "Publish directory" empty (or "."), then save.
          Netlify now publishes your site from GitHub automatically.
  Step 5. In Netlify: Project configuration (or Integrations) > Identity > Enable Identity.
          Set Registration to "Invite only".
          Scroll to "Services" > "Git Gateway" and click "Enable Git Gateway".
  Step 6. In Netlify > Identity > "Invite users", type your own email address and send the invite.
          Open the email, click the link, and set a password. That opens your dashboard.
  (Menu names in Netlify change from time to time. If something looks different, tell Claude what
  you see on screen.)

USING THE DASHBOARD
  Go to  https://thejanidharmasena.netlify.app/admin  and log in.
  Click "My Portfolio" and pick what to edit:
    - Welcome text, Contact info & Social links
    - Projects (add, delete, drag to reorder, change images)
    - Experience & Education
  When finished click "Publish" (top) > "Publish now". The live site updates in about a minute.

IMAGE TIPS
  Upload images already sized for the web: JPG or WEBP, no wider than about 1800 px, ideally under
  500 KB each. The dashboard does not shrink images for you.

CONTACT FORM
  Messages go to the email set in the dashboard (Welcome text, Contact info & Social links > last field)
  through the free FormSubmit service. If you ever change that email, send one test message from the
  live site and click the "Activate Form" button in the email FormSubmit sends to the new address.
