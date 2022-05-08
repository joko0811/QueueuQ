FROM golang:1.18
RUN go mod download
WORKDIR /app
COPY . .
CMD ["go","run","cmd/main.go"]

