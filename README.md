 One-Time Setup for a New Repo

 # Step into your project directory
cd myproject

# Initialize Git (only once per project)
git init

# Add all files to staging area
git add .

# Commit the files
git commit -m "Initial commit"

# Add your GitHub repo URL (replace with yours)
git remote add origin https://github.com/your-username/your-repo.git

# Rename default branch to main (optional but recommended)
git branch -M main

# Push to GitHub
git push -u origin main



2. Regular Workflow for Updates
 # Stage updated files
git add .

# Commit with a message
git commit -m "Updated files"

# Push changes to GitHub
git push
