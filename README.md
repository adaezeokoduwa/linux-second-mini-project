# linux-second-mini-project
# Side Hustle Task 1 - Linux Terminal Directory Operations

This document explains how I successfully completed **Side Hustle Task 1**, which involved working with directories inside a Linux terminal. The task includes creating directories, navigating the file system, and displaying paths.

---

##  Task Breakdown

### 1. Navigating to the `/usr` Directory

To begin, I opened my terminal. I was initially located in my home directory:

```
ubuntu@ubuntu-vm:~$
```

I navigated to the `/usr` directory using the command:

```
cd /usr
```

Then, I confirmed my current path with:

```
pwd
```

Output:
```
/usr
```

---

###  2. Creating a Directory Named `photos` Inside `/usr`

Since `/usr` is a system directory and requires administrative privileges, I used `sudo` to create the directory:

```
sudo mkdir /usr/photos
```

---

### âœ… 3. Navigating into the `photos` Directory

I moved into the newly created `photos` directory:

```bash
cd /usr/photos
```

Then I verified my location:

```bash
pwd
```

Output:
```bash
/usr/photos
```

---

### âœ… 4. Creating 3 Random Directories Inside `photos`

I chose to name the directories `vacation`, `family`, and `events`. I created them using:

```bash
sudo mkdir vacation family events
```

---

### âœ… 5. Displaying the Newly Created Directories

To verify the directories were created successfully, I listed the contents of the `photos` directory:

```bash
ls
```

Output:
```bash
vacation  family  events
```

---

### âœ… 6. Navigating Into One of the Directories

I navigated into the `vacation` directory:

```bash
cd vacation
```

---

### âœ… 7. Showing the Full Path of the Current Location

Finally, I displayed the full path of my current working directory using:

```bash
pwd
```

Output:
```bash
/usr/photos/vacation
```

---

## âœ… Conclusion

This task helped reinforce my understanding of basic Linux terminal commands such as `cd`, `mkdir`, `ls`, and `pwd`. I also practiced using `sudo` for administrative tasks. All steps were completed successfully.
