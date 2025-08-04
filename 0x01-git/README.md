# 0x01-git - Git Fundamentals

Welcome to the Git fundamentals project! This directory contains exercises and scripts designed to master version control using Git and collaborative development workflows.

## 📋 Table of Contents

- [About](#about)
- [Project Structure](#project-structure)
- [Files Description](#files-description)
- [How to Run](#how-to-run)
- [Learning Objectives](#learning-objectives)
- [Commands Used](#commands-used)
- [Author](#author)

## 🎯 About

This project is part of the ALX Software Engineering pre-course curriculum, focusing on:

- Git repository management and version control
- Creating and executing bash scripts
- Understanding file organization in development projects
- Implementing proper .gitignore configurations
- Mastering basic Git commands and workflows

## 📁 Project Structure

```
0x01-git/
├── README.md          # This documentation file
├── .gitignore         # Git ignore configuration
├── up_to_date         # Git update command reference
├── bash/              # Bash scripts directory
│   ├── alx            # ALX greeting script
│   └── school         # School status script
└── c/                 # C programming directory
    └── c_is_fun.c     # C programming placeholder file
```

## 📄 Files Description

### Bash Scripts (`bash/` directory)

#### `alx`
- **Purpose**: Displays ALX School greeting message
- **Content**: `echo "ALX School is so cool!"`
- **Usage**: Demonstrates basic bash scripting and echo commands

#### `school`
- **Purpose**: Shows school operational status
- **Content**: `echo "The school is open!"`
- **Usage**: Example of simple status reporting script

### C Programming (`c/` directory)

#### `c_is_fun.c`
- **Purpose**: Placeholder for C programming exercises
- **Status**: Currently empty, prepared for future C implementations
- **Usage**: Will contain C language code examples

### Configuration Files

#### `.gitignore`
- **Purpose**: Defines files and patterns Git should ignore
- **Content**: Ignores temporary files (`~`)
- **Usage**: Keeps repository clean from unwanted files

#### `up_to_date`
- **Purpose**: Quick reference for Git update commands
- **Content**: `git pull`
- **Usage**: Reminder for keeping repository synchronized

## 🚀 How to Run

### Execute Bash Scripts

```bash
# Navigate to the bash directory
cd bash

# Make scripts executable (if needed)
chmod +x alx school

# Run ALX script
./alx
# Output: ALX School is so cool!

# Run school script
./school
# Output: The school is open!
```

### Git Operations

```bash
# Update repository (as shown in up_to_date)
git pull

# Check status
git status

# Add files
git add .

# Commit changes
git commit -m "Update project files"

# Push to repository
git push origin main
```

## 🎯 Learning Objectives

By completing this project, you will be able to:

1. **Version Control Mastery**
   - Initialize and manage Git repositories
   - Use .gitignore effectively
   - Understand Git workflow commands

2. **Bash Scripting Basics**
   - Create executable shell scripts
   - Use echo for output display
   - Manage file permissions

3. **Project Organization**
   - Structure directories logically
   - Separate different file types
   - Maintain clean project hierarchy

4. **Collaborative Development**
   - Use Git for team collaboration
   - Keep repositories updated
   - Follow version control best practices

## 🛠 Commands Used

| Command | Purpose | Example |
|---------|---------|---------|
| `git pull` | Update local repository | `git pull origin main` |
| `echo` | Display text output | `echo "Hello World"` |
| `chmod +x` | Make file executable | `chmod +x script_name` |
| `git add` | Stage files for commit | `git add .` |
| `git commit` | Save changes | `git commit -m "message"` |

## 👨‍💻 Author

**Salman Eben**
- GitHub: [@salmaneben](https://github.com/salmaneben)
- Project: ALX Software Engineering Pre-Course

---

*This project demonstrates fundamental Git and shell scripting skills essential for software development. Each file serves a specific learning purpose in the ALX curriculum.*
