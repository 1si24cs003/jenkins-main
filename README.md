git init

git add .

git remote add origin https://github.com/1si24cs003/jenkins-main.git

git branch -M main

git commit -m "Initial commit"

git push -u origin main

-----------------------------------------
Q7. Jenkins + Maven + GitHub
Steps

Install Jenkins

Install Git & Maven plugins

Create Maven Job

GitHub repo URL

H/2 * * * *

Build Goal:

clean package


✔ .jar generated in workspace/target

✔ Enable GitHub webhook
✔ Every push triggers build

Q8. Jenkins Nightly Build (2 AM)

0 2 * * *


✔ Runs every night at 2 AM
✔ Also enable GitHub hook trigger
