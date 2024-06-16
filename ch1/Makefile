.DEFAULT_GOAL := build

.PHONY:fmt vet build
fmt:
		go fmt ./...

vet: fmt
		go vet ./...

build: fmt
		go build

clean:
		go clean ./...