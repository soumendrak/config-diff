<p align="center">
  <img src="./logo.svg" alt="Config Diff" width="120" />
</p>

<h1 align="center">Config Diff + Validator</h1>

<p align="center">Side-by-side configuration file comparison with built-in validation.</p>

<p align="center">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white" alt="HTML5" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black" alt="JavaScript" />
  <img src="https://img.shields.io/badge/Zero_Dependencies-0b0?style=flat" alt="Zero Dependencies" />
  <img src="https://img.shields.io/badge/license-MIT-blue?style=flat" alt="License: MIT" />
  <img src="https://img.shields.io/badge/PRs-welcome-brightgreen?style=flat" alt="PRs Welcome" />
</p>

## Overview

Config Diff + Validator is a browser-based tool for comparing and validating YAML, JSON, and TOML configuration files. Paste two versions of a config into the side-by-side editors and instantly see the differences highlighted line by line, plus validation warnings for common syntax issues.

Built with zero external dependencies — just vanilla HTML, CSS, and JavaScript.

## Features

| Feature | Description |
|---|---|
| **Side-by-Side Diff** | Myers LCS-based line diff with color-coded additions, removals, and matching lines |
| **Three Formats** | YAML, JSON, and TOML with auto-detection |
| **Live Validation** | Real-time syntax checks as you type — catches tabs in YAML, duplicate keys, malformed JSON, unclosed TOML brackets |
| **Schema Hints** | Warns on common pitfalls: missing spaces after colons, duplicate keys, unusual formatting |
| **Split View** | Left pane (original) vs right pane (modified) with per-pane validation status |
| **Dark Theme** | Easy on the eyes with orange accents |

## Quick Start

1. Open `index.html` in any modern browser
2. Paste your original config in the left pane
3. Paste the modified config in the right pane
4. See the diff and validation results instantly

No build step, no server, no dependencies.

## Project Structure

```
config-diff/
└── index.html    # The entire application
```

## License

MIT — see [LICENSE](LICENSE)
