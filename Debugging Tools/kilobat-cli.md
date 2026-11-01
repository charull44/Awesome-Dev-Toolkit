# 🌐 Kilobat CLI – macOS Network Diagnostics

<p align="center">
  <a href="https://github.com/seifip/kilobat-cli">
    <img src="https://img.shields.io/badge/Open-Kilobat%20CLI-black?style=for-the-badge" alt="Open Kilobat CLI source" />
  </a>
</p>

---

## 🧩 SNAPSHOT

| 🚀 Category | Debugging Tool |
|------------|----------------|
| 🎯 Best For | Diagnosing a Mac's connection to a host or API |
| 🔗 Link | https://github.com/seifip/kilobat-cli |
| Platform | macOS 14+ |
| License | GPL-3.0-only |

---

<details>
<summary>⚙️ WHAT MAKES IT DIFFERENT?</summary>

<br>

Kilobat brings DNS, latency, interface and proxy-routing checks into one CLI:

* JSON output for scripts
* An interactive terminal dashboard
* A local stdio MCP server: `kilobat mcp`

</details>

---

<details>
<summary>🧪 WHEN TO USE</summary>

<br>

Use it when a host or API will not connect, or when a coding agent needs structured network diagnostics from the Mac it runs on.

```sh
brew install seifip/kilobat/kilobat
kilobat why example.com --json
```

The Homebrew formula builds from source with Xcode 16 or later.

</details>

---

<details>
<summary>💡 WHY IT’S AWESOME</summary>

<br>

The same diagnostics are available to terminal users, scripts and MCP clients. The public CLI source makes the checks inspectable.

The menu-bar app is a separate proprietary product. Reading Wi-Fi names requires that companion app and Location permission; the CLI does not remove macOS permission requirements.

</details>

---

## 🚀 FINAL TAKE

A network troubleshooting tool for Mac developers who want terminal output they can also use in scripts and agent workflows.
