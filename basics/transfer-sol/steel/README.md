# Transfer Sol

Simple example of a Solana program that transfers SOL between accounts.

For more information, see this [README](../README.md).

## Building

```sh
cargo build-sbf

```
## Tests

This project includes both:
- Rust tests: [`program/tests`](/program/tests) directory.
- Node.js tests using [Bankrun](https://kevinheavey.github.io/solana-bankrun/): [`tests`](/tests) directory.

```sh
# rust tests
cargo test-sbf 

# node tests
pnpm build-and-test # this will also build the program
#or 
pnpm test # if you have already built the program
```