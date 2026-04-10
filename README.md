# Tumult RPC 

![License](https://img.shields.io/badge/license-GPLv3-blue.svg)
![Rust](https://img.shields.io/badge/rust-1.75%2B-orange.svg)
![Platform](https://img.shields.io/badge/platform-windows%20%7C%20linux%20%7C%20macos-lightgrey.svg)
![Status](https://img.shields.io/badge/status-stable-green.svg)

**Tumult RPC** is a high-performance implementation of [arRPC](https://github.com/OpenAsar/arrpc) written in Rust. It provides a Discord Rich Presence server with significantly lower resource usage, faster process detection, and dual protocol support.

## 📊 Comparison vs arRPC

| Feature | arRPC (Node.js) | rsrpc (Rust) |
|---------|-----------------|--------------|
| **Memory Usage** | 10GB. | 10MB |
| **Executable Size** | ~125MB (when bundled with Bun) | ~3 MB (Standalone, Windows) |
| **Process Scan** | `powershell` + `wmic` | `sysinfo` |
| **Protocols** | JSON | JSON + MessagePack |

## 📜 License

GPLv3 License. See [LICENSE](LICENSE) for details.
