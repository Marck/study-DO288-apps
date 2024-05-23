FROM quay.io/jkube/jkube-java-binary-s2i:0.0.9
ENV JAVA_APP_DIR=/deployments JAVA_OPTIONS=-Dquarkus.http.host=0.0.0.0
LABEL org.label-schema.description="" org.label-schema.version=1.0 org.label-schema.schema-version=1.0 org.label-schema.build-date=2024-05-23T14:52:19.473108 org.label-schema.name=micro-java org.label-schema.vcs-ref=fea8daa858b4f8b33802fab9a6bd2a8fb92d991d org.label-schema.vcs-url=https://github.com/Marck/study-DO288-apps.git
EXPOSE 8080 8778 9779
COPY /deployments /deployments/
WORKDIR /deployments
