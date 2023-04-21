## Git Tutorial

### SSH Key generation

ssh-keygen
file => Home/.ssh/id_rsa.pub
setting > ssh and gpg key > new ssh key

---

### git configuration

```bash
git config —global user.name “username”
git config —global user.email “gmail”
```

---

### git config check

git config user.name
=> username

git config user.email
=> gmail

---

### git add and push

git init => one time
git remote add origin repositorylink => one thime

git add . ( or ) git add -A => all file / git add filename => filename
git commit -m “note”
git push -u origin master ( or ) git push -u origin main

---

### Git Branch

- Branch Check

```bash
git branch
```

- Create New Branch

```bash
git branch branchname
```

- Switch Branch

```bash
git checkout branchname
```
