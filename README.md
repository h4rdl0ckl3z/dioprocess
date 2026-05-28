# DioProcess — Advanced Windows Process & System Monitor

> **Notice: This is the final public release.**
>
> Development will continue only in private builds. No further updates, features, or bug fixes will be published to this public repository. Thank you for your interest in the project.

---

Modern Windows desktop application for real-time system monitoring and low-level process manipulation.

Built with **Rust 2021** + **Dioxus 0.6** | **Requires administrator privileges**

![Preview 1](./assets/preview1.png)
<img width="1115" height="735" alt="image" src="https://github.com/user-attachments/assets/71dd7db4-1614-4026-8d8b-62737e2fe60d" />


[![Rust](https://img.shields.io/badge/Rust-2021-orange?logo=rust)](https://www.rust-lang.org)
[![Windows](https://img.shields.io/badge/Platform-Windows-blue?logo=windows)](https://microsoft.com/windows)
[![Dioxus](https://img.shields.io/badge/UI-Dioxus%200.6-purple)](https://dioxuslabs.com)

## Core Features

### Process Management
- Live enumeration of processes, threads, handles, modules & memory regions
- Process tree view with parent-child relationships
- Real-time CPU/memory performance graphs
- Process string scanning (ASCII & UTF-16)

### Network & Services
- TCP/UDP connection listing with owning process
- Windows Service management (enumerate, start, stop, create, delete)

### DLL Injection (7 methods)
- LoadLibrary, Thread Hijack, APC Queue, EarlyBird
- Remote Mapping, Function Stomping, Manual Mapping

### Shellcode Injection
- Classic (from file), Web Staging (from URL), Threadless

### Process Creation & Evasion
- PPID Spoofing
- Process Hollowing
- Process Ghosting
- Ghostly Hollowing
- Process Herpaderping
- Herpaderping Hollowing

### Security Research (Kernel Driver)
- Process Protection (PPL) manipulation
- Token Privilege Escalation
- Clear Debug Flags (anti-anti-debugging)
- Kernel Callback Enumeration
- PspCidTable Enumeration
- Kernel Injection (shellcode & DLL)

### DLL Analysis
- Hook Detection (IAT scanning)
- DLL Unhooking (restore from disk)

### System Events (Experimental)
- Real-time kernel event capture (process, thread, image, handle, registry)
- SQLite persistence with 24-hour retention

### Utilities
- File Bloating
- Token Theft

## Build & Run

```bash
cargo build --release
.\target\release\dioprocess.exe   # Run as administrator
```

## Keyboard Shortcuts

| Key | Action |
|-----|--------|
| `F5` | Refresh |
| `Delete` | Kill process |
| `Escape` | Close modal |

## MIT licensed.

**Note:** This public repository is archived and no longer accepting contributions.

Built with Rust & Dioxus — 2025
