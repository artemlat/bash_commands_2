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

### 5. Create empty file tf_1.txt:

```
artem@DESKTOP-4FHC137 MINGW64 /d/linux_terminal/dir_1
$ touch tf_1.txt
```

### 6. Create a file tf_2.txt with lines  
- the first 1
- the second 2
- the third 3  
using command `cat`:

```
artem@DESKTOP-4FHC137 MINGW64 /d/linux_terminal/dir_1
$ cat > tf_2.txt
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
$ cat >> ../tf_2.txt
the sec 3
```

*Press `Ctrl+C`*

### 12. Add to the file tf_3.txt a line “the SeCoNd 2” using `cat` command:

```
artem@DESKTOP-4FHC137 MINGW64 /d/linux_terminal/dir_1/inner_dir_1
$ cat >> tf_3.txt
the SeCoNd 2
```

*Press `Ctrl+C`*

### 13. Add to the file tf_2.txt a line “the seConD 2” using `cat` command:

```
artem@DESKTOP-4FHC137 MINGW64 /d/linux_terminal/dir_1/inner_dir_1
$ cat >> ../tf_2.txt
the seConD 2
```
*Press `Ctrl+C`*

### 14. Create a file tf_4.txt with 15 lines inside:

```
artem@DESKTOP-4FHC137 MINGW64 /d/linux_terminal/dir_1/inner_dir_1
$ seq 15 | cat > tf_4.txt
```

### 15. Create a file tF_5.txt with 13 lines inside:

```
artem@DESKTOP-4FHC137 MINGW64 /d/linux_terminal/dir_1/inner_dir_1
$ seq 13 | cat > tF_5.txt
```

### 16. Show content list of the direction:

```
artem@DESKTOP-4FHC137 MINGW64 /d/linux_terminal/dir_1/inner_dir_1
$ ls -la
total 2
drwxr-xr-x 1 artem 197609  0 May  3 23:07 ./
drwxr-xr-x 1 artem 197609  0 May  3 23:06 ../
-rw-r--r-- 1 artem 197609 30 May  3 22:15 tF_5.txt
-rw-r--r-- 1 artem 197609 66 May  3 19:48 tf_3.txt
-rw-r--r-- 1 artem 197609  0 May  3 22:51 tf_4.txt
```

### 17. Exit the folder inner_dir_1:

```
artem@DESKTOP-4FHC137 MINGW64 /d/linux_terminal/dir_1/inner_dir_1
$ cd ..
```

### 18. Show content of the file tf_3.txt

```
artem@DESKTOP-4FHC137 MINGW64 /d/linux_terminal/dir_1
$ cat inner_dir_1/tf_3.txt
11111
22222
33333
44444
55555
the second 2
the sec 2
the SeCoNd 2
```

### 19. Find path to tf_4.txt

```
artem@DESKTOP-4FHC137 MINGW64 /d/linux_terminal/dir_1
$ find -name tf_4.txt
./inner_dir_1/tf_4.txt
```

### 20. Clear content of the file tf_4.txt without deletting of the file:

```
artem@DESKTOP-4FHC137 MINGW64 /d/linux_terminal/dir_1
$ cat > inner_dir_1/tf_4.txt
```

*Press `Ctrl+C`*

### 21. Find path to files that have “tf” in its name:

```
artem@DESKTOP-4FHC137 MINGW64 /d/linux_terminal/dir_1
$ find . -name "*tf*"
./inner_dir_1/tf_3.txt
./inner_dir_1/tf_4.txt
./tf_1.txt
./tf_2.txt
```

### 22. 











