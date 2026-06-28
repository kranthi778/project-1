# Part 2 – Linux Files and Directories

## 1. Present Working Directory

### Command
```bash
pwd
```

### Explanation
Shows the current working directory.

### Screenshot


![Alt text](screenshots/pwd.png)




## 2. List Files and Directories

### Command
```bash
ls
```

### Explanation
Lists the files and directories in the current location.

### Screenshot

![Alt text](screenshots/ls.png)




## 3. List Files with Details

### Command
```bash
ls -l
```

### Explanation
Shows files and directories in detail, including:
- Permissions
- Owner
- Group
- File size
- Date and time
- File name

### Screenshot

![Alt text](screenshots/ls-l.png)




## 4. List All Files (Including Hidden Files)

### Command
```bash
ls -la
```

### Explanation
Shows all files, including hidden ones, with detailed information.

### Screenshot

![Alt text](screenshots/ls-la.png)




## 5. Change Directory

### Command
```bash
cd <directory_name>
```

### Example
```bash
cd Documents
```

### Explanation
Changes the current working directory.

### Screenshot

![Alt text](screenshots/cd.png)



## 6. Go Back One Directory

### Command
```bash
cd ..
```

### Explanation
Moves to the parent directory.

### Screenshot

![Alt text](screenshots/cd-back.png)




## 7. Go to Home Directory

### Command
```bash
cd
```

### Explanation
Returns to the user's home directory.

### Screenshot

![Alt text](screenshots/cd-home.png)




## 8. Create a Directory

### Command
```bash
mkdir test_folder
```

### Explanation
Creates a new directory called `test_folder`.

### Screenshot

![Alt text](screenshots/mkdir.png)




## 9. Remove an Empty Directory

### Command
```bash
rmdir test_folder
```

### Explanation
Deletes an empty directory.

### Screenshot

![Alt text](screenshots/rmdir.png)




## 10. Create a File

### Command
```bash
touch file.txt
```

### Explanation
Creates a new empty file called `file.txt`.

### Screenshot

![Alt text](screenshots/touch.png)




## Summary

 Command | Purpose  |

  `pwd` | Shows current directory |
  `ls` | Lists files and directories |
  `ls -l` | Lists files with detailed information |
  `ls -la` | Lists all files, including hidden ones |
  `cd` | Changes directory |
  `cd ..` | Moves to the parent directory |
  `cd` | Goes to the home directory |
  `mkdir` | Creates a new directory |
  `rmdir` | Removes an empty directory |
  `touch` | Creates a new file |
