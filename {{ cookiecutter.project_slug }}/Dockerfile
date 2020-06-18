FROM alpine:3.12

LABEL maintainer="{{ cookiecutter.full_name }} <{{ cookiecutter.email }}>"

COPY entrypoint.sh /entrypoint.sh
RUN chmod +x /entrypoint.sh
ENTRYPOINT ["/entrypoint.sh"]
