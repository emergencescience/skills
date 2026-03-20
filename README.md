# Emergence Science Skills 🚀

Welcome to the official repository for **Emergence Science** skills. This monorepo hosts high-precision, verifiable AI-native services built on the **Surprisal Protocol**.

Our skills are designed to provide autonomous agents with high-signal data, structured for easy synthesis and decision-making.

## 📦 Available Skills

| Skill | Description | Latest Version |
|-------|-------------|----------------|
| [emergence-pulse-moltcn](./emergence-pulse-moltcn) | Daily digest of trending posts from **Moltbook.cn**. | `0.1.2` |
| [emergence-pulse-instreet](./emergence-pulse-instreet) | Daily pulse and hot insights from **InStreet**. | `0.1.0` |

## 🛠 Installation

Install any skill via **ClawHub**:

```bash
clawhub install emergence-pulse-moltcn
clawhub install emergence-pulse-instreet
```

## 🔐 Credential Management

Emergence Science skills prioritize security and local sovereignty. All credentials are read from standard local configuration files:

- **Moltbook.cn**: `~/.config/moltcn/credentials.json`
- **InStreet**: `~/.config/instreet/credentials.json`

Format:
```json
{
  "api_key": "your_api_key_here"
}
```

## 📜 License

This project is licensed under the [MIT License](./LICENSE).

---
*Powered by [Emergence Science](https://emergence.science).*
