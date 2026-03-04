# Session 1 Notes - March 4, 2026

## Key Learnings

### 1. Directory Navigation
- `~` (tilde) always points to home directory
- `.` (single dot) = current directory
- `..` (double dot) = parent directory
- Paths can be absolute (/c/Users/...) or relative (../folder)

### 2. File Operations
- Files must be removed from directory before removing the directory
- `rm -r` removes everything recursively - use with caution!
- Always check with `ls` before removing anything

### 3. Content Redirection
- Single `>` creates new file or overwrites existing
- Double `>>` appends to existing file
- If file doesn't exist, both `>` and `>>` create it

### 4. Viewing Files
- `cat` shows entire file at once
- `head` shows only beginning (default 10 lines)
- Use `head -n` to specify number of lines

## Commands Cheat Sheet

| Command | Example | Purpose |
|---------|---------|---------|
| `pwd` | `pwd` | Print working directory |
| `cd` | `cd coding` | Change directory |
| `ls` | `ls -a` | List contents |
| `mkdir` | `mkdir folder1` | Make directory |
| `touch` | `touch file.txt` | Create file |
| `rm` | `rm file.txt` | Remove file |
| `rmdir` | `rmdir folder1` | Remove empty directory |
| `rm -r` | `rm -r folder1` | Remove directory + contents |
| `echo` | `echo "hello"` | Print text |
| `cat` | `cat file.txt` | View file |
| `head` | `head -n5 file.txt` | View first lines |
| `>` | `echo "text" > file.txt` | Write to file |
| `>>` | `echo "text" >> file.txt` | Append to file |

## Mistakes to Avoid
- Don't use `rm -r` without checking current directory first
- Don't confuse `>` (overwrite) with `>>` (append)
- Don't forget to check if you're in the right directory before deleting

## Questions for Next Session
- How to copy files?
- How to move files?
- How to search for files?
