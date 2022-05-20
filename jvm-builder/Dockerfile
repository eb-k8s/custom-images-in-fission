FROM fission/jvm-builder
RUN rm usr/share/maven/conf/settings.xml
COPY --chown=501:dialout settings.xml /usr/share/maven/conf/settings.xml