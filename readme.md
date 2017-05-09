

https://www.docker.com/sites/default/files/UseCase/RA_CI%20with%20Docker_08.25.2015.pdf
https://www.docker.com/use-cases/cicd


jenkins git plugin
https://wiki.jenkins-ci.org/display/JENKINS/Git+Plugin



* Install Bitbucket Plugin at your Jenkins
https://wiki.jenkins-ci.org/display/JENKINS/BitBucket+Plugin

* add webhook to bitbucket repo
https://confluence.atlassian.com/bitbucket/manage-webhooks-735643732.html

http://vps365425.ovh.net:8080/bitbucket-hook/
http://citizendiop:mySNEjenkins123@vps365425.ovh.net:8080/bitbucket-hook/


* Configure your Jenkins project as follows:
under "build trigger" enable "Build when a change is pushed to BitBucket"
under Source Code Management select GIT; enter your credentials and define Branches to build (like **feature/*)

* 
By this way we have three build projects :  one for all features, one for develop and one for release branch.