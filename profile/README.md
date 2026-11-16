<p align="center">
  <b>🌐 <a href="https://goome-ui.github.io/docs/builder/">Try it in your browser</a> 🌐</b><br>
  <sub>drag a ui together in the <a href="https://goome-ui.github.io/docs/builder/">builder</a>, or see the <a href="https://goome-ui.github.io/docs/browser/">real goome running in a page</a>, nothing to install</sub>
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/goome-ui/.github/main/profile/logo.png" alt="goome" width="150">
</p>

<h1 align="center">🫠 goome 🫠</h1>

<p align="center">
<b>See-through overlays, normal app windows, game mod menus and engine ui for any C program. One file, no dependencies, Linux, Windows, Mac.</b>
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/goome-ui/c-goome/main/docs/demo.gif" alt="goome demo on gnome" width="720"><br>
  <sub>a notes app, a stream overlay and a mod menu, all goome, running on my GNOME desktop</sub>
</p>

<p align="center">
  <img src="https://goome-ui.github.io/docs/assets/badges/c99.svg" alt="C99">
  <img src="https://goome-ui.github.io/docs/assets/badges/one-file-goome-h.svg" alt="one file">
  <img src="https://goome-ui.github.io/docs/assets/badges/dependencies-none.svg" alt="no dependencies">
  <img src="https://goome-ui.github.io/docs/assets/badges/ui-kit-built-in.svg" alt="UI kit">
  <img src="https://img.shields.io/badge/Linux-X11%20%2B%20Wayland-1b1d22?style=flat-square&logo=linux&logoColor=white" alt="Linux">
  <img src="https://img.shields.io/badge/Windows-10%20%2F%2011-1b1d22?style=flat-square&logo=windows11&logoColor=white" alt="Windows">
  <img src="https://img.shields.io/badge/macOS-14%2B-1b1d22?style=flat-square&logo=apple&logoColor=white" alt="macOS">
  <img src="https://img.shields.io/badge/license-GPL--3.0-1b1d22?style=flat-square" alt="GPL-3.0">
</p>

<p align="center">
  goome puts a see-through layer on top of every app on your screen. You draw on it, only the parts you draw take clicks, and everything else goes right through to whatever is under it. Good for game overlays and little HUDs.<br> <br>
  You can make apps and overlays with it, or game mods and UI inside an engine, all from the same code.<br> <br>
  It's a single C header you drop in and it runs on Linux (X11 and Wayland), Windows and macOS. You can use it from C, C#, Python, Java, Rust, Node, Go, Zig or Lua, and it works in Unity, Godot, Minecraft mods and OBS too.<br> <br>
  <b>0.5 is out</b> with animations, emoji and right to left text, typing in other languages (IME), screen reader support and five new languages. <a href="https://goome-ui.github.io/docs/versions/">Whats new</a><br> <br>
  Theres an install line for every language right below.<br> <br>
  The <a href="https://goome-ui.github.io/docs/">docs</a> have everything, and the <a href="https://goome-ui.github.io/docs/builder/">UI builder</a> lets you drag a layout together in your browser and gives you the code.<br>
  <a href="https://github.com/goome-ui/examples">Examples</a> are up too if you want to jump in.<br> <br>
  To try it first, grab one of the <a href="https://goome-ui.github.io/docs/downloads/">ready made apps</a> from the <a href="https://github.com/goome-ui/examples/releases/latest">examples release</a>. To start your own, <code>goome new</code> from <a href="https://github.com/goome-ui/goome-cli">goome-cli</a> makes a project from a template in any of the languages.<br> <br>
  Anyone can help out. A desktop it doesnt work on yet is the best thing you can send, read the <a href="https://github.com/goome-ui/.github/blob/main/CONTRIBUTING.md">contributing guide</a> first. Questions go in <a href="https://github.com/goome-ui/c-goome/discussions">Discussions</a>, and every main repo has a few <a href="https://goome-ui.github.io/docs/community/">good first issues</a>.<br> <br>
  Do you like this project? If so, please let me know!
  <a href="https://sevvy-wevvy.com/discord">Discord</a>
</p>

<h3 align="center">⚡ Install ⚡</h3>

<div align="center">

| Language | Install |
| :---: | :---: |
| C | grab <a href="https://github.com/goome-ui/c-goome/releases/latest">goome.h</a> and include it |
| Python | <code>pip install goome</code> |
| C# | <code>dotnet add package GoomeSharp</code> |
| Java | <code>io.github.goome-ui:goome</code> on Maven Central |
| Rust | <code>goome = "0.5"</code> in your Cargo.toml |
| Go | <code>go get github.com/goome-ui/go-goome</code> |
| VS Code | <code>goome-ui.vscode-goome</code> on the <a href="https://marketplace.visualstudio.com/items?itemName=goome-ui.vscode-goome">Marketplace</a> or <a href="https://open-vsx.org/extension/goome-ui/vscode-goome">Open VSX</a> |
| JetBrains | <a href="https://plugins.jetbrains.com/plugin/36174-goome">goome</a> from the plugin marketplace |

