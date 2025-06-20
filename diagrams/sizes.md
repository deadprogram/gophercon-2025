# Sizes

https://mermaid.js.org/syntax/xyChart.html


```mermaid
xychart-beta
    title "hello.go (GOARCH=amd64 GOOS=linux)"
    x-axis [tinygo0.38.0, go1.22.4]
    y-axis "Size (in bytes)" 0 --> 1100000
    bar [13968, 1007800]
```

```mermaid
xychart-beta
    title "hello-wasi.go (GOARCH=wasm GOOS=wasip1)"
    x-axis [tinygo0.38.0, go1.22.4]
    y-axis "Size (in bytes)" 0 --> 2600000
    bar [80388, 2540172]
```
