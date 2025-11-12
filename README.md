# Fetch any existing content (like README) from GitHub
git fetch origin main

# Merge the remote branch with your local one safely
git pull origin main --allow-unrelated-histories

# Add all your local Android Studio project files
git add .

# Commit your files with a clear message
git commit -m "Merged remote and added full DogApiResponse Android project"

# Push everything to GitHub
git push -u origin main

# DogApiResponse
DogApiResponse pROJECT
