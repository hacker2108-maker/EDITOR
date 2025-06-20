# ✨ EDITOR - A Minimal Text Editor in C

A lightweight, terminal-based text editor written in C with syntax highlighting and keybindings inspired by modern editors.

## 🚀 Features

- **Syntax Highlighting** for C and Ruby (easily extensible)
- **Customizable Keybindings** (vim-like navigation)
- **Lightweight** - No dependencies beyond standard C libraries
- **Cross-platform** - Works on Linux, macOS, and other Unix-like systems
- **Persistent Configuration** (coming soon)

## ⌨️ Keybindings

| Command              | Key Combination      |
|----------------------|---------------------|
| Save file            | `Ctrl-S`            |
| Quit                 | `Ctrl-Q`            |
| Find                 | `Ctrl-F`            |
| Move cursor          | Arrow keys          |
| Page up/down         | `Page Up`/`Page Down`|
| Home/End             | `Home`/`End`        |
| Delete character     | `Backspace`/`Delete`|
| Insert newline       | `Enter`             |

## 📦 Installation

```bash
# Clone the repository
git clone https://github.com/hacker2108-maker/EDITOR.git
cd EDITOR

# Compile (requires gcc)
make

# Run
./editor [filename]
```

## 🔧 Building from Source

1. Ensure you have `gcc` installed
2. Run `make` in the project directory
3. The binary `editor` will be created

## 🌈 Syntax Highlighting Support

Currently supports:
- C/C++ (`.c`, `.h`, `.cpp`)
- Ruby (`.rb`)

Easy to extend for other languages by modifying `HLDB` in the source code.

## 📝 Todo

- [ ] Add more language syntax definitions
- [ ] Implement copy/paste functionality
- [ ] Add configuration file support
- [ ] Improve search/replace functionality

## 🤝 Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you'd like to change.

## 📜 License

[MIT](https://choosealicense.com/licenses/mit/)

---

💻 **Happy coding!** Let me know if you have any questions or suggestions for improvements.