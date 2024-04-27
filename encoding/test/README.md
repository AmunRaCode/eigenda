# Reed Solomon Encoding with Elliptic Curve Points

- This library performs **Reed Solomon Encoding** using elliptic curve points and enables KZG multi-proof and reveal operations in \( O(n \log n) \) time using Fast Fourier Transform (FFT), based on the FK20 algorithm.

- Built upon cryptographic primitives from [go-kzg](https://pkg.go.dev/github.com/protolambda/go-kzg), it supports a flexible number of systematic nodes, parity nodes, and arbitrary data sizes without restrictions related to powers of two.
