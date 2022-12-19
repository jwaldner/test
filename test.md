git remote set-url origin git@github.com:jwaldner/test.git

echo "# m_waldner_web" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/jwaldner/test.git
git push -u origin main


 