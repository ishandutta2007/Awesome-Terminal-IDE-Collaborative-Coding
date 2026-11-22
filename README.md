# Awesome-Terminal-IDE-Collaborative-Coding
# Awesome-Terminal-IDE-Collaborative-Coding

# Top Terminal IDE & Collaborative Coding Ecosystem

**Curated List of SaaS/Hosted Platforms & Open-Source GitHub Projects**  
*Focused on Terminal IDEs, Real-Time Collaborative Editors, Cloud Dev Environments & Remote Pair Programming*  
**Last updated: November 2026**

This repository tracks notable **SaaS/hosted platforms** and **open-source projects** for **Terminal IDEs & Collaborative Coding**. These tools enable developers and engineering teams to edit code inside the terminal, share live terminal sessions, run remote cloud development workspaces, and collaborate in real time across local and distributed machines.

**Examples** include zenbu-labs/terminal-code, Zed, Helix, Neovim, Lapce, Eclipse Theia, code-server, OpenVSCode Server, tmate, Zellij, Coder, Daytona, Replit, GitHub Codespaces, Gitpod, CodeSandbox, StackBlitz, VS Code Live Share, and JetBrains Code With Me.

**Open-source emphasis**: This list heavily expands on active open-source terminal-native IDEs, multiplayer code editors, self-hosted cloud IDEs, and terminal session-sharing utilities — ideal for developers, open-source maintainers, and teams building fast, reproducible, and collaborative coding workflows.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saashosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[GitHub Codespaces](https://github.com)**  
  Cloud-hosted development environments integrated directly into GitHub repositories with prebuilt containers, browser/desktop/CLI access, and Live Share support.

- **[Replit](https://replit.com)**  
  Browser-based collaborative cloud IDE featuring real-time multiplayer editing, integrated terminal shells, instant deployments, and AI coding agents.

- **[Gitpod (Ona)](https://gitpod.io)**  
  Automated cloud development environment platform that provisions ephemeral, ready-to-code workspaces from Git repositories with team sharing.

- **[CodeSandbox](https://codesandbox.io)**  
  Cloud development platform providing instant microVM sandboxes, live collaboration, and browser or SSH-connected IDE workflows.

- **[StackBlitz](https://stackblitz.com)**  
  Instant browser-based IDE powered by WebContainers that executes Node.js and full-stack environments locally in the browser with live URL sharing.

- **[VS Code Live Share](https://microsoft.com)**  
  Microsoft's proprietary extension for VS Code enabling real-time collaborative editing, shared debugging sessions, and shared terminal access.

- **[JetBrains Code With Me](https://jetbrains.com)**  
  Commercial collaborative development and pair programming service built into JetBrains IDEs with voice/video calls and shared terminal permissions.

- **[Floobits](https://floobits.com)**  
  Real-time collaborative code editing service offering plugins for terminal and GUI editors alongside shared workspaces.


## Open-Source GitHub Projects

- **[terminal-code (zenbu-labs/terminal-code)](https://github.com/zenbu-labs/terminal-code)**  
  Runs full VS Code directly inside modern terminals (using the Kitty graphics protocol and `code-server`), supporting split panes, diffs, extensions, and SSH remoting.

- **[Zed](https://github.com)**  
  High-performance, multiplayer-native code editor written in Rust with built-in real-time collaborative workspaces, screen/terminal sharing, and Vim mode.

- **[Eclipse Theia](https://github.com)**  
  Open-source, extensible cloud and desktop IDE framework compatible with VS Code extensions and designed for multi-user web workspaces.

- **[code-server](https://github.com)**  
  Open-source tool by Coder that runs VS Code on any remote server and serves it securely through a web browser or terminal wrapper.

- **[OpenVSCode Server](https://github.com)**  
  Upstream open-source server distribution of VS Code maintained by Gitpod for self-hosted cloud and container development environments.

- **[Helix](https://github.com)**  
  Post-modern modal terminal text editor written in Rust with built-in tree-sitter syntax highlighting, multi-cursor editing, and zero-config LSP integration.

- **[Neovim](https://github.com)**  
  Hyper-extensible Vim-based terminal editor with native Lua scripting, async LSP, and plugins like `instant.nvim` for peer-to-peer collaborative editing.

- **[Lapce](https://github.com)**  
  Lightning-fast, open-source code editor written in Rust featuring a native GPU-accelerated UI, modal editing, and built-in remote SSH development.

- **[Termide](https://github.com/termide/termide)**  
  All-in-one terminal workspace written in Rust combining an LSP-enabled code editor, dual-pane SFTP file manager, Git client, database viewer, and detachable SSH sessions.

- **[Fresh](https://github.com)**  
  Lightweight, zero-config terminal IDE built as a single binary with LSP support, multi-cursor editing, Git diff review, and remote SSH workflows.

- **[tmate](https://github.com)**  
  Fork of `tmux` engineered for instant, encrypted terminal sharing that lets multiple developers view and type in the same terminal session over SSH or web.

- **[Zellij](https://github.com)**  
  Modern terminal workspace and multiplexer written in Rust with floating panes, WebAssembly plugins, and multi-user session attachment.

- **[Coder](https://github.com)**  
  Self-hosted cloud development environment platform using Terraform to provision remote workspaces accessible via browser IDEs, local editors, or SSH.

- **[Daytona](https://github.com)**  
  Open-source development environment manager for spinning up standardized remote workspaces on any infrastructure with single-command CLI orchestration.

- **[Upterm](https://github.com)**  
  Open-source instant terminal sharing utility built for remote pair programming, allowing secure multi-user SSH access to a local terminal session.

### Additional Strong Open-Source Options

- **[Micro](https://github.com)** — Modern, intuitive terminal-based text editor with standard desktop keybindings, mouse support, and plugin ecosystem.
- **[Kakoune](https://github.com)** — Modal terminal code editor using a client-server architecture that natively supports multiple users editing the same session simultaneously.
- **[DevPod](https://github.com)** — Client-only open-source tool to spin up reproducible `devcontainer.json` environments on any cloud, Kubernetes cluster, or SSH host.
- **[Wetty](https://github.com)** & **[ttyd](https://github.com)** — Lightweight web-based terminal emulators for sharing CLI sessions over HTTP/HTTPS.
- **[Code-Sync](https://github.com/sahilatahar/Code-Sync)** — Open-source real-time collaborative web code editor built with React, Socket.IO, and Docker.
- **[Termux](https://github.com)** — Open-source Android terminal emulator and Linux environment enabling full mobile terminal IDE workflows.

**Frameworks for building custom systems**: Combine **Neovim** or **Helix** inside **tmate** / **Zellij** for instant terminal pair programming, or deploy **Coder** + **code-server** + **DevPod** for a complete self-hosted collaborative cloud IDE platform.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Terminal sharing tools (`tmate`, `upterm`) and self-hosted cloud IDEs grant shell execution access; always use read-only links or strict SSH key authentication when collaborating with external guests.
- GPU-accelerated terminal wrappers like `terminal-code` require terminal emulators supporting the Kitty graphics protocol (e.g., Ghostty, Kitty, WezTerm).

---

**Made for terminal enthusiasts, remote engineering teams, pair programmers, and open-source developers.**  
Let's make terminal IDEs and collaborative coding faster, self-hostable, and open to everyone.
