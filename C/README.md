# wasm-c
example for wasm in c


## Build

```bash
emsdk_env.bat
```

```
emcc dice-roll.c -s WASM=1 -O3 -o index.js
```

use [http-server](https://github.com/indexzero/http-server) to open

```bash
http-server .
```