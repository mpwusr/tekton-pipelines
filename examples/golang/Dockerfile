FROM registry.access.redhat.com/ubi9/ubi-minimal:latest
WORKDIR /app
COPY dist/app /app/app
EXPOSE 8080
USER 65532:65532
ENTRYPOINT ["/app/app"]
