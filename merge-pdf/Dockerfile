FROM ubuntu:jammy
RUN apt-get update -y && \
apt-get install -y poppler-utils && \
rm -rf /var/lib/apt/lists/*
WORKDIR /pdf
ENTRYPOINT [ "pdfunite" ]