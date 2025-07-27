Push Code to GitHub — Step-by-Step Guide (Beginner Friendly)
✅ 1. Install Git (One-Time Setup)
🔹 Windows:
Download: https://git-scm.com/download/win

Install with default settings

Open Git Bash or Command Prompt and run:

css
Copy
Edit
git --version
🔹 macOS:
Open Terminal and run:

css
Copy
Edit
git --version
It will prompt to install Xcode tools (accept it).

🔹 Ubuntu/Linux:
bash
Copy
Edit
sudo apt update
sudo apt install git
⚙️ 2. Setup Git (One-Time)
bash
Copy
Edit
git config --global user.name "Your GitHub Username"
git config --global user.email "youremail@example.com"
✔️ Use the same email you used on GitHub.

📁 3. Prepare Your Project Folder
Open VS Code or Terminal and go to your project folder:

bash
Copy
Edit
cd path/to/your/project
If Git is not already initialized, run:

bash
Copy
Edit
git init
📌 4. Add & Commit Code
bash
Copy
Edit
git add .
git commit -m "Initial commit"
🌐 5. Create New Repository on GitHub
Go to: https://github.com/new

Enter repository name (same as your project or anything)

Keep it Public or Private

❌ Do NOT select “Initialize with README”

Click Create Repository

🔗 6. Link Local Folder with GitHub
Copy the URL GitHub shows (e.g. https://github.com/yourname/myproject.git)

Then run:

bash
Copy
Edit
git remote add origin https://github.com/yourusername/repo-name.git
git branch -M main
git push -u origin main
If prompted, login via browser or GitHub CLI.

🧠 Optional Commands
🔍 Check your Git config:
bash
Copy
Edit
git config --global user.name
git config --global user.email
✏️ Change Git user/email:
bash
Copy
Edit
git config --global user.name "NewName"
git config --global user.email "newemail@example.com"
✅ Done! Your Code is Live on GitHub 🎉
# Guide_To_Push_Code
