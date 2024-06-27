# Sol-types

用来使用 rust 类型来表示 ABI 中的各种类型。

## File

- src/types/ty.rs: SolType trait 用来表示 rust 里的 solidity 类型
- src/abi/token.rs: Tokens are an intermediate state between ABI-encoded blobs, and Rust types.
- src/abi/encoder.rs: token 如何编码成二进制表示
