FROM alpine:3.9
RUN apk add ca-certificates
WORKDIR /app
COPY ../../outyet .

EXPOSE 8080

CMD ["./outyet"]