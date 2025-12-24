# gRPC Connect Example

Accesses a gRPC endpoint from a browser using the Connect protocol.

- Based on [Connect for Web – Getting Started](https://connectrpc.com/docs/web/getting-started)
- Protobuf definition: [Eliza](https://github.com/connectrpc/examples-go/blob/main/proto/connectrpc/eliza/v1/eliza.proto)
- Transport created using createConnectTransport()
- Connect RPC protocol doesn't require a proxy to connect to the service as required for the gRPC-web protocol

![Screenshot](assets/screenshot.png)

## Getting Started

```shell
pnpm i
pnpm dev
```

Now point your browser to http://localhost:3000

## Code generation from Eliza protobuf

```shell
pnpm codegen
```