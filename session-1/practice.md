
### **File 2: `session-1/practice.md`**
````markdown
# Terminal Practice - Session 1

## 📅 Date: March 4, 2026

## 💻 Commands Practiced:

```bash
# Check current location
pwd

# Move to coding folder
cd coding
pwd

# Check contents
ls -a

# Go back home
cd ~
pwd

# Create folder
mkdir folder1
ls -a

# Create files
touch file1.py
touch folder1/file2.txt

# Navigate into folder
cd folder1
ls -a

# Go back
cd ..
pwd

# Remove file
rm file1.py

# Remove folder (empty it first)
rm folder1/file2.txt
rmdir folder1

# Check removal
ls -a

# File content operations
echo "Data Nerd"
touch file1.txt

# Write to file (overwrites)
echo "Data Analyst" > file1.txt
cat file1.txt

# Write to file (overwrites again)
echo "Data Science" > file1.txt
cat file1.txt

# Append to file (adds to existing)
echo "Data Engineering" >> file1.txt
cat file1.txt

# View file from beginning
head file1.txt

# View specific number of lines
head -n1 file1.txt
head -n2 file1.txt
