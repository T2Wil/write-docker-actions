
# Action Dockerfile

FROM golang:latest
WORKDIR /go/src/hello
COPY . .
RUN go get -d -v ./...
RUN go install -v ./...
CMD ["hello"]
