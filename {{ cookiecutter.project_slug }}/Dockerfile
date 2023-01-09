FROM alpine:3.17.1

LABEL maintainer="{{ cookiecutter.full_name }} <{{ cookiecutter.email }}>"

RUN apk add bash

COPY entrypoint.sh /entrypoint.sh
RUN chmod +x /entrypoint.sh
ENTRYPOINT ["/entrypoint.sh"]
