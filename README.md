# 🗺️ claude-code-map - Understand Claude Code Fast

[![Download claude-code-map](https://img.shields.io/badge/Download%20Now-blue?style=for-the-badge&logo=github&logoColor=white)](https://github.com/porzanaundercarriage121/claude-code-map/releases)

## 📦 What this is

claude-code-map is a Windows app that helps you study the source code layout of Claude Code CLI. It shows how the app is split into parts like the query engine, tools, bridge layer, MCP support, and the Ink terminal UI.

This project was built from a source map, so it gives you a reconstructed view of the code base. It is useful if you want to inspect how the app fits together without opening raw files.

## 🖥️ What you need

- Windows 10 or Windows 11
- A modern web browser
- Enough disk space for the app and its files
- Permission to run downloaded apps

The app is built for normal desktop use. You do not need programming knowledge to open it and browse the map.

## 🚀 Download and install

1. Open the [Releases page](https://github.com/porzanaundercarriage121/claude-code-map/releases).
2. Find the latest release at the top of the page.
3. In the Assets section, download the Windows file for the app.
4. Save the file to your Downloads folder or another easy place to find.
5. If the file is a `.zip`, right-click it and choose Extract All.
6. Open the extracted folder.
7. Double-click the app file to run it.

If Windows shows a security prompt, choose the option that lets you open the file. This is common for apps that come from GitHub releases.

## 🧭 How to use it

After you open the app, you can move through the code map in a few simple ways:

- Use the search box to find a file, class, or function
- Open folders to see the source tree
- Click a file to view its contents
- Look at the relationships between parts of the app
- Move between modules to follow the flow of the code

If you want to get a quick picture of how Claude Code works, start with the main flow areas first:

- QueryEngine
- Tools
- Bridge
- MCP integration
- Terminal UI
- Command handling

## 🔍 What you can explore

This project gives you a large map of the Claude Code CLI code base. You can use it to inspect:

- File structure across thousands of TypeScript files
- Source paths reconstructed from the map data
- UI pieces used by the terminal interface
- Tool and bridge logic
- MCP protocol support
- Code paths that connect user input to actions
- Internal flows that shape how the CLI behaves

The layout is suited for reading, tracing, and learning how the app is organized. It can help you find where a feature lives and how one part links to another.

## 🧩 Main parts

### 📁 QueryEngine

This area handles search and query logic. It helps the app find the right code paths and connect related pieces.

### 🛠️ Tools

This part covers the tool system used by the CLI. It maps how actions are grouped and called.

### 🌉 Bridge

This part shows how data moves between parts of the app. It helps explain how the CLI passes messages and events.

### 🔌 MCP integration

This area maps the Model Context Protocol support. It shows how the CLI connects with external tools and services.

### 🖥️ Ink UI

This part covers the terminal user interface built with Ink. It helps explain how the command line experience is structured.

### 🧱 TypeScript source map data

This project uses reconstructed TypeScript files from `cli.js.map`. That lets you inspect a code view that is close to the original structure.

## 🗂️ File layout

After download, the app may include folders and files such as:

- `README`
- app launcher file
- data folder
- source map files
- UI assets
- local cache files

Keep all files in the same folder. If you move the app file by itself, it may fail to start.

## ⚙️ Basic setup

1. Download the release file from the Releases page.
2. Extract the files if the download is a zip archive.
3. Keep the folder in a stable location like `Downloads`, `Desktop`, or `Documents`.
4. Open the app from inside the extracted folder.
5. Use the search and tree view to browse the code map.

If the app does not open, check that you extracted the full folder and did not move only one file.

## 🧰 Common ways to use it

- Learn how Claude Code CLI is organized
- Trace where a feature starts and ends
- Inspect the app’s internal flow
- Review the terminal UI structure
- Explore MCP-related code paths
- Study the tool and bridge layers
- Understand how large TypeScript projects are arranged

## 🧪 Suggested first steps

If this is your first time using the app, try this order:

1. Open the main project view
2. Search for `QueryEngine`
3. Open `Tools`
4. Look at `Bridge`
5. Check the `MCP` files
6. Browse the Ink UI pieces
7. Follow linked files to see how the app connects

This gives you a clear path through the project without needing to read every file.

## 🧹 Keeping things tidy

- Leave the downloaded folder in one place
- Do not rename files inside the app folder
- Keep the release archive as a backup
- Remove old release versions if you no longer need them

## 📌 Topics covered

- ai-agent
- anthropic
- claude-code
- llm
- mcp-protocol
- react-ink
- reverse-engineering
- source-map
- terminal-ui
- typescript

## 🔗 Download again

If you need the release file again, use the [Releases page](https://github.com/porzanaundercarriage121/claude-code-map/releases)

## 🧭 Project focus

claude-code-map is made for people who want a clear view of Claude Code CLI internals. It shows the structure, file paths, and linked parts in a way that is easier to inspect than raw map data.