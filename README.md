# 19CS416-CS-Ex-3-Linux-Commands
# Name: Sanjit A , Register no: 212224220087

**Linux** is an open-source operating system, and its kernel is the heart of the OS, facilitating communication between hardware and software. One of the key advantages of Linux is its customizability; developers can modify the Linux kernel to create their own tailored operating systems.

## Linux Commands

Linux commands are executed in the terminal, which is case-sensitive. This guide covers some basic and advanced commands used in Linux.

### 1. `ls` Command

The `ls` command is used to display a list of contents in a directory.

**Syntax:** 
```bash
ls
```

**Output:**
![435972849-08e910a1-293d-4acb-88ef-44049604437f](https://github.com/user-attachments/assets/d54fadb2-a577-4f4b-8060-6f87c26eb28a)

### 2. `pwd` Command

The `pwd` command displays the location of the current working directory.

**Syntax:**
```bash
pwd
```

**Output:**
![435972921-7da7918b-78fa-4bc4-a535-ba2f3e7f7919](https://github.com/user-attachments/assets/b7adbdcf-990c-4702-98ab-3903f5a2a373)

### 3. `mkdir` Command

The `mkdir` command is used to create a new directory.

**Syntax:**
```bash
mkdir <directory_name>
```

**Output:**
![435973254-818e8fe8-1344-4366-aebb-c9536c4c262c](https://github.com/user-attachments/assets/28e7a82d-aea8-44b8-b83b-ec07996e2f9a)

### 4. `rmdir` Command

The `rmdir` command is used to delete a directory.

**Syntax:**
```bash
rmdir <directory_name>
```

**Output:**
![435973309-055b94cc-1d37-4cb0-b4fc-84e091e63bd1](https://github.com/user-attachments/assets/13de2141-8d92-427c-b01f-369129347193)

### 5. `cd` Command

The `cd` command is used to change the current directory.

**Syntax:**
```bash
cd <directory_name>
```

**Output:**
![435973346-b7f87ccc-fd79-4679-a659-0c9d5087cc19](https://github.com/user-attachments/assets/e8d1f024-11f0-4d78-bd05-7f77c95ebaed)

### 6. `cat` Command

The `cat` command is used to create, display, and concatenate files.

**Syntax:**
```bash
cat [OPTION]... [FILE]...
```

**Output:**
![435973403-d681c5b6-45cf-4b12-bf18-aa30ff73d74d](https://github.com/user-attachments/assets/7309e55f-9e6e-4429-94c3-204843d308a2)

### 7. `cp` Command

The `cp` command is used to copy files or directories.

**Syntax:**
```bash
cp <source_file> <destination_file>
```

**Output:**
![435973500-10f1fc72-b422-4d2c-8cc8-56deb7a82259](https://github.com/user-attachments/assets/d2032085-775f-4bbc-b6af-757746e68b6e)

### 8. `gedit` Command

`gedit` is a general-purpose text editor used to create and edit text files.

**Syntax:**
```bash
gedit <file_name>
```

**Output:**
![435973549-96f3010a-ab97-4b22-857a-8fbbc1332981](https://github.com/user-attachments/assets/cbebd8ec-adfb-46ff-93fd-6e6229a02959)

### 9. `su` Command

The `su` command provides administrative access to another user.

**Syntax:**
```bash
su <username>
```

**Output:**
![435973596-7eea654a-815e-458b-a872-1730fceb3ace](https://github.com/user-attachments/assets/741f2972-0cee-40d3-9a77-23b78f0449b6)

### 10. `mv` Command

The `mv` command is used to move a file or directory from one location to another.

**Syntax:**
```bash
mv <file_name> <directory_path>
```

**Output:**
![435973639-2184c683-f944-4335-93e5-3803e81d5fa3](https://github.com/user-attachments/assets/cd304188-a2e7-45c7-a793-3befb7f0f9d7)

### 11. `rename` Command

The `rename` command is used to rename files.

**Syntax:**
```bash
rename 's/old-name/new-name/' <files>
```

**Output:**
![435973760-4354db03-5d97-4f4f-a0f7-d41e419fe68f](https://github.com/user-attachments/assets/2bc5351c-2aa4-4a21-b5ec-dad68133e6db)

### 12. `head` Command

The `head` command displays the first 10 lines of a file.

**Syntax:**
```bash
head <file_name>
```

**Output:**
![435973830-c2c02321-d4bc-4167-8e7f-399a4b0231cf](https://github.com/user-attachments/assets/977e9478-a581-4f15-97c9-b994720fb54a)

### 13. `tail` Command

The `tail` command displays the last 10 lines of a file.

**Syntax:**
```bash
tail <file_name>
```

**Output:**
![435973889-b7098325-f196-4521-9a48-cb8688bc2fd7](https://github.com/user-attachments/assets/13a6b32b-5105-4b12-b041-9136c33f261e)

### 14. `id` Command

The `id` command displays the user ID (UID) and group ID (GID).

**Syntax:**
```bash
id
```

**Output:**
![435973949-4d20d704-f0dc-459c-9852-1cee6fbdb672](https://github.com/user-attachments/assets/305b8b27-4f29-4a3a-9e8a-edf41dde5e8b)

### 15. `grep` Command

The `grep` command is used to search for a pattern within files.

**Syntax:**
```bash
command | grep <search_word>
```

**Output:**
![435974008-7e3a98e4-e343-4876-9043-78453aa0761a](https://github.com/user-attachments/assets/78da2837-f1af-46dd-8f77-296bfdcd67dc)

### 16. `tr` Command

The `tr` command is used to translate or delete characters.

**Syntax:**
```bash
command | tr <old> <new>
```

**Output:**
![435974113-7f67a36c-0a14-4451-9a32-2d3818c8521c](https://github.com/user-attachments/assets/a51e1fb1-e068-43f5-87d9-7e513f39d84f)

### 17. `chmod` Command

The `chmod` command is used to change the access mode (permissions) of a file.

**Syntax:**
```bash
chmod <options> <permissions> <file_name>
```

**Output:**
![435974193-15c627f3-8d9d-43fb-a7e5-4d3b35dba852](https://github.com/user-attachments/assets/d095189f-fa1b-4be6-8193-6e5468e87101)

### 18. `tar` Command

The `tar` command is used to create or extract archive files.

**Syntax:**
```bash
tar [options] [archive-file] [files_to_archive]
```

**Output:**
![435974290-a5d4222a-0fe3-4466-beab-9f997ccdd056](https://github.com/user-attachments/assets/56fbbb7a-e046-468c-bd20-0b465262db3b)

### 19. `chown` Command

The `chown` command is used to change the ownership of a file.

**Syntax:**
```bash
chown <owner_name> <file_name>
```

**Output:**
![435974353-145be69e-00c3-425c-980e-95e0b7169211](https://github.com/user-attachments/assets/3aa94a90-6c1f-48e1-895c-f41f59ee6d83)

### 20. `make` Command

The `make` command is used to build and maintain groups of programs.

**Syntax:**
```bash
make [-f makefile] [options] [targets]
```

**Output:**
![435974408-9f1d6f92-46e7-4504-8fe9-df7dff743942](https://github.com/user-attachments/assets/17c73ea2-5edd-42d8-992c-f60bda1265f9)

### 21. `ifconfig` Command

The `ifconfig` command is used to configure network interfaces.

**Syntax:**
```bash
ifconfig [options] [interface]
```

**Output:**
![421790753-4ddf3532-2c94-48ea-866d-ec8c013b942e](https://github.com/user-attachments/assets/a7db8363-91dd-4b71-b4fb-0b07c0d0a9fd)

### 22. `chmod 777` Command

The `chmod 777` command gives read, write, and execute permissions to the owner, group, and others.

**Syntax:**
```bash
chmod 777 <file_name>
chmod -R 777 /path/to/file/or/folder
```

**Output:**
![435974474-1ffd1f72-4653-4c8e-b590-e5790f1c4a76](https://github.com/user-attachments/assets/ac68107c-b5b4-4ae5-882d-48d52a847167)

### 23. `host` Command

The `host` command is used to display the IP address for a given domain name.

**Syntax:**
```bash
host <domain_name> or <ip_address>
```

**Output:**
![435974599-4deeb987-fc39-4fe9-8c39-018a7e69264f](https://github.com/user-attachments/assets/7cf9d300-b6b4-41db-a951-a2a53b115c24)

### 24. `gzip` Command

The `gzip` command is used to compress files, replacing the original file with a compressed one with a `.gz` extension.

**Syntax:**
```bash
gzip <file1> <file2> <file3>...
```

**Output:**
![435974642-054f8bab-1e08-47c6-b202-891b325ebbeb](https://github.com/user-attachments/assets/ff0e119e-9065-4bb6-b550-4fb4dfa9ce3c)

### 25. `sort` Command

The `sort` command is used to sort the contents of a file alphabetically.

**Syntax:**
```bash
sort <file_name>
```

**Output:**
![435974698-ead16232-a880-431f-8c79-eb3048c32748](https://github.com/user-attachments/assets/1b0ba6d8-8fc9-4a13-93e9-d74371441496)

### 26. `cal` Command

The `cal` command displays the current month's calendar with the current date highlighted.

**Syntax:**
```bash
cal
```

**Output:**
![435974753-780edc21-831f-4bd5-8967-62d7820d3720](https://github.com/user-attachments/assets/e816154d-5da8-4212-8376-76557fa97f83)

### 27. `clear` Command

The `clear` command clears the terminal screen.

**Syntax:**
```bash
clear
```

**Output:**
![435974793-c9c33a55-ee78-40ca-af6e-94724e2edac2](https://github.com/user-attachments/assets/afe3fc54-edb3-44f4-8fe1-824237880e35)

### 28. `mail` Command

The `mail` command is used to send emails from the command line.

**Syntax:**
```bash
mail
```

**Output:**
![435974843-a923dc29-2a2e-475a-a23d-eccbb6574e9f](https://github.com/user-attachments/assets/cefa0121-7161-4f7f-a88c-aed593fd9a62)

### 29. `df` Command

The `df` command displays the disk space usage of file systems.

**Syntax:**
```bash
df
```

**Output:**
![435974961-74cd05dd-0029-472f-a7d8-6fb78fd3d5c1](https://github.com/user-attachments/assets/468258ac-c42b-48ad-ab50-93cc205156e6)

### 30. `find` Command

The `find` command is used to search for files in a directory hierarchy.

**Syntax:**
```bash
find <directory> -name <file_name>
```

**Output:**
![435975023-c26f979a-4d8b-41a5-8b7d-acc217f0f195](https://github.com/user-attachments/assets/6a6e4879-c4b1-4570-ace0-8cad1e0843f2)

## Result
