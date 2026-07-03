# GIT-AND-GITHUB-setup all laptop and desktop
1.install git -->https://git-scm.com/install/windows<br>
2.add your confing into git<br>
3.open git bash into computer<br>
4.paste below CMD: <br>
git config --global --unset user.name<br>
git config --global --unset user.email<br>
git config --global user.name "devang01-ninja"<br>
git config --global user.email "devangajudia01@gmail.com"<br>
5.check your git config (paste below cmd into gitbash)<br>
git config --list <br>
6. check your email and username in given output <br>
7.create a project folder into computer (ex. news-website)<br>
8.join your folder with github <br>
9.go to github website (login first)<br>
10.give a new repo (check for new btn into dashboard - green btn)<br>
11.give a name to repo (ex. newa-website)<br>
12.click botton --> create a repo (green botton)<br>
13.find the link that start with -->git remote add origin --> copy that whole line <br>
14.open your va code --> open terminal (check the menu click the option terminal -->new terminal) --> first check last words (ex. /news-website) <br>
15.paste the copy link(repo link) --> close the terminal<br>
16.create files, edit files, delete files into your folder<br>
17.open terminal and give below cmd one by one:<br>
git add .<br>
git commit -m "give a msg"<br>
git push origin main (main --> branch name {check your working brach first and after tha t write the branch name})<br>
18.repeat the cycle<br>
edit files --> git add . --> git commit -m "give a msg" --> git push origin main --> edit files<br>
