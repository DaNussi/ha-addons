# https://developers.home-assistant.io/docs/add-ons/configuration#add-on-dockerfile
FROM openjdk:17-oracle

COPY rootfs/app /app

RUN chmod a+x /app/run.sh

CMD [ "/app/run.sh" ]