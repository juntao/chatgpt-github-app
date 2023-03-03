# chatgpt-github-app

Deploy this function on [flows.network](https://flows.network) and you will get a ChatGPT bot that responds to every issue comment.

See a live demo [here](https://github.com/second-state/chat-with-chatgpt/)

Powered by `gpt-3.5-turbo`, Rust and [WasmEdge](https://github.com/WasmEdge/WasmEdge)

### Build locally

```
cargo build --target wasm32-wasi --release
```
