FROM alpine:3.14

ENTRYPOINT ["sh"]
ENV HOME "/home/user"
WORKDIR "${HOME}"

RUN apk add python3 py3-pip
COPY PillHelper "${HOME}/"
RUN sh "build.sh"
