    # Privify SCOUT

    **AI risk visibility for security and platform leadership.**

    SCOUT runs on any machine in minutes and produces a single, shareable report
    that shows where AI is actually operating across your organization — sanctioned
    and shadow — and what risk it is creating. No agents, no cloud connectivity,
    no installation required.

    Security teams use it to get a defensible view of AI-driven exposure before an
    audit or board conversation. Platform teams use it to reconcile what is
    deployed against what is sanctioned. CIOs use it to understand AI risk posture
    without interpreting raw scan output.

    **Latest: 0.1.4**

    ## Download

    | Platform | Binary |
    |----------|--------|
    | macOS (arm64 + Intel) | [scout-macos](https://github.com/Privify-Inc/privify_scout-releases/raw/main/releases/0.1.4/scout-macos) |
    | Linux x86\_64 | [scout-linux](https://github.com/Privify-Inc/privify_scout-releases/raw/main/releases/0.1.4/scout-linux) |
    | Windows x86\_64 | [scout-windows.exe](https://github.com/Privify-Inc/privify_scout-releases/raw/main/releases/0.1.4/scout-windows.exe) |

    Verify integrity: [checksums.txt](https://github.com/Privify-Inc/privify_scout-releases/raw/main/releases/0.1.4/checksums.txt) (SHA-256)

    ## Quick start

    ```bash
    # macOS
    curl -LO https://github.com/Privify-Inc/privify_scout-releases/raw/main/releases/0.1.4/scout-macos
    chmod +x scout-macos && xattr -c scout-macos && ./scout-macos

    # Linux
    curl -LO https://github.com/Privify-Inc/privify_scout-releases/raw/main/releases/0.1.4/scout-linux
    chmod +x scout-linux && ./scout-linux

    # Windows (PowerShell)
    Invoke-WebRequest -Uri https://github.com/Privify-Inc/privify_scout-releases/raw/main/releases/0.1.4/scout-windows.exe -OutFile scout.exe
    .\scout.exe
    ```

    A browser report opens automatically when the scan completes.

    ## What SCOUT finds

    | Signal category | What it surfaces |
    |-----------------|-----------------|
    | MCP servers | Registered tool-call surfaces (Cursor, Claude Desktop, custom) |
    | API keys | Keys in environment variables and config files (OpenAI, Anthropic, etc.) |
    | Local AI servers | Ollama, LM Studio, llama.cpp, and active AI processes |
    | AI model files | Weight files on disk — GGUF, safetensors, .bin |
    | AI tools & config | IDE extensions, CLAUDE.md, .cursorrules, browser AI usage |
    | AI packages | OpenAI / Anthropic SDKs, LangChain, and AI CLI tools |
    | Network & containers | LAN AI endpoints, networked MCP servers, Docker/k8s AI workloads |

    Findings are organized into an interactive three-level report: a spatial
    overview graph, per-category detail, and per-finding drill-down. Everything
    stays on the machine — no data is transmitted.

    ## Who it's for

    **CISOs** — a defensible view of AI-driven risk exposure, ready for audit or
    board presentation without reformatting.

    **AI platform leads** — a clear picture of what is actually deployed versus
    what your organization has sanctioned.

    **CIOs** — a business-level summary of AI risk posture, without needing to
    interpret raw scan output.

    ## All releases

    - [0.1.4](releases/0.1.4/README.md)
- [0.1.3](releases/0.1.3/README.md)
- [0.1.2](releases/0.1.2/README.md)
- [0.1.1](releases/0.1.1/README.md)
- [0.1.0](releases/0.1.0/README.md)

    ---
    Built by [Privify](https://privify.io) · [Request a demo](mailto:hello@privify.io)
