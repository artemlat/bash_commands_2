# #2 Linux terminal (GitBash) commands  
*Here I continued to learn using of basic Linux terminal commands. There are some of them:*  
### 1. Create a folder dir_1:

```
artem@DESKTOP-4FHC137 MINGW64 /d/linux_terminal
$ mkdir dir_1
```

### 2. Go to the folder dir_1:

```
artem@DESKTOP-4FHC137 MINGW64 /d/linux_terminal
$ cd dir_1
```

### 3. Create a folder inner_dir_1:

```
artem@DESKTOP-4FHC137 MINGW64 /d/linux_terminal/dir_1
$ mkdir inner_dir_1
```

### 4. Check where I am: 

```
artem@DESKTOP-4FHC137 MINGW64 /d/linux_terminal/dir_1
$ pwd
/d/linux_terminal/dir_1
```

### 5. Create empty file tf_1.txt in the inner_dir_1 folder not entering it:

```
artem@DESKTOP-4FHC137 MINGW64 /d/linux_terminal/dir_1
$ touch inner_dir_1/tf_1.txt
```

### 6. Create a file tf_2.txt with lines  
- the first 1
- the second 2
- the third 3  
using command `cat` in the inner_dir_1 folder not entering it:

```
artem@DESKTOP-4FHC137 MINGW64 /d/linux_terminal/dir_1
$ cat > inner_dir_1/tf_2.txt
- the first 1
- the second 2
- the third 3
```

*Press `Ctrl+C`*

### 7. Go to the folder inner_dir_1:

```
artem@DESKTOP-4FHC137 MINGW64 /d/linux_terminal/dir_1
$ cd inner_dir_1/
```

### 8. Create file tf_3.txt with any lines using `cat` command:

```
artem@DESKTOP-4FHC137 MINGW64 /d/linux_terminal/dir_1/inner_dir_1
$ cat > tf_3.txt
11111
22222
33333
44444
55555
```

*Press `Ctrl+C`*

### 9. Add to the file tf_3.txt a line “the second 2” using `cat` command:

```
artem@DESKTOP-4FHC137 MINGW64 /d/linux_terminal/dir_1/inner_dir_1
$ cat >> tf_3.txt
the second 2
```

*Press `Ctrl+C`*

### 10. Add to the file tf_3.txt a line “the sec 2” using `cat` command:

```
artem@DESKTOP-4FHC137 MINGW64 /d/linux_terminal/dir_1/inner_dir_1
$ cat >> tf_3.txt
the sec 2
```

*Press `Ctrl+C`*

### 11. Add to the file tf_2.txt a line “the sec 3” using `cat` command:

```
artem@DESKTOP-4FHC137 MINGW64 /d/linux_terminal/dir_1/inner_dir_1
$ cat >> tf_2.txt
the sec 3
```

*Press `Ctrl+C`*

### 12. 








