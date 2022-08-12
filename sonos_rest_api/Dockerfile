FROM chrisns/docker-node-sonos-http-api
USER root
RUN rm -rf /app/presets
RUN ln -sf /config/sonos_rest_api/presets /app/presets
USER node

