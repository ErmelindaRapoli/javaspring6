# Cheat Sheet

### Use git from command line and solve the error:

<code>git@github.com: Permission denied (publickey).
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.</code>

Generate the SSH key on your machine:
> ssh-keygen -C <yourmail@mail.com>

The files are generated under username/.ssh/

Copy the content of the id_xxx.pub file inside your account in GitHub.
Account -> Settings > SSH and GPG keys -> New SSH key and past there the key.
