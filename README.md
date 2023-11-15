## wsl2

### rust

```shell
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
source "$HOME/.cargo/env"
```

### WebAssembly wasm-pack

```shell
curl https://rustwasm.github.io/wasm-pack/installer/init.sh -sSf | sh
```

### bun

```shell
curl -fsSL https://bun.sh/install | bash
```

## Build the Project Rust

```shell
wasm-pack build
```
