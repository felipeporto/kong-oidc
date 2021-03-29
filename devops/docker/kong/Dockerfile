FROM kong:2.3-alpine

LABEL description="Linux Alpine + Kong 2.3 + kong-oidc plugin"

USER root

RUN luarocks install kong-oidc
RUN export KONG_PLUGINS=oidc

USER kong