FROM jenkins/jenkins:lts
# if we want to install via apt
USER root
RUN git config --global http.sslverify false && apt-get update && apt-get install -y maven
