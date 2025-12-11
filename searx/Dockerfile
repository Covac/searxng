FROM searxng/searxng:latest
ENV SEARXNG_REDIS_URL=""
COPY settings.yml /etc/searxng/settings.yml
RUN mkdir -p /var/cache/searxng && chown -R searxng:searxng /var/cache/searxng
EXPOSE 8080
