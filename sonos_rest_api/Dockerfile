FROM chrisns/docker-node-sonos-http-api
# ENV LANG C.UTF-8

# # Copy data for add-on
# COPY run.sh /
# RUN chmod a+x /run.sh
USER root
RUN rm -rf /app/presets
RUN ln -sf /config/sonos_rest_api/presets /app/presets
USER node

# CMD [ "/run.sh" ]
