Download and Installing Jenkins and Java
========================================
   1. I have downloaded Jenkins by using this URL "https://www.jenkins.io/download/"
   2. I have installed Java-JDK ensure that Jenkins should support java version.
   3. After that go to that particular jenkins directory and run command like Java -jar jenkins.war
   4. While running it will give some password take that password and login to jenkins and give username and password and remember that.

 Creating Of Freestyle Project
==============================
    I have created two jobs one is for pass and another one is for fail.
       Pass Freestyle Job
      ====================
       1. I have entered into Dashboard and clicked on New Item for creating Node(Freestyle Project) and saved it.
       2. I General tab I have given some description and seted periodically build option and i have given 
           echo commands in execute windows batch command.
       3. After that i applied and saved the changes.
       
      Fail Freestyle Job
      ==================
      1.same steps i have repeated as above but with some failed batch command so that it got failed

 Creating Github account
 ======================
 1. I have created github account with terralogic credentials.
 2. I have created one repository in that..

     Gitbash Operations
    =====================
    1.Go to that particular jobs directory and I have given:
            a)git init ===> To initialize .git folder
            b)git status ====> will show status of jobs if there are in red colour indicates that we need to add those files or folders
            c)git add . ==-=> added all folders means staged
            d)git commit -m "first commit" ====>commited with some message (all folders came into tracking stage)
            e)git remote add origin <github_https_code>(https://<token>/github.com/username/reposname.git)
            f)git push origin master ====>I have pushed my source code into master
    
          
