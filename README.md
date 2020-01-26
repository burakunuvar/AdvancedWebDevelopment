# AdvancedWebDevelopment
## Setting Up Ubuntu Server & SSH
- [Install Git on Linux](https://www.atlassian.com/git/tutorials/install-git)
- [Install NodeJS on Linux](https://github.com/nodesource/distributions/blob/master/README.md) 
- [rsync](https://www.tecmint.com/rsync-local-remote-file-synchronization-commands/) 
- [apt-get](https://help.ubuntu.com/community/AptGet/Howto)

```
$ cd ~ ./ssh
$ ssh-keygen -C "test@gmail" 
$ ssh-keygen -t rsa -b 4096 -C "your_email@example.com"
$ /Users/testuser/.ssh/id_rsa_gcp
$ pbcopy < ~/.ssh/id_rsa_gcp.pub ( on Mac )
$ nano ~ ./ssh/authorized-keys and save ( on vm ) 
$ ssh -i path-to-private-key username@external-ip
```
