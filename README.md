# Classification-Deployment-Heroku

# Steps we are following to deploy our app on Heroku
    Step1: our main file name should be app.py
    Step2: Our Flask Instance name should be app
                app:app
    Step3: Create a new file and name it as Procfile
            Note: Procfile should not have any extension like .txt
                  P should be capital case

    Step4: In Procfile we are supposed to mention the commands which will be used by the cloud instance at the time of deployment
    Step5: heroku login	hit enter on git bash command prompt.

# Initialising the local GIT
    Step5: git init
    Step6: git add .
    Step7: git commit -m "Initial commit"

# Steps to Push Your Application from Local to Heroku Cloud
    Step8: heroku login
    Step9: heroku create
    Step10: git remote -v
    Step11: git push origin master
