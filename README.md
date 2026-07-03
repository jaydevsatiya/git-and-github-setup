# git-and-github-setup For All Laptop and Desktop
install git --> https://git-scm.com/install/windows <br>
Add Your Config into Git <br>
Open Git Bash Into Computer <br>
Paste Below CMD: <br>
git config --global --unset user.name <br>
git config -global --unset user.email <br>
git config --global user.name "jaydevsatiya" <br>
git config --global user.email "jaydevsatiya39@gmail.com" <br>
check your git config (paste below cmd into gitbash)
git config --list
Check your email and username in given output
create a project folder into computer (ex. News-Website)
join your folder with github
go to Github Website (login first)
Create a New Repo (check for new btn into dashboard - green color btn)
Give a Name to Repo (ex. News-Website)
Click botton --> create a Repo (green botton)
find the link that start with --> git remote add origin --> Copy that whole line
open your vs code --> open terminal (check the menu click the option terminal --> new terminal) --> first check last words (ex. /News-Website>)
paste the copy link(repo link) --> close the terminal
create files, edit files, delete files into your folder
open terminal and give below cmd one by one:
git add .
git commit -m "give a msg"
git push origin main (main --> branch name {check your working brach first and after tha t write the branch name})
repeat the cycle
edit files --> git add . --> git commit -m "give a msg" --> git push origin main --> edit files
