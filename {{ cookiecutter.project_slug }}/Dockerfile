FROM alpine:3.18.3

LABEL maintainer="{{ cookiecutter.full_name }} <{{ cookiecutter.email }}>"

RUN apk add bash

COPY entrypoint.sh /entrypoint.sh
RUN chmod +x /entrypoint.sh
ENTRYPOINT ["/entrypoint.sh"]
