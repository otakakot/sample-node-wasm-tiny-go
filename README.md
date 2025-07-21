# sample-node-wasm-tiny-go

```shell
brew tap tinygo-org/tools
brew install tinygo
```

```shell
GOOS=js GOARCH=wasm tinygo build -o main.wasm ./main.go
```

```shell
node index.mjs
```
