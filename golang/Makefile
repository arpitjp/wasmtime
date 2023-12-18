wasm-build:
	GOOS=wasip1 GOARCH=wasm go build -o dist/main.wasm src/main.go

wasmtime: wasm-build
	wasmtime dist/main.wasm
