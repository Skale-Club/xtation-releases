# Xtation desktop apps

Windows desktop wrappers for YouTube, YouTube Music, and your own Home Assistant. Current stable version: **1.1.0**.

Download and run the Windows x64 installer you want:

- [YouTube](https://github.com/Skale-Club/xtation-releases/releases/download/v1.1.0/youtube_1.1.0_x64-setup.exe)
- [YouTube Music](https://github.com/Skale-Club/xtation-releases/releases/download/v1.1.0/youtube-music_1.1.0_x64-setup.exe)
- [Home Assistant](https://github.com/Skale-Club/xtation-releases/releases/download/v1.1.0/home-assistant_1.1.0_x64-setup.exe)

Installation is per user and requires no Rust, Node, C++ tools, or administrator account. Windows may show a SmartScreen warning because these installers do not have a paid Authenticode certificate.

Home Assistant asks for **your own server address on first launch**. The address stays in your Windows user profile and can be changed or forgotten under **Ajuda > Endereço do Home Assistant**. No personal server is bundled.

The apps check for updates in the background. Use **Ajuda > Atualizações** to check manually; when an update is ready, choose **Reiniciar para atualizar**. Each app verifies its own update signature before installation. These update signatures are separate from Windows Authenticode signing.

[Release notes and all assets](https://github.com/Skale-Club/xtation-releases/releases/latest).

This repository contains installers and update feeds. Development and source history are maintained separately.