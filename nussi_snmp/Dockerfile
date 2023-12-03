# https://developers.home-assistant.io/docs/add-ons/configuration#add-on-dockerfile
FROM openjdk:17-oracle

COPY rootfs /

RUN chmod a+x /opt/app/run.sh

CMD [ "/bin/bash","/opt/app/run.sh" ]