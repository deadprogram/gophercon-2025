
```
go build -o hello-biggo-1.25 -ldflags="-s -w" ./src/examples/hello/
tinygo build -o hello-tinygo-0.39 -gc=leaking -scheduler=none ./src/examples/hello/
```

```
GOOS=wasip1 GOARCH=wasm go build -o hello-wasi-biggo-1.25 -ldflags="-s -w" ./src/examples/hello-wasi/
tinygo build -o hello-wasi-tinygo-0.39 -gc=leaking -scheduler=none -no-debug target wasip1 ./src/examples/hello-wasi/
```
