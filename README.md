# hello-world-go
hello-world in Golang

The image contains golang hello-world program. The image is created using "scratch" and hello-world go-program binary.

Step: 1
Build hello-world program.
go build hello-world.go

NOTE: remove hello-world.go after step:1, no problem to keep this file but your docker image size will increase.

Step:2
Build Docker Image using:
docker build --tag hello-world-go .

RUN: docker run hello-world-go
