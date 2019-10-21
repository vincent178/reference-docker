FROM golang:1.13

WORKDIR /src

COPY . .

RUN go build -o test

CMD ["test"]
