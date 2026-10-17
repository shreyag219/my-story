# Beyond the Code — My Story
### iLEAD 2027 | Build Your Story Challenge

A personal storytelling website crafted for the **iLEAD 2027 Build Your Story** challenge by **Shreya G.**, a Computer Science Engineering student.

---

## 🌟 Philosophy & Vision

> *"I believe that growth does not come from instant perfection. It comes from curiosity, consistency, creativity, and learning from mistakes."*
> 
> *"I'm still becoming. And that's the exciting part."*

This website is designed with an editorial, futuristic aesthetic featuring subtle purple and cyan gradients, dark-mode cosmic tones, generative canvas constellation visuals, responsive navigation, and micro-interactions.

---

## 📁 Project Structure

```
Beyond the Code — My Story/
├── index.html       # Semantic HTML5 storytelling document
├── style.css        # Editorial styling, glassmorphism, responsive media queries
├── script.js        # Interactive canvas, scroll tracking, tabs & navigation
└── README.md        # Local execution and GitHub Pages deployment guide
```

---

## 🚀 How to Run the Website Locally

You have multiple easy ways to view the website on your computer:

### Option 1: Direct File Open (Easiest)
1. Open this folder in your File Explorer (`c:\Users\Shreya G\Desktop\Beyond the Code — My Story`).
2. Double-click **`index.html`** to open it directly in your favorite browser (Chrome, Edge, Firefox, Brave, etc.).

### Option 2: Local Python Server (Recommended for True HTTP Simulation)
1. Open a terminal or PowerShell in this folder:
   ```powershell
   cd "c:\Users\Shreya G\Desktop\Beyond the Code — My Story"
   ```
2. Start Python's built-in lightweight web server:
   ```bash
   python -m http.server 8000
   ```
3. Open your browser and navigate to:
   ```
   http://localhost:8000
   ```

### Option 3: VS Code / Cursor "Live Server"
If you use VS Code:
1. Open this folder in VS Code.
2. Install the **Live Server** extension (by Ritwick Dey).
3. Right-click `index.html` and click **"Open with Live Server"**.

---

## 🌐 How to Publish to GitHub Pages (Free Hosting)

Publishing your website to GitHub Pages gives you a free, public URL that you can share with the iLEAD evaluators, mentors, and on your profiles.

### Step 1: Create a GitHub Repository
1. Log in to [GitHub](https://github.com/).
2. Click the **+** (plus icon) in the top right corner and choose **New repository**.
3. Name your repository (e.g., `beyond-the-code` or `my-story`).
4. Set it to **Public**.
5. Leave "Add a README file" unchecked (since we already have one).
6. Click **Create repository**.

### Step 2: Initialize Git and Push Your Files
Open PowerShell in your project directory and run the following commands:

```powershell
# 1. Initialize git in this folder
git init

# 2. Add all files to staging
git add .

# 3. Create your initial commit
git commit -m "Initial release: Beyond the Code — My Story for iLEAD 2027"

# 4. Set the main branch
git branch -M main

# 5. Connect to your new GitHub repository (replace with your actual repository URL)
git remote add origin https://github.com/YOUR_GITHUB_USERNAME/YOUR_REPOSITORY_NAME.git

# 6. Push your code to GitHub
git push -u origin main
```

*(Note: If you haven't configured your Git credentials on this PC yet, run `git config --global user.name "Your Name"` and `git config --global user.email "your.email@example.com"` before committing).*

### Step 3: Enable GitHub Pages
1. Go to your repository on GitHub.
2. Click **Settings** (tab with the gear icon near the top right).
3. In the left sidebar, click **Pages** (under the "Code and automation" section).
4. Under **Build and deployment**:
   - **Source**: Select `Deploy from a branch`.
   - **Branch**: Select `main` from the dropdown, and leave the folder as `/ (root)`.
5. Click **Save**.

### Step 4: Access Your Live Website
- In about 1 to 2 minutes, GitHub will build and publish your site.
- Refresh the **Pages** settings page, and you will see a banner:
  > *"Your site is live at `https://<your-username>.github.io/<your-repo-name>/`"*
- Click the link to test your live website!

---

## 🛠️ Highlights of the Build

- **Interactive Constellation Canvas**: Ambient particle simulation responding to cursor movement with dynamic proximity connections.
- **Micro-Interactions**: Custom tabbed deep-dive in "What Excites Me", 3D card tilt effects, and reading progress indicator.
- **Performance & Battery Optimized**: The background canvas uses `IntersectionObserver` to automatically pause rendering when scrolled out of view.
- **Accessibility & Contrast**: Built with accessible typography hierarchies, semantic HTML5 tags, ARIA labels, and WCAG AA contrast compliance.
- **Zero Heavy Dependencies**: Pure HTML5, modern CSS3, and clean vanilla JavaScript.
