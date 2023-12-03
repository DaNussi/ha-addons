# https://developers.home-assistant.io/docs/add-ons/configuration#add-on-dockerfile
FROM openjdk:17-oracle

COPY rootfs /

RUN chmod a+x /run.sh

CMD [ "/run.sh" ]