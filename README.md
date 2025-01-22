<div align="center">
  <h2 align="center">Discord Mass Reporter</h2>
  <p align="center">
    An automated tool for sending multiple reports on Discord users and servers with proxy support and multi-threading capabilities.
    <br />
    <br />
    <a href="https://discord.cyberious.xyz">💬 Discord</a>
    ·
    <a href="#-changelog">📜 ChangeLog</a>
    ·
    <a href="https://github.com/sexfrance/Discord-Mass-Reporter/issues">⚠️ Report Bug</a>
    ·
    <a href="https://github.com/sexfrance/Discord-Mass-Reporter/issues">💡 Request Feature</a>
  </p>
</div>

---

### ⚙️ Installation

- Requires: `Python 3.7+`
- Make a python virtual environment: `python3 -m venv venv`
- Source the environment: `venv\Scripts\activate` (Windows) / `source venv/bin/activate` (macOS, Linux)
- Install the requirements: `pip install -r requirements.txt`

---

### 🔥 Features

- Mass report Discord users and servers
- Interactive reporting menu with multiple report reasons
- Proxy support for avoiding rate limits
- Multi-threaded report sending
- Real-time reporting statistics
- Configurable thread count
- Debug mode for troubleshooting
- Proxy/Proxyless mode support
- Multi Token support for authentication
- Automated user agent randomization

---

### 📝 Usage

1. **Configuration**:
   Edit `input/config.toml`:

   ```toml
   [report]
   user_id = "" # Optional: Pre-configured user ID to report
   server_id = "" # Optional: Pre-configured server ID to report

   [dev]
   Debug = false
   Proxyless = false
   Threads = 1
   ```

2. **Setup Required Files**:

   - Add Discord tokens to `input/tokens.txt` (one per line)
   - Add proxies to `input/proxies.txt` (optional, one per line)
   - Format: `ip:port` or `user:pass@ip:port`

3. **Running the script**:

   ```bash
   python main.py
   ```

4. **Using the Tool**:
   - Choose between reporting a user or server
   - Enter the target ID
   - Select the report reason from the menu
   - Specify the number of reports to send

---

### 📹 Preview

![Preview](https://i.imgur.com/d7KkoHB.gif)

---

### ❗ Disclaimers

- This project is for educational purposes only
- The author is not responsible for any misuse of this tool
- Use responsibly and in accordance with Discord's terms of service

---

### 📜 ChangeLog

```diff
v0.0.1 ⋮ 12/26/2024
! Initial release
```

<p align="center">
  <img src="https://img.shields.io/github/license/sexfrance/Discord-Mass-Reporter.svg?style=for-the-badge&labelColor=black&color=f429ff&logo=IOTA"/>
  <img src="https://img.shields.io/github/stars/sexfrance/Discord-Mass-Reporter.svg?style=for-the-badge&labelColor=black&color=f429ff&logo=IOTA"/>
  <img src="https://img.shields.io/github/languages/top/sexfrance/Discord-Mass-Reporter.svg?style=for-the-badge&labelColor=black&color=f429ff&logo=python"/>
</p>
