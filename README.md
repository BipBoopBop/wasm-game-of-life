<div align="center">

  <h1><code>wasm-game-of-life</code></h1>

<strong><a href="https://en.wikipedia.org/wiki/Conway%27s_Game_of_Life">Conway's Game of Life</a> implementation using Rust, Javascript and WebAssembly. Started from wasm-pack-template : a template for kick starting a Rust and WebAssembly project using <a href="https://github.com/rustwasm/wasm-pack">wasm-pack</a>.</strong>

</div>

## Run

Build the webassembly module with `wasm-pack build`

```
wasm-pack build
```

start the webserver with `npm run start`

```
cd www
npm run start
```

Open the webpage at http://localhost:8080