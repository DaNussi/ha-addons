# https://developers.home-assistant.io/docs/add-ons/configuration#add-on-dockerfile
FROM openjdk:17-oracle

COPY rootfs /

WORKDIR /opt/app
RUN chmod a+x run.sh

CMD [ "/bin/bash","run.sh" ]