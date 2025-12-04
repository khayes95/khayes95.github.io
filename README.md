# Kevin David Hayes - Personal Academic Website

A clean, professional academic website based on [Jon Barron's template](https://github.com/jonbarron/jonbarron_website).

## 🚀 Quick Deployment to GitHub Pages

### Step 1: Create GitHub Repository

1. Go to [github.com](https://github.com) and sign in
2. Click the **+** icon → **New repository**
3. Name it: `yourusername.github.io` (replace `yourusername` with your actual GitHub username)
4. Make it **Public**
5. Click **Create repository**

### Step 2: Upload Your Files

**Option A: Using GitHub Web Interface (Easiest)**
1. In your new repo, click **Add file** → **Upload files**
2. Drag all files from this folder into the upload area
3. Click **Commit changes**

**Option B: Using Git (Command Line)**
```bash
cd /path/to/this/folder
git init
git add .
git commit -m "Initial website"
git remote add origin https://github.com/yourusername/yourusername.github.io.git
git push -u origin main
```

### Step 3: Enable GitHub Pages

1. Go to your repository **Settings**
2. Click **Pages** in the left sidebar
3. Under "Source", select **main** branch
4. Click **Save**
5. Wait 1-2 minutes, then visit `https://yourusername.github.io`

---

## 📁 File Structure

```
website/
├── index.html          # Main webpage
├── stylesheet.css      # Styling
├── images/             # Your photos and paper figures
│   └── kevin_hayes.jpg # Your profile photo (add this!)
└── data/
    └── KevinHayes-CV.pdf  # Your CV/resume (add this!)
```

## ✏️ Customization Checklist

### Before Publishing:

- [ ] **Add your profile photo**: Save as `images/kevin_hayes.jpg` (square, ~400x400px works well)
- [ ] **Add your CV**: Save as `data/KevinHayes-CV.pdf`
- [ ] **Update social links** in `index.html`:
  - Replace `YOUR_ID` in Google Scholar link
  - Replace `YOUR_HANDLE` in Twitter, LinkedIn, GitHub links
- [ ] **Add paper images**: Create simple figures for each paper (~160px wide)
  - `images/finegrain.png`
  - `images/knowledge_graph.png`
  - `images/propellant_void.png`
  - `images/microfluidics.png`
  - `images/energetics.png`
  - `images/aps_kg.png`
- [ ] **Add real paper links**: Replace `#` placeholders with actual URLs

### Optional Enhancements:

- Add a favicon: Replace `images/favicon.ico`
- Add more publications as they come out
- Update the bio text as your research evolves

---

## 🖼️ Paper Figure Tips

For paper thumbnails, you can:
1. Take a screenshot of a key figure from your paper
2. Resize to ~160px wide
3. Save as PNG with a descriptive filename

Tools: Preview (Mac), Paint (Windows), or any image editor.

---

## 💻 Local Preview (Optional)

To preview your site locally before deploying:

```bash
# If you have Python installed:
cd /path/to/website
python3 -m http.server 8000

# Then open http://localhost:8000 in your browser
```

---

## 🛠️ Setting Up Claude Code on Your Mac

Once your website is deployed, you might want Claude Code for future edits:

```bash
# Install Homebrew (if you don't have it)
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"

# Install Node.js
brew install node

# Install Claude Code
npm install -g @anthropic-ai/claude-code

# Login
claude login
```

Then you can edit your website by running `claude` in your terminal!

---

## 📧 Contact

Kevin David Hayes  
University of Maryland  
khayes1@umd.edu

---

*Template based on [Jon Barron's website](https://jonbarron.info/) • Free to use and modify*
