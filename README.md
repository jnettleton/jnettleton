## Jerry Nettleton

Systems engineer working in **Rust**, **networking** and **IoT/embedded**. Minnesota.

### Recent work
- **SmartThings, Staff Software Engineer (2021–2026)**
  - Designed and built the async Rust log shipper in the hub firmware: jittered backoff,
    severity-aware offline buffering, a remote per-hub log level, and batched upload.
    In production since January 2024, in the common hub codebase.
  - Java/Kotlin microservices on AWS across five regions, with Docker and Terraform.
- **Earlier:** C#/.NET since 2002, including consulting at Avanade.

### Currently building
- **An async Rust proxy.** Work in progress; the link and design notes go here once it's public.

### Projects
- [pi-workspace-rust](https://github.com/jnettleton/pi-workspace-rust): Rust driver for an SPI TFT display on a Raspberry Pi (`rppal`).
- [pi-workspace-cpp](https://github.com/jnettleton/pi-workspace-cpp): C++ on a Raspberry Pi with CMake presets, an aarch64 cross-toolchain and a Docker-based cross-build.

### Open source
- [Azure/azure-relay-bridge#32](https://github.com/Azure/azure-relay-bridge/pull/32) (merged, 2024):
  `ConfigureAwait(false)` across the relay's TCP/UDP forwarders, after hitting a deadlock
  under load testing; plus deterministic disposal in the bridge tests.

### Contact
[LinkedIn](https://www.linkedin.com/in/jnettleton)

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=jnettleton&count_private=true&show_icons=true&include_all_commits=true&theme=gotham)
