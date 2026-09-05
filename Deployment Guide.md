# A. RAMBABU - DIGITAL BIOLOGY HUB
## Deployment & Folder Structure Guide

This guide will help you package your website into a ZIP file or deploy it directly to GitHub Pages.

### 1. Folder Structure
Create a main folder on your computer named `Digital-Biology-Hub`. Inside it, create the following subfolders and place your `index.html` file in the root. 

Your final structure should look exactly like this:

```text
Digital-Biology-Hub/
│
├── index.html                 <-- (Save the code from the editor here)
│
├── videos/                    <-- (Place your .mp4 files here)
│   ├── placeholder.mp4
│   └── (add more videos here)
│
├── notes/                     <-- (Place your .pdf files here)
│   ├── nutrition.pdf
│   ├── respiration.pdf
│   ├── diagrams.pdf
│   └── excretion.pdf
│
└── images/                    <-- (For future custom images/thumbnails)
    └── (add images here)
```

### 2. Preparing the ZIP (For Local Sharing)
If you want to share the website offline with students:
1. Ensure all your `.mp4` and `.pdf` files are placed in their respective folders.
2. Right-click the `Digital-Biology-Hub` main folder.
3. Select **Compress to ZIP file** (Windows) or **Compress "Digital-Biology-Hub"** (Mac).
4. Share the resulting `.zip` file. Students can extract it and double-click `index.html` to run the site completely offline!

### 3. Deploying to GitHub Pages (Live Website)
To make your website available on the internet for free:

1. **Create a GitHub Account:** Go to [github.com](https://github.com/) and sign up.
2. **Create a New Repository:** * Click the **"+"** icon in the top right and select **New repository**.
   * Name it `digital-biology-hub`.
   * Keep it **Public** and click **Create repository**.
3. **Upload Your Files:**
   * On the next screen, click **"uploading an existing file"**.
   * Drag and drop your `index.html` file and your `videos`, `notes`, and `images` folders directly into the browser.
   * Click **Commit changes** at the bottom.
4. **Activate GitHub Pages:**
   * Go to the **Settings** tab of your repository.
   * On the left sidebar, click on **Pages**.
   * Under the "Build and deployment" section, find the **Branch** dropdown menu.
   * Change it from "None" to **main** (or **master**) and click **Save**.
5. **Your Website is Live!**
   * Wait about 1-2 minutes.
   * Refresh the Pages settings screen. You will see a message at the top saying: 
     _**"Your site is live at https://[your-username].github.io/digital-biology-hub/"**_
   * Share this link with your students!