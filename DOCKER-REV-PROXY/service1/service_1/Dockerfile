# Build the Go app
FROM golang:1.20-alpine AS builder

WORKDIR /app
COPY . .

RUN go build -o service1

# Final minimal image
FROM alpine:latest

WORKDIR /app
COPY --from=builder /app/service1 .

EXPOSE 8080

CMD ["./service1"]
