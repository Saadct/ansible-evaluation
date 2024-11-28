FROM gitlab/gitlab-ce:latest

ENV GITLAB_HOME /var/opt/gitlab
ENV GITLAB_VERSION 15.0.0-ce.0

EXPOSE 80 443 22

CMD ["gitlab-ctl", "reconfigure"]
