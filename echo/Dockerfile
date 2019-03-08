FROM alpine:latest

LABEL version="0.1.0"
LABEL repository="http://github.com/sbstjn/actions"
LABEL homepage="http://github.com/sbstjn/actions"
LABEL maintainer="Sebastian Müller <mail@sbstjn.com>"

LABEL com.github.actions.name="GitHub Action to print messages"
LABEL com.github.actions.description="Wraps a simple bash echo command."
LABEL com.github.actions.icon="package"
LABEL com.github.actions.color="purple"

RUN apk add --no-cache bash

COPY "entrypoint.sh" "/entrypoint.sh"
ENTRYPOINT ["/entrypoint.sh"]