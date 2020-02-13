FROM jboss/base-jdk:8

ENV JAVA_HOME opt/jboss/jboss-eap

COPY apache-maven-3.6.3 /opt/maven
RUN export M2_HOME=/opt/maven
RUN export M2=$M2_HOME/bin
RUN export PATH=$M2:$PATH

COPY driverJDBC.sh /op
COPY BundlesTerceros.sh /opt
COPY atomikos.sh /opt
