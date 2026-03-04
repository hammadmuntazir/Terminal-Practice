# Basic Terminal Commands Reference

## 📍 Navigation Commands

| Command | Description | Example |
|---------|-------------|---------|
| `pwd` | Print current directory path | `pwd` → /c/Users/name |
| `cd` | Change directory | `cd Documents` |
| `cd ..` | Go to parent directory | `cd ..` |
| `cd ~` | Go to home directory | `cd ~` |
| `cd /` | Go to root directory | `cd /` |
| `ls` | List files and folders | `ls` |
| `ls -a` | List all (including hidden) | `ls -a` |
| `ls -l` | List with details | `ls -l` |
| `ls -la` | List all with details | `ls -la` |

## 📁 File/Folder Operations

| Command | Description | Example |
|---------|-------------|---------|
| `mkdir` | Create directory | `mkdir newfolder` |
| `mkdir -p` | Create nested directories | `mkdir -p parent/child` |
| `touch` | Create empty file | `touch file.txt` |
| `rm` | Remove file | `rm file.txt` |
| `rmdir` | Remove empty directory | `rmdir emptyfolder` |
| `rm -r` | Remove directory + contents | `rm -r folder` |
| `rm -f` | Force remove (no confirmation) | `rm -f file.txt` |
| `cp` | Copy file/folder | `cp file1.txt file2.txt` |
| `cp -r` | Copy recursively | `cp -r folder1 folder2` |
| `mv` | Move/rename file | `mv old.txt new.txt` |

## 📝 File Content Commands

| Command | Description | Example |
|---------|-------------|---------|
| `cat` | View entire file | `cat file.txt` |
| `head` | View first 10 lines | `head file.txt` |
| `head -n5` | View first 5 lines | `head -n5 file.txt` |
| `tail` | View last 10 lines | `tail file.txt` |
| `tail -n5` | View last 5 lines | `tail -n5 file.txt` |
| `echo` | Print text | `echo "Hello"` |
| `echo >` | Write to file (overwrite) | `echo "text" > file.txt` |
| `echo >>` | Append to file | `echo "text" >> file.txt` |
| `wc` | Count lines/words | `wc file.txt` |
| `wc -l` | Count lines only | `wc -l file.txt` |

## 🆘 Help Commands

| Command | Description | Example |
|---------|-------------|---------|
| `command --help` | Show help | `ls --help` |
| `man command` | Show manual | `man ls` |
| `info command` | Show info page | `info ls` |
| `whatis` | Brief description | `whatis ls` |

## ⚡ Useful Shortcuts

| Shortcut | Function |
|----------|----------|
| `Tab` | Auto-complete file/folder names |
| `↑` `↓` | Navigate command history |
| `Ctrl+C` | Cancel current command |
| `Ctrl+L` | Clear screen |
| `Ctrl+D` | Exit terminal |
| `Ctrl+A` | Go to start of line |
| `Ctrl+E` | Go to end of line |
| `Ctrl+U` | Clear current line |
| `!!` | Repeat last command |

## 📌 Pro Tips

1. **Use Tab** - Saves time and prevents typos
2. **Check before delete** - Always `ls` before `rm`
3. **Quote spaces** - Use quotes for names with spaces: `mkdir "My Folder"`
4. **Escape characters** - Use `\` for special chars: `touch file\ with\ spaces.txt`
5. **Command history** - Type `history` to see all previous commands

## 🚨 Dangerous Commands (Use Carefully!)

```bash
# These can delete everything - be VERY careful!
rm -rf /          # NEVER RUN THIS!
rm -rf *          # Deletes all files in current directory
rm -rf .          # Deletes current directory and everything in it
