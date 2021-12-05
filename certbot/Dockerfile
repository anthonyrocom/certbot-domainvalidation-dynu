FROM certbot/certbot:arm64v8-latest

RUN apk update \
 && apk add jq curl bash\
 && rm -rf /var/cache/apk/*
