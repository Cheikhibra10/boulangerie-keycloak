FROM quay.io/keycloak/keycloak:26.7.0

ENV KC_DB=postgres
ENV KC_CACHE=local

RUN /opt/keycloak/bin/kc.sh build

ENTRYPOINT ["/opt/keycloak/bin/kc.sh"]