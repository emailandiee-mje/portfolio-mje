# Git & GitHub Setup Guide

## ⚠️ Current Status
Git is not currently installed on your system. Follow the steps below to set up Git and connect your portfolio to GitHub.

---

## 📦 Step 1: Install Git

1. **Visit Git Download Page**
   - Go to: https://git-scm.com/download/win
   - Download the Windows installer (latest version)

2. **Run the Installer**
   - Run `Git-[version]-64-bit.exe`
   - Use default settings (click "Next" through the installation)
   - When prompted for "Choosing the default editor for Git", select Visual Studio Code
   - Complete the installation

3. **Verify Installation**
   - Open PowerShell or Command Prompt
   - Run: `git --version`
   - Should display version number (e.g., "git version 2.42.0.windows.1")

---

## 🔧 Step 2: Configure Git

After Git is installed, open PowerShell and run:

```powershell
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
```

Replace with your actual name and email (preferably the email connected to your GitHub account).

---

## 🚀 Step 3: Connect Your Portfolio Repository

Navigate to your portfolio folder and run these commands:

```powershell
# Navigate to the portfolio directory
cd "c:\Users\might\OneDrive\Documents\_Portfolio"

# Initialize Git repository
git init

# Add all files
git add .

# Create initial commit
git commit -m "Initial commit: Portfolio website with dashboard showcase"

# Add remote repository
git remote add origin https://github.com/emailandiee-mje/portfolio-mje.git

# Rename branch to main (GitHub standard)
git branch -M main

# Push to GitHub
git push -u origin main
```

---

## 🔐 Step 4: GitHub Authentication

When pushing to GitHub, you'll be prompted for authentication. Two options:

### Option A: Personal Access Token (Recommended)
1. Go to GitHub.com → Settings → Developer settings → Personal access tokens
2. Click "Generate new token"
3. Select scopes: `repo`, `gist`, `read:user`
4. Copy the token
5. When Git prompts for password, paste the token

### Option B: GitHub CLI
1. Download GitHub CLI: https://cli.github.com/
2. Run: `gh auth login`
3. Follow the prompts to authenticate

---

## ✅ Step 5: Verify Remote Connection

```powershell
git remote -v
```

Should display:
```
origin  https://github.com/emailandiee-mje/portfolio-mje.git (fetch)
origin  https://github.com/emailandiee-mje/portfolio-mje.git (push)
```

---

## 📤 Step 6: Enable GitHub Pages

1. Go to: https://github.com/emailandiee-mje/portfolio-mje
2. Click **Settings** → **Pages**
3. Under "Source", select:
   - Branch: `main`
   - Folder: `/ (root)`
4. Click **Save**

Your portfolio will be live at:
`https://emailandiee-mje.github.io/portfolio-mje/`

---

## 🔄 Updating Your Portfolio

After making changes locally:

```powershell
# Check what changed
git status

# Add all changes
git add .

# Commit with a message
git commit -m "Update project descriptions and skills"

# Push to GitHub
git push origin main
```

GitHub Pages will automatically rebuild and deploy your changes!

---

## 🐛 Troubleshooting

### Error: "fatal: not a git repository"
- You're not in the correct directory
- Navigate to: `cd "c:\Users\might\OneDrive\Documents\_Portfolio"`

### Error: "Authentication failed"
- Check your Personal Access Token is correct
- Make sure token hasn't expired
- Try using GitHub CLI instead (`gh auth login`)

### Error: "remote origin already exists"
- Repository was already initialized
- Run: `git remote remove origin`
- Then: `git remote add origin [URL]`

### Changes not appearing on GitHub Pages
- Wait 1-2 minutes for deployment
- Check repository Settings → Pages to verify source branch
- Try force refresh browser (Ctrl+Shift+R)

---

## 📚 Useful Git Commands

```powershell
# View commit history
git log

# Check current status
git status

# See what changed
git diff

# Undo last commit (before push)
git reset --soft HEAD~1

# Create a new branch
git branch feature-name

# Switch branches
git checkout feature-name

# View all branches
git branch -a
```

---

## 🌐 Next Steps

1. ✅ Install Git
2. ✅ Configure user settings
3. ✅ Initialize repository
4. ✅ Push to GitHub
5. ✅ Enable GitHub Pages
6. ✅ Share your portfolio link!

---

**Need Help?**
- Git Documentation: https://git-scm.com/doc
- GitHub Guides: https://guides.github.com/
- GitHub Pages Help: https://docs.github.com/en/pages

