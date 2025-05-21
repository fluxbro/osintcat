# 🕵️‍♀️ OSINTCAT

OSINTCAT is a powerful and flexible Open Source Intelligence (OSINT) tool that allows you to gather intelligence from various sources with just a few lines of code.


## 📦 Installation

```bash
pip install osintcat
```

## 🚀 Quick Start

```python
from osintcat import osintcat


result = osintcat(cat_id="", module="breach", query="target@example.com")
print(result)

discord_info = osintcat(cat_id="", module="discord", query="ID")
print(discord_info)


email_osint = osintcat(cat_id="", module="email-osint", query="target@example.com")
print(email_osint)
```

## 🛠️ Available Modules

| Module | Description | Input Example |
|--------|-------------|--------------|
| `breach` | Data breach Lookup | `target@example.com` |
| `discord` | Discord ID 2 IP | `ID` |
| `email-osint` | Email OSINT Lookup | `target@example.com` |

## 🔧 Configuration

osintcat requires a `cat_id` for authentication. You can get your cat id on [our website](https://osintcat.com/register) ( Only for premium users. ).

## 🌐 Community

<div align="center">
  <a href="https://discord.gg/osintcats">
    <img src="https://img.shields.io/discord/1369757362612732124?color=5865F2&logo=discord&logoColor=white&style=for-the-badge" alt="Join our Discord server">
  </a>
</div>

Join our community for support

## 🔄 Changelog

See [CHANGELOG](https://osintcat/pypi/changelogs) for version history.