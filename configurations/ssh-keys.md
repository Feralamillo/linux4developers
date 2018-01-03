# Configure the ssh-key

In order to create your own ssh-key

1. Run ssh-keygen
```
$ ssh-keygen
Generating public/private rsa key pair.
Enter file in which to save the key (/Users/emmap1/.ssh/id_rsa):
```
2. List the contents of ~/.ssh to view the key files.
```
$ ls ~/.ssh
id_rsa id_rsa.pub
```
3. run ssh-add ~/.ssh/id_rsa
```
$ ssh-add ~/.ssh/id_rsa
Identity added:
```
4. Copy and paste the key where you want
```
$ cat ~/.ssh/id_rsa.pub
```
