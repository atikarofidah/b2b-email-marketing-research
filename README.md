# cursor-setup

## Tools Installed
- Cursor IDE
- Claude Code extension
- Codex extension
- Git

## Steps Completed
1. Installed Cursor IDE
2. Installed Claude Code and Codex extensions
3. Created a public GitHub repository
4. Connected GitHub with Cursor
5. Opened repository in Cursor
6. Edited README.md file

### 1. GitHub Authentication Confusion
**Issue:**  
During the process of connecting Cursor IDE with GitHub, I was confused by the authentication flow. The browser requested a device authorization code, but it was not immediately clear where to obtain that code.

**Solution:**  
I navigated back to Cursor IDE and triggered the login process using the Command Palette (Ctrl + Shift + P → "GitHub: Sign in"). This generated the required device code, which I then entered on GitHub to complete the authentication successfully.

---

### 2. "Clone Repository" Option Not Visible
**Issue:**  
Initially, I could not find the "Clone Repository" option in Cursor, which blocked me from opening my GitHub project.

**Solution:**  
I used the Command Palette (Ctrl + Shift + P) and manually searched for "Git: Clone". This allowed me to clone the repository using the GitHub URL and proceed with the setup.

---

### 3. Git Not Detected in Cursor
**Issue:**  
Some Git features were missing in Cursor, indicating that Git might not be properly installed or detected on my system.

**Solution:**  
I verified the installation using the terminal (`git --version`). After confirming or reinstalling Git, I restarted Cursor IDE, which enabled full Git functionality including clone, commit, and push.

---

### 4. Understanding Git Workflow (Commit & Push)
**Issue:**  
As a beginner, I needed to understand the difference between local changes (commit) and uploading them to GitHub (push).

**Solution:**  
I learned that committing saves changes locally, while pushing uploads them to the remote repository. After making changes to README.md, I committed with a message and pushed to GitHub successfully.

---

### 5. Initial Setup Overwhelm
**Issue:**  
Setting up multiple tools (Cursor, extensions, GitHub) at once felt overwhelming at the beginning.

**Solution:**  
I broke the process into smaller steps and followed official documentation and tutorials. This made the setup more manageable and helped me understand each component clearly.

## Notes
This project demonstrates basic setup and usage of AI-powered coding tools and GitHub workflow.