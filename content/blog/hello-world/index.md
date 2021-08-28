---
title: Basic Linux/Unix Commands We should know
date: "2015-05-01T22:12:03.284Z"
description: "Linux/Unix commands"
---

**Background**
I was a window user, I never thought to use Linux in my life time. But Suddenly it changed my world and I don't want to go back to the windows because **I fell in love with linux**.
I am not a system admin now but I work on few Linux distribution which made me realized that whoever is going to learn Linux, they should know these basic Linux commands, which will help them to save few times and practice.

**1. mkdir**:

mkdir stands for **make directory** i.e. this command is responsible to create directories.

**Syntax**:

```
mkdir [FILENAME]
```

**Example:**

![Alt Text](https://dev-to-uploads.s3.amazonaws.com/i/lng9oygdt02owq9scqe9.PNG)

**2. ls**:

**ls** stands for list i.e. list the names of files and directories in current working directory.

**Example:**

![Alt Text](https://dev-to-uploads.s3.amazonaws.com/i/bq0d029lvq1aitvgn50e.PNG)

**Syntax**:

```
ls [OPTIONS]
```

There are various options which support **ls** command. Listing few of them in below.

- **ls -a :** list all the files including hidden files. even though it include "." and ".." files.

- **Example:**

![Alt Text](https://dev-to-uploads.s3.amazonaws.com/i/bfc7szulkfdf9vfmfw0f.PNG)

- **ls -A :** list all the files including hidden files except "." and ".." files.

  **Example:**

![Alt Text](https://dev-to-uploads.s3.amazonaws.com/i/o68pmxzg6k1tht4jx0ex.PNG)

- **ls -r:** list the files in descending order name excluding hidden files.

  **Example:**

![Alt Text](https://dev-to-uploads.s3.amazonaws.com/i/5fpuznsfjvng59790qpq.PNG)

- **ls -R:** list the files recursively and it shows the files inside directories.

  **Example:**

![Alt Text](https://dev-to-uploads.s3.amazonaws.com/i/7ibzdkb1b6r1cg3yuy59.PNG)

- **ls -l:** list the files in long format i.e. name of each file, owner name, group name, size, index number, timestamp, permission etc.

  **Example:**

![Alt Text](https://dev-to-uploads.s3.amazonaws.com/i/4rfeomke1otpnmbhqivk.PNG)

- **ls -g:** list the files in long format but without owner name.

  **Example:**

![Alt Text](https://dev-to-uploads.s3.amazonaws.com/i/bd0qgr4xmrbovx3ngo9h.PNG)

- **ls -o:** list the files in long format but without group name.

  **Example:**

![Alt Text](https://dev-to-uploads.s3.amazonaws.com/i/rz84x02nu8lxsivql0x1.PNG)

- **ls -s:** list the files with their sizes.

  **Example:**

![Alt Text](https://dev-to-uploads.s3.amazonaws.com/i/943ivd11g6wseu10ivwr.PNG)

- **ls -S:** sort the files with their sizes.

  **Example:**

![Alt Text](https://dev-to-uploads.s3.amazonaws.com/i/5yvdlfrhhnd481s4dniy.PNG)

- **ls -i:** list the files with their index numbers.

  **Example:**

![Alt Text](https://dev-to-uploads.s3.amazonaws.com/i/ebkndeast55hyg1darcy.PNG)

- **ls -t:** sort the files with time, latest should be at top.

  **Example:**

![Alt Text](https://dev-to-uploads.s3.amazonaws.com/i/y0qbk37mswznw5f9lcck.PNG)

- **ls -p:** append "/" to directories.

  **Example:**

![Alt Text](https://dev-to-uploads.s3.amazonaws.com/i/mayufsiv5e4xpbryyf4q.PNG)

- **ls -d \*/:** list the directories

  **Example:**

![Alt Text](https://dev-to-uploads.s3.amazonaws.com/i/kj1joqij0mw3mwyq1r52.PNG)

- **ls -ltr:** we can merge the above command together based on requirements. This is representing that **list of all the files in long format, sort the files with modification time, in descending order.**

  **Example:**

![Alt Text](https://dev-to-uploads.s3.amazonaws.com/i/xc8jgtf35fwntl89qrap.PNG)

**3. cd**:

**cd** full form is **change directory**. so it's used to change the shell directory.

**Syntax**:

```
cd [Directory Name]
```

But while going back to the parent directory of current directory, need to use below commands

```
cd ..
```

While going back to the parent's of parent's directory, need to use below commands.

```
cd ../..
```

Based on the requirements we can add more ".." and "/" after cd command.

**Example:**

![Alt Text](https://dev-to-uploads.s3.amazonaws.com/i/s7zrrwiczbc0iyrxmvc4.PNG)

**4. lsof**:

lsof stands for **List Of Open File** i.e. this command provide the information of list of opened files and opened for which process.

**Syntax**:

```
lsof [OPTIONS][USER NAME]
```

**Example:**

- Provided **\$lsof -u [USER NAME]** command to see the opened file for specific user.

![Alt Text](https://dev-to-uploads.s3.amazonaws.com/i/t3wz7563k84xvyecbpbx.PNG)

**5. watch**:

It gives continuous output in full screen mode with 2.0s interval.

**Syntax**:

```
watch [command]
```

**Example:**

Provided command **watch date** in below example

![Alt Text](https://dev-to-uploads.s3.amazonaws.com/i/3ompaxcmxqrz2i8iq1jd.PNG)

**5. df**:

df stands for disk free i.e. it is used to show information about file system's total space and available space.

**Syntax**:

```
df [OPTION]...[file]...
```

**Example:**

- If no file name is provided then it displays space available and used on all current mounted file systems.

![Alt Text](https://dev-to-uploads.s3.amazonaws.com/i/c02sh6zu3p6prknvldhv.PNG)

- If file name is provided then it display space available and used on that particular file.

![Alt Text](https://dev-to-uploads.s3.amazonaws.com/i/1xkrfhpmhusko48pr99a.PNG)

**6. who**:

Provides the details of currently logged in user information.

- Login name of the users
- Terminal Line Number
- Login Time of the user
- Remote hostname of the user

**Syntax**:

```
who [OPTIONS]...[FILE]...
```

**Example:**

![Alt Text](https://dev-to-uploads.s3.amazonaws.com/i/q48xywj4ptev0jjnqw7a.PNG)

**7. wget**:
Use to download the files from the server using HTTP,HTTPS,FTP protocols.

**Syntax**:

```
wget [OPTIONS]...[FILE]...
```

**Example:**

![Alt Text](https://dev-to-uploads.s3.amazonaws.com/i/qsmpel6wyiyo6aec08f6.PNG)

**8. w**:
Use to see the information of user who is logged in and what they are doing.

The header provide the information of current time, how long system is running, how many users logged in and load average for past 1, 5 and 15 mins.
Other than these it display each user- login name, tty, remote host, login time, idle time, JCPU , PCPU and the command line of their current process.

**Syntax**:

```
w [OPTIONS] USER ...
```

**Example:**

![Alt Text](https://dev-to-uploads.s3.amazonaws.com/i/a6iq5blvdzpjwuqfu0rh.PNG)

**9. wc**:

**wc** stands for word count i.e. it is used for counting purpose.
It counts the number of lines, number of words, number of characters.

**Syntax**:

```
wc [OPTIONS]... [FILE]...
```

**Example:**

First column represent number of lines present in specific file, second column represent the number of words present in specific file, third column represent number of character presents and fourth column represents the name of the file.

![Alt Text](https://dev-to-uploads.s3.amazonaws.com/i/kn3u4v75hwdmf8u9qxxl.PNG)

**10. lshw**:

**lshw** stands for list of hardware i.e. it displays details of system's hardware information. To access this command we should be a super user.

**Syntax**:

```
lshw [FORMAT]... [OPTIONS]...
```

Here format can be **html, xml, json, short, businfo**.

**Example:**

- It provides the full hardware information.

![Alt Text](https://dev-to-uploads.s3.amazonaws.com/i/q8ngjhi71uid6kv3v7pn.PNG)

- It list the hardware info in compact format.

![Alt Text](https://dev-to-uploads.s3.amazonaws.com/i/769vwk866775oaltj4se.PNG)

**11. man**:

**man** stands for Manual i.e. it is used to display user manual for any command.
It provides details of command which includes : **NAME, SYNOPSIS, DESCRIPTION, OPTIONS, EXIT STATUS, RETURN VALUES, NOTES, FILES, EXAMPLES, AUTHOR, REPORTING BUGS, COPYRIGHT and SEE ALSO.**

**Syntax**:

```
man[OPTION]... [COMMAND NAME]...
```

**Example:**

- Provided **\$man lshw** command without option and shown the whole manual of the specified command name.

![Alt Text](https://dev-to-uploads.s3.amazonaws.com/i/u509mlgak1e59cbnfyya.PNG)

- Provided **\$man -w [COMMAND NAME]** command with option and shown the location of the manual page for the specified command name.

![Alt Text](https://dev-to-uploads.s3.amazonaws.com/i/svt5jrlcul8h7605gxk4.PNG)

**12. cat**:

**cat** stands for **concatenate**. It reads data from the files and give their output. It also helps us to create file, view files, concatenate files.

**Syntax**:

```
cat[OPTION]... [FILE]...
```

**Example:**

- Provided **\$cat [file_name]** command to get the output whatever is inside the file.

![Alt Text](https://dev-to-uploads.s3.amazonaws.com/i/knldxybph9hptdehrx9u.PNG)

- Provided **cat >[file_name]** command to create the file and at the same time you can provide the text inside the file. After that you can exit using **Ctrl+D**.

![Alt Text](https://dev-to-uploads.s3.amazonaws.com/i/2k5ld8kdj5rn1qp1zlyu.PNG)

**13. rm**:

**rm** stands for **remove**. remove commands can remove the files, directories etc. But by default it doesn't remove directories. **But Be careful of these commands.**

**Syntax**:

```
rm[OPTION]... [FILE]...
```

**Example:**

- Provided **\$rm [FILE NAME]** command to remove specified file name.

![Alt Text](https://dev-to-uploads.s3.amazonaws.com/i/e8rrgnxdpdb0t9ssilvs.PNG)

- **\$rm -r:** remove directories recursively.

- **\$rm -f:** remove _Read only file_ without permission.

- **\$rm -rf. :** Force deletion of _Current folder and sub folders_.

- **\$rm -rf/ :** Force deletion of _Everything in root directory_.

- **\$rm -rf\* :** Force deletion of _Everything in current directory_.

- **\$rm -rf [DIRECTORY NAME] :** Force deletion of _Specified Directory Name_. It deletes everything whatever present inside of the directories.

- **\$rmdir [DIRECTORY NAME]:** Remove the _Specified Directory Name_. If directories content files or folders, this command unable to delete directories.

**14. pwd**:

**pwd** stands for **Print Working Directory**. It prints path of the working directory, starting from the root.

**Syntax**:

```
pwd [OPTION]
```

**Example:**

![Alt Text](https://dev-to-uploads.s3.amazonaws.com/i/tpmscap1zt10zevca5a8.PNG)

**15. mv**:

**mv** stands for **Move** i.e. it moves file or files or directories from one place to another place.

**Syntax**:

```
mv [OPTION] [Source] [Destination]
```

**Example:**

![Alt Text](https://dev-to-uploads.s3.amazonaws.com/i/m99jvp1ckla7y614ewm0.PNG)

- Provided **\$mv [file1][file2]** command, which is responsible to rename the _file1_ to _file2_ and override the _file2_ value with _file1_ value.

![Alt Text](https://dev-to-uploads.s3.amazonaws.com/i/k2q4p01mu2v1jh0kds5c.PNG)

- Provided **\$mv -b [file1][file2]** command, -b is responsible to take the backup of overridden file value(_file2_). It creates a backup file with tilde (~) character append with it.

![Alt Text](https://dev-to-uploads.s3.amazonaws.com/i/cud17wd8lnjbrkq6jzku.PNG)

**NOTE:** `You can use --help option with any of the command to know more about the commands.`

![Alt Text](https://dev-to-uploads.s3.amazonaws.com/i/nvg4j5zpwzpa0btc1ln5.PNG)
