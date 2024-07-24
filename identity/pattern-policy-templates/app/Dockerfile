FROM alpine:3.19

# Install jq and curl
RUN apk add --no-cache jq curl

ADD vault-init /vault-init
ENTRYPOINT ["/vault-init"]

