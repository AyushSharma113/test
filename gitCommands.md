# GitHub repository ko apne local machine me clone karne ke liye
git clone git@github.com:username/repo-name.git  

# Naya git repo initialize karne ke liye (agar project folder blank hai to)
git init  

# Working directory se saare changes staging area me daalne ke liye
git add .  

# Staging area ke changes ko local repo me commit karne ke liye
git commit -m "first commit"  

# Current branch ka naam "main" me rename karne ke liye (default pehle master hota hai)
git branch -M main  

# Apne local repo ko remote repo (GitHub) se connect karne ke liye
git remote add origin git@github.com:username/repo-name.git  

# Local repo ke commits ko GitHub (remote) pe bhejne ke liye aur future ke liye tracking set karne ke liye
git push -u origin main  
