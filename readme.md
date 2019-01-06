# Docker image for jenkins with support of docker image built

https://hub.docker.com/r/jenkins/jenkins/
https://github.com/rancher/jenkins-rancher

# link
https://medium.com/@manav503/how-to-build-docker-images-inside-a-jenkins-container-d59944102f30 
https://getintodevops.com/blog/the-simple-way-to-run-docker-in-docker-for-ci

# docker file - install docker
docker version musth match docker installed in host
https://docs.docker.com/install/linux/docker-ce/debian/#install-docker-ce

# Build the image with below command

    docker build -t snecommerce/jenkins-docker:latest .

# login & push
    docker login
    docker push snecommerce/jenkins-docker

# TODO 
update to officiel https://hub.docker.com/r/jenkins/jenkins/

https://github.com/rancher/jenkins-master

https://rancher.com/drone-vs-jenkins/

https://rancher.com/docker-based-build-pipelines-part-1-continuous-integration-and-testing/
