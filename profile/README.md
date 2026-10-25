
<p align="center">
  <img src="https://github.com/user-attachments/assets/ac790a70-0def-43f1-b24f-6371df55bfb6" alt="Logo" width="120" />
</p>

<h1 align="center">PC Screen Cast to Any Device</h1>

<p align="center">
  <em>Cast your PC screen to any device on your local network — phone, TV, tablet. <br>Open-source, no accounts, no cloud, privacy-first.</em>
</p>

<p align="center">
  <a href="#">
    <img src="https://github.com/user-attachments/assets/f53d36ed-adae-458e-9028-6664e9979f04" alt="Latest Release" />
  </a>
</p>

<br>

## About

<img align="right" width="520" src="https://github.com/user-attachments/assets/1551c1d9-c33c-4f8c-89bb-1cbdef0f94a4" alt="Screenshot" />

**PC Screen Cast to Any Device** is an open-source tool for streaming your computer screen to phones, TVs, tablets, and other devices over your local network. It is built for people who want a simple, transparent way to mirror their desktop — without accounts, subscriptions, or sending data through third-party cloud servers.

Whether you want to show a presentation on a TV, mirror your screen to a phone, or share your desktop with another device in the same room, the tool does it locally and privately. No sign-up, no telemetry, no external dependency.

The project is community-driven, with a focus on reliability, low latency, and clear logs when something goes wrong.

### Key Features

- **Cast to any device** — phone, TV, tablet, or another PC on the same network
- **Local network only** — data never leaves your LAN
- **No accounts** — no sign-up, no cloud, no subscriptions
- **Low latency** — optimized for real-time screen mirroring
- **Cross-platform** — Windows, Linux, and macOS
- **Multiple receivers** — web browser, native app, or smart TV client
- **Audio support** — stream system audio alongside the screen
- **Detailed logging** — built-in diagnostics for troubleshooting

<br clear="right" />

---

## Supported Devices

| Receiver | Support |
| :--- | :---: |
| Web browser (any modern browser) | Yes |
| Android phone / tablet | Yes |
| iOS phone / tablet | Yes |
| Smart TV (browser-based) | Yes |
| Another PC (browser or client) | Yes |
| Chromecast / AirPlay | Experimental |
| Smart TV native apps | Not supported |

<p align="center">
  Yes — supported &nbsp;&nbsp; Experimental — may work with limitations &nbsp;&nbsp; Not supported — no native support
</p>

---

## System Requirements

- **OS (sender):** Windows 10+, modern Linux distro, or macOS 12+
- **Runtime:** .NET 8 (bundled in releases) or Docker
- **RAM:** 512 MB minimum, 2 GB recommended
- **Network:** Both devices on the same local network (LAN/Wi-Fi)
- **Receiver:** Any device with a modern web browser, or the native client

---

## How to Use

1. **Download** the latest release for your platform, or pull the Docker image.
2. **Extract** the archive (or run the container).
3. **Launch** the application — it will start a local server and show a URL.
4. **Open the URL** on the receiver device (phone, TV, tablet) in a browser.
5. **Select your screen** and start casting.
6. **Adjust quality and latency** in the settings if needed.

> Both devices must be on the same local network. No internet connection is required.

---

## Configuration

| Setting | What It Does |
| :--- | :--- |
| `server.port` | Local port for the casting server |
| `stream.quality` | Video quality preset (low, medium, high) |
| `stream.fps` | Target frame rate |
| `audio.enabled` | Stream system audio alongside the screen |
| `security.pin` | Optional PIN to restrict who can connect |
| `log.level` | Logging verbosity (info, debug, trace) |

---

## Important to Know

- **Local network only.** The tool is designed for devices on the same LAN. Do not expose the server to the public internet without authentication.
- **No cloud, no accounts.** Nothing is sent to external servers, and no sign-up is required.
- **Performance depends on your network.** Wi-Fi quality and router speed affect latency and smoothness.
- **Some receivers are experimental.** Chromecast and AirPlay may work with limitations.
- **Keep it updated.** New releases include performance and compatibility fixes.

---

## Frequently Asked Questions

**Do I need an internet connection?**
No. The tool works entirely on your local network.

**Is my data sent to a cloud server?**
No. All traffic stays on your LAN.

**Which devices can receive the stream?**
Any device with a modern web browser, plus the native client where available.

**Does it support audio?**
Yes, system audio can be streamed alongside the screen.

**Can I use it over the internet?**
It is designed for local networks. Exposing it publicly is not recommended without additional security.

**Is it free?**
Yes, the project is open-source and free to use.

**Is it legal?**
The tool itself is legal. You are responsible for what you cast and for complying with the laws in your jurisdiction.

---

## Troubleshooting

| Problem | Suggested Fix |
| :--- | :--- |
| Receiver cannot connect | Check that both devices are on the same network and the port is open |
| Stream is laggy | Lower quality or FPS in settings; check Wi-Fi signal |
| No audio | Enable audio streaming in settings and check system audio permissions |
| Browser shows a blank page | Try another browser or update the current one |
| Server does not start | Check the port is not in use and the app has network permissions |
| Docker container exits | Inspect logs with `docker logs <container>` |

---

## Contributing

Contributions are welcome — bug reports, receiver support, and code. Please read the contributing guidelines before opening a pull request, and include logs when reporting issues.

---

## Disclaimer

PC Screen Cast to Any Device is an open-source tool intended for casting your own screen to devices on your local network. It does not include content, subscriptions, or third-party services. You are responsible for complying with the laws in your jurisdiction and for securing your local network.

---

## Keywords

`pc screen cast` · `screen mirroring` · `cast pc to phone` · `cast pc to tv` · `local network streaming` · `open source screen cast` · `privacy-first casting` · `no cloud screen mirror` · `lan screen sharing` · `desktop mirroring` · `cast to any device` · `screen cast tool` · `low latency mirroring` · `self-hosted casting` · `docker screen cast` · `windows screen cast` · `linux screen cast` · `macos screen cast` · `phone screen receiver` · `tv screen receiver`
