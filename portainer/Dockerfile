FROM portainer/portainer:latest
COPY portainer.crt /certs/
COPY portainer.key /certs/
HEALTHCHECK --interval=5m --timeout=3s CMD curl -f http://localhost:9000 || exit 1
CMD ["--ssl", "--sslcert", "/certs/portainer.crt", "--sslkey", "/certs/portainer.key"]