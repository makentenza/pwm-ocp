FROM tomcat:9-jre10-slim

MAINTAINER Marcos Entenza <mak@redhat.com>

LABEL io.k8s.description="PWM open source password self service" \
      io.k8s.display-name="PWM password self service" \
      io.openshift.expose-services="8080:tcp" \
      io.openshift.tags="pwm"

RUN mkdir -p /media/pwm/

ADD src ${CATALINA_HOME}/webapps/