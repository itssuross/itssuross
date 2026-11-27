<h1 align="center">Uroš</h1>

<p align="center"><strong>Rust, Swift, and Assembly. Bare-metal kernels, native macOS apps, and systems tooling.</strong></p>

<p align="center">
  <img alt="Rust" src="https://img.shields.io/badge/Rust-8C3822?style=for-the-badge&amp;logo=rust&amp;logoColor=white">
  <img alt="Swift" src="https://img.shields.io/badge/Swift-F05138?style=for-the-badge&amp;logo=swift&amp;logoColor=white">
  <img alt="Assembly" src="https://img.shields.io/badge/Assembly-252525?style=for-the-badge&amp;logoColor=white">
</p>

<p align="center">
  <a href="#what-i-build">What I build</a> ·
  <a href="#featured">Featured</a> ·
  <a href="#stack">Stack</a> ·
  <a href="#open-source">Open source</a> ·
  <a href="#contact">Contact</a>
</p>

---

## What I build

Most of my work lives in **Rust**, **Swift**, and **Assembly**, spanning bare-metal systems code, native macOS apps, and command-line tools. I pick up other languages whenever a project or contribution calls for them, though these three are my home base.

A lot of what I build stays private while I work on it. I put it out when I’m happy with it.

## Featured

**[Aegis](https://github.com/itssuross/aegis)** · Bare-metal ARM64 kernel · **Rust & Assembly**

A standalone, zero-dependency operating system kernel written from scratch with no external crates, targeting the QEMU `virt` platform.

- **Multitasking & memory:** Preemptive round-robin scheduler, identity-mapped MMU, and an IRQ-safe heap allocator.
- **Hardware & interrupts:** GICv2 interrupt controller, ARM Generic Physical Timer, PL011 UART driver, and PSCI power management.
- **Resilience & UX:** Custom exception vector table with trap recovery and an interactive shell with sub-millisecond wakeup.

## Stack

| Language | Where I use it |
| :--- | :--- |
| **Rust** | Bare-metal kernels, CLI tools, and cross-platform systems software |
| **Swift** | Native macOS apps built to feel at home on the platform |
| **Assembly** | Boot code, exception vectors, and direct hardware control on ARM64 |
| **Everything else** | Other languages and web tools picked up as needed for specific projects or PRs |

## Open source

**[Atrium](https://github.com/itssljk/atrium)** · A customizable browser start page · **[20 merged PRs](https://github.com/itssljk/atrium/pulls?q=is%3Apr+is%3Amerged+author%3Aitssuross)** · **[My fork](https://github.com/itssuross/atrium)**

I worked across search, accessibility, and settings, including making [search suggestions work with the keyboard](https://github.com/itssljk/atrium/pull/30), testing [search contrast over wallpapers](https://github.com/itssljk/atrium/pull/28) across 42 desktop cases, and making [backup restores reject malformed shortcuts](https://github.com/itssljk/atrium/pull/32) before writing settings.

## The long-term project

> I want to build a programming language of my own, from the syntax and parser through the compiler and runtime.

I have a rough idea of what I want the language to do. I’m still figuring out what it should feel like to write in it.

---

## Contact

[![Email](https://img.shields.io/badge/Email-itssuross%40duck.com-444444?style=for-the-badge&logo=duckduckgo&logoColor=white)](mailto:itssuross@duck.com)
![Discord](https://img.shields.io/badge/Discord-itssuross-5865F2?style=for-the-badge&logo=discord&logoColor=white)
