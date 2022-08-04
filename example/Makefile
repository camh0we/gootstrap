mod-init:
	go mod init github.com/camh0we/example

mod-tidy:
	go mod tidy
	
build:
	go build -o bin/example github.com/camh0we/example/cmd/example

install:
	go install -i github.com/camh0we/example/cmd/example

run-only:
	bin/example

run: build run-only

test:
	go test github.com/camh0we/example/...

testv:
	go test -v github.com/camh0we/example/...

testc:
	go test -race -coverprofile=coverage.txt -covermode=atomic github.com/camh0we/example/...