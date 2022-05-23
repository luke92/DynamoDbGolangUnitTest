# DynamoDbGolangUnitTest
Project using Unit Test in Golang with DynamoDB

# Requisites
Dynamock
- https://github.com/gusaul/go-dynamock

## How to create project
- Run `go mod init github.com/luke92/DynamoDbGolangUnitTest`
- Run `go get github.com/gusaul/go-dynamock`
- Create `main.go`

## How to run tests
- https://ieftimov.com/posts/testing-in-go-go-test/
- Run `go test` (The first way to control test runs is by supplying the test files as arguments to the `go test`)
- Run `go test -v` (If we would like to see a more detailed output, we can use the `-v` flag:)
- Run `go test -v -run TestGetTransactGetItems` (The third way to run tests is by specifying a test function to be run, using the `-run` flag)
- Run `go test -cover` (For get coverage `-cover`)
- Run `go test -v -failfast` (`-failfast` it will stop at the first test that fails, aborting the running test suite/files)
- Run `go test -coverprofile=prof.out` (`-coverprofile` To see where our problem is)
- Run `go tool cover -html=hundred.out` (After run `-coverprofile` to view in an HTML what part of code is covered)