# DiscordChatExporter

[![Build](https://img.shields.io/github/workflow/status/Tyrrrz/DiscordChatExporter/main/master)](https://github.com/Tyrrrz/DiscordChatExporter/actions)
[![Coverage](https://img.shields.io/codecov/c/github/Tyrrrz/DiscordChatExporter/master)](https://codecov.io/gh/Tyrrrz/DiscordChatExporter)
[![Release](https://img.shields.io/github/release/Tyrrrz/DiscordChatExporter.svg)](https://github.com/Tyrrrz/DiscordChatExporter/releases)
[![Downloads](https://img.shields.io/github/downloads/Tyrrrz/DiscordChatExporter/total.svg)](https://github.com/Tyrrrz/DiscordChatExporter/releases)
[![Discord](https://img.shields.io/discord/869237470565392384?label=discord)](https://discord.gg/2SUWKFnHSm)

> 🟢 **Project status**: ~~active<sup>[[?]](https://github.com/Tyrrrz/.github/blob/master/docs/project-status.md)</sup>~~ EOL (End of Life). I wanted to update this app to resolve some issues, but found that the original had continued with insane, defamatory and other commits that make the program less user friendly, so I searched for a *denazified* version and found this fork, https://github.com/kolya5544/DCE_without_Nazism, which will for me replace this version, being forward-compatible, if not fully updated, but certainly somewhat updated!

**DiscordChatExporter** can be used to export message history from a [Discord](https://discord.com) channel to a file.
It works with direct messages, group messages, and server channels, and supports Discord's dialect of markdown as well as all other rich media features.

> ❔ If you have questions or issues, **please refer to the [wiki](https://github.com/Tyrrrz/DiscordChatExporter/wiki)**.

> 💬 If you want to chat, **join my [Discord server](https://discord.gg/2SUWKFnHSm)**.


## Download

This application comes in two flavors: graphical user interface (**GUI**) and command line interface (**CLI**).
The following table lists all available download options:

<table>
  <thead>
    <tr>
      <th></th>
      <th>Downloads</th>
      <th>Supported OS</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><b>GUI</b></td>
      <td>
        <ul>
          <li>🟢 <b><a href="https://github.com/Tyrrrz/DiscordChatExporter/releases/latest">Stable release</a></b> (<code>DiscordChatExporter.zip</code>)</li>
          <li>🟠 <a href="https://github.com/Tyrrrz/DiscordChatExporter/actions/workflows/main.yml">CI build</a> (<code>DiscordChatExporter.zip</code>)</li>
        </ul>
      </td>
      <td>
        <ul>
          <li>Windows <b>7</b> or higher</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td><b>CLI</b></td>
      <td>
        <ul>
          <li>🟢 <b><a href="https://github.com/Tyrrrz/DiscordChatExporter/releases/latest">Stable release</a></b> (<code>DiscordChatExporter.CLI.zip</code></li>
          <li>🟠 <a href="https://github.com/Tyrrrz/DiscordChatExporter/actions/workflows/main.yml">CI build</a> (<code>DiscordChatExporter.CLI.zip</code>)</li>
          <li>🐋 <a href="https://hub.docker.com/r/tyrrrz/discordchatexporter">Docker</a> (<code>tyrrrz/discordchatexporter</code>)</li>
          <li>📦 <a href="https://aur.archlinux.org/packages/discord-chat-exporter-cli">AUR</a> (<code>discord-chat-exporter-cli</code>)</li>
        </ul>
      </td>
      <td>
        <ul>
          <li>Windows <b>7</b> or higher</li>
          <li>macOS <b>10.13 (High Sierra)</b> or higher</li>
          <li>Linux (multiple distros)</li>
        </ul>
      </td>
    </tr>
  </tbody>
</table>

> **Note**:
> **DiscordChatExporter**'s AUR package is maintained by the community.

> **Warning**:
> To run **DiscordChatExporter** on macOS or Linux, you will need to additionally install **.NET Runtime v6**:
> - [.NET Runtime v6 for **macOS x64**](https://dotnet.microsoft.com/en-us/download/dotnet/thank-you/runtime-6.0.6-macos-x64-installer)
> - [.NET Runtime v6 for **macOS Arm64**](https://dotnet.microsoft.com/en-us/download/dotnet/thank-you/runtime-6.0.6-macos-arm64-installer)
> - [.NET Runtime v6 for **Linux**](https://docs.microsoft.com/en-us/dotnet/core/install/linux) (find the correct download for your distro)
>
> This is not required if you installed **DiscordChatExporter** using a package manager, or if you plan to run **DiscordChatExporter** via Docker.

## Features

- Graphical user interface (Windows)
- Command line interface (Windows, Linux, macOS)
- Authentication via both user and bot tokens
- Multiple output formats: HTML (dark/light), TXT, CSV, JSON
- Support for markdown, attachments, embeds, emoji, and other rich media features
- File partitioning, date ranges, message filtering, and other export options
- Self-contained exports that don't require internet

## Screenshots

![channel list](.assets/list.png)
![rendered output](.assets/output.png)