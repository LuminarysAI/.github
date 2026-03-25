# Luminarys AI

Next-generation AI platform that combines an autonomous agent and an MCP server with sandboxed WebAssembly skill execution.

Write skills in any language. Run them in isolated WASM sandboxes. Expose via MCP or let the agent orchestrate autonomously.

## Repositories

| Repository | Description |
|------------|-------------|
| [luminarys](https://github.com/LuminarysAI/luminarys) | Host runtime, `lmsk` skill toolchain, releases |
| [skill-examples](https://github.com/LuminarysAI/skill-examples) | Example skills in AssemblyScript, Go, and Rust |
| [mcp-demo-cluster](https://github.com/LuminarysAI/mcp-demo-cluster) | Multi-node cluster demo with Docker Compose | 
| [sdk-as](https://github.com/LuminarysAI/sdk-as) | AssemblyScript SDK ([@luminarys/sdk-as](https://www.npmjs.com/package/@luminarys/sdk-as)) |
| [sdk-go](https://github.com/LuminarysAI/sdk-go) | Go SDK |
| [sdk-rust](https://github.com/LuminarysAI/sdk-rust) | Rust SDK ([luminarys-sdk](https://crates.io/crates/luminarys-sdk)) |

## Quick Start

```bash
# Download and run
curl -sL https://github.com/LuminarysAI/luminarys/releases/latest/download/luminarys-linux-amd64.tar.gz | tar xz
./luminarys
# MCP endpoint: http://localhost:8080/mcp
```

[Documentation](https://luminarys.ai)
