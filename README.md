## Git Tutorial

### SSH Key generation

| Title                 | Description                              |
| --------------------- | ---------------------------------------- |
| ssh-keygen            | generate ssh key                         |
| directory             | ~/.ssh/id_rsa.pub                        |
| Add ssh-key in github | Setting > SSH and GPG keys > New SSH-Key |

---

### git configuration

```bash
git config —global user.name “username”
git config —global user.email “gmail”
```

---

### git config check

```bash
git config user.name
username
```

```bash
git config user.email
gmail
```

---

### git add and push

```bash
git init
git remote add origin repository

git add -A
git commit -m "note"
git push -u origin master
```

| Command                                                | Description                                                                                                                                                           |
| ------------------------------------------------------ | --------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| git init                                               | this keyword must be use once time in this project                                                                                                                    |
| git remote add origin repository                       | this keyword must be use once time in this project                                                                                                                    |
| git add -A (or) git add .                              | this keyword is selected All file                                                                                                                                     |
| git add filename                                       | this keyword is selected file same with filename                                                                                                                      |
| git commit -m 'note'                                   | this keyword is note                                                                                                                                                  |
| git push -u origin master (or) git push -u origin main | this keyword is push to the repository <br/> your repository branch is master and then push to the master or your repository branch is main and then push to the main |

---

### Git Branch

| Command                        | Description                                   |
| ------------------------------ | --------------------------------------------- |
| git branch                     | check branch                                  |
| git branch branchname          | create new branch                             |
| git checkout branchname        | change branch                                 |
| git push -u origin Head        | push to the current branch                    |
| git push -u origin Head:master | Current branch data push to the master branch |
