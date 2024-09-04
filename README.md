# Navigate to your script directory
cd ~/scripts

# Initialize git repository if not done already
git init

# Add remote repository
git remote add origin https://github.com/yourusername/laxsus-99.git

# Add files to the repository
git add laxsus-99.py
git add README.md

# Commit the files
git commit -m "Initial commit"

# Push files to GitHub
git push -u origin master
