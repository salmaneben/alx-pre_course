# Bash Scripts Directory

This directory contains bash shell scripts for the ALX pre-course Git fundamentals project.

## 📋 Table of Contents

- [About](#about)
- [Scripts Overview](#scripts-overview)
- [Usage](#usage)
- [Learning Objectives](#learning-objectives)
- [Requirements](#requirements)
- [Author](#author)

## 🎯 About

This directory demonstrates basic bash scripting concepts as part of the ALX Software Engineering curriculum. The scripts showcase fundamental shell programming principles including:

- Script structure and shebang usage
- Echo command for output display
- Executable file permissions
- Basic shell script execution

## 📄 Scripts Overview

### `alx`
**Purpose**: Display ALX School greeting message  
**Content**: 
```bash
#!/bin/bash
echo "ALX School is so cool!"
```
**Function**: Demonstrates basic bash script structure and text output

### `school`
**Purpose**: Display school operational status  
**Content**: 
```bash
#!/bin/bash
echo "The school is open!"
```
**Function**: Shows simple status reporting through shell scripts

## 🚀 Usage

### Making Scripts Executable
```bash
# Navigate to the bash directory
cd bash

# Make scripts executable
chmod +x alx
chmod +x school

# Or make all scripts executable at once
chmod +x *
```

### Running the Scripts
```bash
# Execute ALX script
./alx
# Expected Output: ALX School is so cool!

# Execute school script
./school
# Expected Output: The school is open!

# Alternative execution method
bash alx
bash school
```

### Viewing Script Contents
```bash
# Display script content
cat alx
cat school

# Or use less for longer scripts
less alx
```

## 🎯 Learning Objectives

After working with these scripts, you will understand:

1. **Shell Script Basics**
   - Proper shebang (`#!/bin/bash`) usage
   - Script file structure and organization
   - Echo command for text output

2. **File Permissions**
   - Making files executable with `chmod +x`
   - Understanding executable permissions in Unix/Linux
   - Different methods of script execution

3. **Script Execution**
   - Direct execution with `./script_name`
   - Execution through interpreter: `bash script_name`
   - Path resolution and script location

4. **Development Practices**
   - Clear, descriptive script content
   - Consistent coding style
   - Meaningful script names and purposes

## 📋 Requirements

- **Shell**: Bash (Bourne Again Shell)
- **OS**: Unix/Linux environment (or Windows with Git Bash)
- **Permissions**: Execute permission on script files
- **Editor**: Any text editor (vim, nano, VS Code, etc.)

## 🔧 Best Practices Demonstrated

1. **Shebang Line**: All scripts start with `#!/bin/bash`
2. **Simple Output**: Clear, concise echo statements
3. **Meaningful Names**: Script names reflect their purpose
4. **Executable Format**: Scripts are designed to be directly executable

## 📊 Script Analysis

| Script | Lines | Purpose | Complexity |
|--------|-------|---------|------------|
| `alx` | 2 | Greeting display | Beginner |
| `school` | 2 | Status reporting | Beginner |

## 🔍 Common Commands

```bash
# Check script permissions
ls -la alx school

# View all scripts in directory
ls -la *.sh

# Execute all scripts
for script in alx school; do ./$script; done
```

## 👨‍💻 Author

**Salman Eben**
- GitHub: [@salmaneben](https://github.com/salmaneben)
- Project: ALX Software Engineering Pre-Course - 0x01-git

---

*These bash scripts serve as an introduction to shell scripting concepts in the ALX Software Engineering curriculum. Each script demonstrates fundamental bash programming principles essential for system administration and development automation.*
