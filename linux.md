# Linux Interview Questions

### [<-- Back](./README.md)

- How can you see which kernel version a system is currently running

  ```
  $ uname -v
  ```

- how can you check a systems current ip address

  ```
  $ ip addr
  ```

- how do you check for free disk space

  ```
  $ df -h
  ```

- how do you manage services on a system

  ```
  $ du -h
  ```

- how would you check the size of a directory's contents on a disk

  ```
  $ du -sh <path_to_dir>
  ```

- how would you check for open ports on a linux machine

  ```
  $ netstat
  ```

- how do you check CPU usage for a process

  ```
  $ top
  ```

- Dealing with mounts

  ```
  $ mount
  ```

- how do you look up something you don't know

  ```
  $ man
  ```

- what do you do when you can't find an answer in a man page

  ```
  $ man -k
  ```


- #### Other Useful Commands

- Use the `grep` command to search for something specific in a file or outputted text

- Use `rsync` to remotely copy files

- `journalctl` can be used to display the logs of servers

- Software Managers:
  - Ubuntu / Debian: `apt`
  - Fedora / Enterprise Linux: `dnf`
  - Suse: `zypper`

- `ps` short synopsys of running processes

- `ls` is used to list all the files and directories in a specific folder or in your current directory

- `chown` to change ownership to file or directory

- `chmod` change what the user can do to the file or directory

- `systemctl` interact with services that are running or start running them