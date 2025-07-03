# linux-second-mini-project
# Side Hustle Task 1 - Linux Terminal Dire

###  2. Creating a Directory Named `photos` Inside `/usr`

Since `/usr` is a system directory and requires administrative privileges, I used `sudo` to create the directory:

```
sudo mkdir /usr/photos
```

---

![](https://github.com/adaezeokoduwa/linux-second-mini-project/blob/main/pics/creating-folders.png?raw=true)
### 3. Navigating into the `photos` Directory

I moved into the newly created `photos` directory:

```
cd /usr/photos
```

Then I verified my location:

```
pwd
```

Output:
```
/usr/photos
```

---

### 4. Creating 3 Random Directories Inside `photos`

I chose to name the directories `3mtt`, `darey`, and `training`. I created them using:

```
sudo mkdir 3mtt
sudo mkdir darey
sudo mkdir training

```

---
![](https://github.com/adaezeokoduwa/linux-second-mini-project/blob/main/pics/folders-created.png?raw=true)

###  5. Displaying the Newly Created Directories

To verify the directories were created successfully, I listed the contents of the `photos` directory:

```bash
ls
```

Output:
```
3mtt    darey   training
```

---

### 6. Navigating Into One of the Directories

I navigated into the `darey` directory:

```
cd darey
```

---

### 7. Showing the Full Path of the Current Location

Finally, I displayed the full path of my current working directory using:

```
pwd
```

Output:
```
/usr/photos/darey
```

---
![](https://github.com/adaezeokoduwa/linux-second-mini-project/blob/main/pics/showing%20path.png?raw=true)
## Conclusion

This task helped reinforce my understanding of basic Linux terminal commands such as `cd`, `mkdir`, `ls`, and `pwd`. I also practiced using `sudo` for administrative tasks. All steps were completed successfully.
