#Git_Dwmo
#create a new repository on the command line
echo "# Git_Demo" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/rajendra8/Git_Demo.git
git push -u origin main
