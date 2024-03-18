# Noir Scroll Demo

This demo showcases Noir.js WASM support running on a Scroll Sepolia Testnet verifier.
The demo consists of proving that `X != Y` without revealing `X`.

Also check out the [live demo](https://funny-pasca-841f19.netlify.app/), blog article on [English](https://dev.to/filosofiacodigoen/aztec-noir-scroll-zk-development-made-easy-249f) and [Spanish](https://dev.to/turupawn/aztec-noir-scroll-crea-zk-dapps-facil-40jg), and Noir official documentation.

## How to run 🚀

### Load the website

Install the dependencies:

```bash
cd webapp
npm install
```

Launch the server:
```bash
npm start
```

The server should load at `http://localhost:5173/`.

### Read the state proof

```bash
cd storage_proofs
npm install
node main.js
```