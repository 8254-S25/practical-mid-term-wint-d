## CST 8254 Practical Mid Term

**Your Name:**

```
Wint Damrhung (041147073)
```

**1.**

```
scp "C:\Users\Win\OneDrive\Desktop\AC Level 2\CST8254_Networking and Operations\practical-mid-term-wint-d\wintdamrhung.txt" pi@10.0.0.122:/home/pi/
```

**2. What command do you use to see a directory listing that includes the permissions of the files?**

```
ls -l
```

**3.**

```
ls -l > pr1.txt
```

**4. What are the permissions of the file you just created?**

```
-rw---xr-- 1 pi pi  890 Jun 18 11:55 pr1.txt
```

**5. What command do you use to display the folder you are currently working from?**

```
pwd
```

**6.**

```
chmod g=x pr1.txt
```

**7.**

```
mkdir midtermExam-301
```

**8. What are the permissions of this new folder  ?**

```
drwxr-xr-x 2 pi pi 4096 Jun 18 11:57 midtermExam-301
```

**9. What command do you use to list the ports your raspberry pi is listening to? Try it using the `-at` flag.**

```
netstat -at
```

**10.**

```
netstat -at > pr2.txt
```

**11.**

```
sftp pi@10.0.0.122
```

**12.**

```
put "C:\Users\Win\OneDrive\Desktop\AC Level 2\CST8254_Networking and Operations\practical-mid-term-wint-d\midtermPi.txt"
```

**13.** What does the command do?

```
pwd > mt.txt: saves current directory path to mt.txt
tree -l >> pr.txt: appends directory structure0 (tree view) to pr.txt
```

**14.**

```
sudo useradd wintdamrhung
```

 **15.**

```
sudo mkdir /home/wintdamrhung
sudo chown wintdamrhung:wintdamrhung /home/wintdamrhung
```

**16.**

```
sudo apt-get update
sudo apt-get install filezilla -y
```

