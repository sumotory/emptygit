(created third.txt)
git init
git add .
git commit -m "adding third.txt"
git log 
(created fourth.txt)
git add fourth.txt
git commit -m "adding fourth.txt"
git log
(removed third.txt)
git add .
git commit -m "removing third.txt"
git log
git remote add origin https://github.com/sumotory/emptygit.git
git push -u origin main