</div>

<h3 align="center">📦 Repos 📦</h3>

<div align="center">

| Repo | What it is |
| :---: | :---: |
| <a href="https://github.com/goome-ui/c-goome"><b>c-goome</b></a> | The main one, the C library. Just drop in <code>goome.h</code> |
| <a href="https://github.com/goome-ui/csharp-goome"><b>csharp-goome</b></a> | C# bindings for .NET 8, with a Unity package and Unity mod templates |
| <a href="https://github.com/goome-ui/python-goome"><b>python-goome</b></a> | Python bindings over ctypes, nothing to build |
| <a href="https://github.com/goome-ui/java-goome"><b>java-goome</b></a> | Java 22+ bindings (FFM or LWJGL), plus Fabric and NeoForge mods |
| <a href="https://github.com/goome-ui/godot-goome"><b>godot-goome</b></a> | A GDExtension so you can use it in Godot |
| <a href="https://github.com/goome-ui/rust-goome"><b>rust-goome</b></a> | Rust crates, <code>goome</code> on top and <code>goome-sys</code> for the raw C |
| <a href="https://github.com/goome-ui/node-goome"><b>node-goome</b></a> | Node bindings, an N-API addon with prebuilds so theres nothing to compile |
| <a href="https://github.com/goome-ui/go-goome"><b>go-goome</b></a> | Go bindings over cgo, just <code>go get</code> it |
| <a href="https://github.com/goome-ui/zig-goome"><b>zig-goome</b></a> | A Zig package, zig cc builds goome.h for you |
| <a href="https://github.com/goome-ui/lua-goome"><b>lua-goome</b></a> | Lua 5.4 and LuaJIT module, works in LOVE too |
| <a href="https://github.com/goome-ui/obs-goome"><b>obs-goome</b></a> | OBS Studio source that draws a goome ui in your stream, timers, now playing, goal bars or your own builder files, and you can click it |
| <a href="https://github.com/goome-ui/docs"><b>docs</b></a> | The <a href="https://goome-ui.github.io/docs/">docs site</a> and the <a href="https://goome-ui.github.io/docs/builder/">UI builder</a> |
| <a href="https://github.com/goome-ui/examples"><b>examples</b></a> | Small apps and overlays you can copy from, mods and engine demos. The <a href="https://github.com/goome-ui/examples/releases/latest">apps to download</a> are on its releases |
| <a href="https://github.com/goome-ui/goome-cli"><b>goome-cli</b></a> | <code>goome new</code>, makes you a new project from a template |
| <a href="https://github.com/goome-ui/vscode-goome"><b>vscode-goome</b></a> | VS Code extension with a goome side panel, snippets, hover docs, new project and a builder preview. On the <a href="https://marketplace.visualstudio.com/items?itemName=goome-ui.vscode-goome">Marketplace</a> |
| <a href="https://github.com/goome-ui/jetbrains-goome"><b>jetbrains-goome</b></a> | Plugin for Rider and the other JetBrains IDEs, same features as the VS Code one. On the <a href="https://plugins.jetbrains.com/plugin/36174-goome">JetBrains Marketplace</a> |
| <a href="https://goome-ui.github.io/docs/templates/"><b>goome-app-template-*</b></a> | A tiny ready app to start from in <a href="https://github.com/goome-ui/goome-app-template-c">C</a>, <a href="https://github.com/goome-ui/goome-app-template-csharp">C#</a>, <a href="https://github.com/goome-ui/goome-app-template-python">Python</a>, <a href="https://github.com/goome-ui/goome-app-template-java">Java</a>, <a href="https://github.com/goome-ui/goome-app-template-godot">Godot</a>, <a href="https://github.com/goome-ui/goome-app-template-rust">Rust</a>, <a href="https://github.com/goome-ui/goome-app-template-node">Node</a>, <a href="https://github.com/goome-ui/goome-app-template-go">Go</a>, <a href="https://github.com/goome-ui/goome-app-template-zig">Zig</a> or <a href="https://github.com/goome-ui/goome-app-template-lua">Lua</a> |
| <a href="https://github.com/goome-ui/awesome-goome"><b>awesome-goome</b></a> | A list of everything made with goome, apps, mods, guides and tools. Add yours with a PR |

</div>

<h3 align="center">🫶 Contributors 🫶</h3>

<p align="center">
Thanks to everyone who helps out across all the goome repos, every fix, issue and PR counts!<br> <br>
<a href="https://github.com/goome-ui/c-goome/graphs/contributors"><img src="https://contrib.rocks/image?repo=goome-ui/c-goome" alt="contributors"></a>
</p>
