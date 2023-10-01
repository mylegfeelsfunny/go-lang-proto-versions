BUF_VERSION:=v1.17.0

generate: generate/proto

generate/proto:
	go run github.com/bufbuild/buf/cmd/buf@$(BUF_VERSION) generate

lint-list:
	gofmt -l .

lint-fix:
	gofmt -w .
