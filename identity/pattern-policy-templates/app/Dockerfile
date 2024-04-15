FROM alpine:3.16.9

# Install jq and curl
RUN apk add --no-cache jq curl

ADD vault-init /vault-init
ENTRYPOINT ["/vault-init"]

