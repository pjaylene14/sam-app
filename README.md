# sam-app
CI/CD repository
cd ~/environment/sam-app
git init -b main
echo -e "\n\n.aws-sam" >> .gitignore
git add .
git commit -m "Initial commit"
git remote add origin https://github.com/pjaylene14/sam-app.git
git push -u origin main
