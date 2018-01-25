FROM jenkins/jenkins:lts

# COPY https.pem /var/lib/jenkins/cert
# COPY https.key /var/lib/jenkins/pk
VOLUME ["/var/jenkins_home","/var/log/jenkins"]
# ENV JENKINS_OPTS --logfile=/var/log/jenkins/jenkins.log

EXPOSE 8080
EXPOSE 50000