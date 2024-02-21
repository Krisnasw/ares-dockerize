FROM sonarqube:community

ENV SONAR_JDBC_URL=jdbc:postgresql://db:5432/sonar
ENV SONAR_JDBC_USERNAME=sonar
ENV SONAR_JDBC_PASSWORD=sonar

COPY plugins/ /opt/sonarqube/extensions/plugins/

VOLUME /opt/sonarqube/data
VOLUME /opt/sonarqube/extensions
VOLUME /opt/sonarqube/logs

EXPOSE 9000