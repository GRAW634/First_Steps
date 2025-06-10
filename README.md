mkdir First_Steps 
cd First_Steps 
git init
echo "# My First CI/CD Project" &gt; README.mdgit add README.md
git commit -m "Initial commit"
git temote add origin https://github.com/GRAW634/First_Steps.git
git push -u origin main
