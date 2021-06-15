FROM alpine:3.14.0

LABEL maintainer="{{ cookiecutter.full_name }} <{{ cookiecutter.email }}>"

RUN apk add bash

COPY entrypoint.sh /entrypoint.sh
RUN chmod +x /entrypoint.sh
ENTRYPOINT ["/entrypoint.sh"]
