FROM alpine
RUN apk --no-cache add bash curl jq wget groff less python py-pip &&\
  pip install awscli &&\
  apk --purge -v del py-pip
CMD tail -f /dev/null

