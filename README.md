# golang-examples

## initial project
    go mod init project

## example how install package
    go get github.com/urfave/cli

## run program
    go run main.go

## compile
    go build

# go test - examples

## test all packages

    go test ./...
## shows all functions

    go test -v
## shows test coverage

    go test --cover

## shows test coverage - generate file

    go test --coverprofile cobertura.txt

## check functions that are covered

    go test --cover --func=cobertura.txt

## check functions that are not covered

    go test --cover --html=cobertura.txt
