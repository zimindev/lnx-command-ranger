# 🧭 Quick Guide to Using `ranger` — Terminal File Manager

## What is `ranger`?
`ranger` is a terminal-based file manager that shows directory contents in a multi-column layout.  
It’s fast, lightweight, and designed for keyboard users (especially if you like Vim-style navigation).

---

## 📥 Installing ranger

- On Debian/Ubuntu:
```bash
sudo apt install ranger
````

* On Arch Linux:

```bash
sudo pacman -S ranger
```

* On Fedora:

```bash
sudo dnf install ranger
```

---

## 🚀 Starting ranger

```bash
ranger
```

* Opens ranger in your current directory.

---

## 🗂 Basic Navigation

| Action       | Key/Command         | Description                      |
| ------------ | ------------------- | -------------------------------- |
| Move down    | `j`                 | Move cursor down one file/folder |
| Move up      | `k`                 | Move cursor up one file/folder   |
| Enter folder | `l` or `Enter`      | Open selected folder             |
| Go back / Up | `h`                 | Go to parent directory           |
| Open file    | `Enter`             | Open file with default program   |
| Preview file | Automatically shown | Preview text files and images    |

---

## 📂 Managing Files and Folders

| Action                   | Key/Command          | Description                                          |
| ------------------------ | -------------------- | ---------------------------------------------------- |
| Create folder            | `:mkdir folder_name` | Create a new folder                                  |
| Create empty file        | `:touch file_name`   | Create empty file                                    |
| Rename file/folder       | `cw`                 | Change (rename) current file/folder name (vim-style) |
| Delete file/folder       | `dd`                 | Delete selected file/folder                          |
| Copy file/folder         | `yy`                 | Yank (copy) selected file/folder                     |
| Paste copied file/folder | `pp`                 | Paste copied file/folder                             |
| Move file/folder         | `:move target_path`  | Move current file/folder to target path              |

---

## 🔍 Searching

| Action              | Key/Command         | Description                    |
| ------------------- | ------------------- | ------------------------------ |
| Search file         | `/` + type filename | Search files in current folder |
| Filter by extension | `:filter *.txt`     | Show only files with .txt      |

---

## 🔧 Other Useful Commands

| Command                | Description                              |
| ---------------------- | ---------------------------------------- |
| `:quit` or `q`         | Quit ranger                              |
| `:shell` or `!command` | Run shell command without leaving ranger |
| `zh`                   | Toggle hidden files on/off               |
| `r`                    | Reload current directory                 |

---

## 🌟 Tips

* `ranger` config files are in `~/.config/ranger/`.
* Use `:help` inside ranger for interactive help.
* Press `?` for keybindings cheat sheet inside ranger.
