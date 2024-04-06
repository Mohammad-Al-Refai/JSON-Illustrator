# Flip book
Drawing frame by frame to make animations and convert them to gif file


<img src="https://github.com/Mohammad-Al-Refai/flip-book/assets/55941955/ef32dac3-dfd3-4707-92a5-3b3849b84c36" width="200"/>

## Using
- React js
- Typescript
- Webassembly
- Golang

## Screenshot

![image](https://github.com/Mohammad-Al-Refai/flip-book/assets/55941955/76d8e92d-58a3-409d-b5e3-67c717e0dfef)



## Compile to wasm
```
GOOS=js GOARCH=wasm go build -o main.wasm main.go & cp "main.wasm" ../frontend/public
```

### copy wasm_exec.js 

```
cp "$(go env GOROOT)/misc/wasm/wasm_exec.js" .
```