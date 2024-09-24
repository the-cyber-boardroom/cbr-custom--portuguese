FROM alpine:latest

RUN apk add --no-cache wget

WORKDIR /data

CMD ["wget", "--mirror", "--convert-links", "--adjust-extension", "--page-requisites", "--no-parent", "https://www.cyberclub.london/"]
