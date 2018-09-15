#docker run -it -d -p 80:8080 -p 50000:50000 -v /var/jenkins_home:/var/jenkins_home:z --name=jenkins {name of this image build}
FROM jenkins/jenkins:lts
LABEL maintaine=earaujo@jpl.nasa.gov
USER root
RUN apt-get -y update && apt-get -y upgrade
