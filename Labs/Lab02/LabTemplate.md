## Lab 02

- Name:
- Email

## Part 1 Answers

The answers for this section are to help you record what steps  
are needed to create a file locally (in your cloned repo)  
and push them (sync) with GitHub

1. Add a file for tracking:git add Lab02.md
2. Commit changes:git commit -m"changes committed"
3. Sync local commits with GitHub:git pull
4. Sync commits on GitHub to `clone`d repository:git push

## Part 2 Answers

For each, write the command used or answer the question posed.

1.sudo adduser mriaz
2./home/mriaz
3.No ubuntu can not add files to mriaz home directory becuase it does not have permission 
4.su mriaz (then entre password)
5.cd home/
6.yes mriaz can add files to directory as he has the permission 
7.exit
8.cd /home

## Part 3 Answers

For each, write the command used or answer the question posed.

1.sudo addgroup crew
2.sudo usermod -aG crew mriaz AND sudo usermod -aG crew ubuntu
3.sudo chown -R ubuntu:crew /home AND THEN chmod -R g+rw /home
4.su mriaz
5.touch newfile
6.because they are now  members of the same group crew and can access the same directories or files

## Part 4 Answers

For each, write the command used or answer the question posed.

1.sudo touch sudowho.txt
2.rw-r--r--
3.sudo vim sudowho.txt


## Part 5 Answers

1. `ssh` command before configuring `config` file: ssh -i ceg2350.pem ubuntu@3.94.73.255
2. HostName:3.94.73.255
3. User:ubuntu
4. IdentityFile:/home/muhammad10
5. `~/.ssh/config` contents:
 Host ceg2350
        user ubuntu
        HostName 3.94.73.255
        IdentityFile /home/muhammad10/ceg235000.pem
        port 22
```
Paste your config file entry here
```

6. `ssh` command after configuring `config` file:ssh ceg2350
