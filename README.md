Fancode Live Events ✨✊

""Workflow Status" (https://github.com/kajju027/Fancode-Events-Json/actions/workflows/update_fancode_json.yml/badge.svg)" (https://github.com/kajju027/Fancode-Events-Json/actions)
""Last Commit" (https://img.shields.io/github/last-commit/kajju027/Fancode-Events-Json)" (https://github.com/kajju027/Fancode-Events-Json/commits/main)
""Repo Size" (https://img.shields.io/github/repo-size/kajju027/Fancode-Events-Json)" (https://github.com/kajju027/Fancode-Events-Json)
""Stars" (https://img.shields.io/github/stars/kajju027/Fancode-Events-Json?style=social)" (https://github.com/kajju027/Fancode-Events-Json/stargazers)
""Forks" (https://img.shields.io/github/forks/kajju027/Fancode-Events-Json?style=social)" (https://github.com/kajju027/Fancode-Events-Json/network/members)

---

Overview

Fancode Live Events is a continuously updated repository that provides structured Fancode event data for developers and IPTV integrations.
It delivers clean, ready-to-use outputs with low latency and reliable availability.

---

Available Files

fancode.json

A structured dataset that includes:

- Live matches
- Upcoming matches
- Event metadata
- Match details such as teams, category, language, and more

fancode.m3u

An IPTV-ready playlist file that includes:

- Live streams only
- Stream URLs
- Match titles
- tvg-logo support
- Category and language grouping

---

Update Frequency

Update Type| Interval
Automatic Updates| Every 7 minutes

This ensures near real-time data availability.

---

Usage

Direct Links

JSON:
https://raw.githubusercontent.com/kajju027/Fancode-Events-Json/main/fancode.json

M3U Playlist:
https://raw.githubusercontent.com/kajju027/Fancode-Events-Json/main/fancode.m3u

---

JavaScript Example

fetch("https://raw.githubusercontent.com/kajju027/Fancode-Events-Json/main/fancode.json")
.then((response) => response.json())
.then((data) => console.log(data));

---

IPTV Usage

Paste the .m3u URL into any compatible IPTV player to access the available live streams.

---

Repository Status

Metric| Value
Updates| Automated
Availability| High
Maintenance| Minimal

---

Disclaimer

This repository does not host any media content.
It provides structured data and publicly accessible stream references for informational and development purposes only.

---

Maintainer

Sayan

---

Support

If you find this project useful:

- Star the repository
- Share it
- Use responsibly
