---
{"dg-publish":true,"permalink":"/posts/useful-git-commands/"}
---

***Setup:***
```bash
git config --global user.name username
git config --global user.email email
```

***Init Repo:***
```bash
git init
git add .
git remote add origin remote-url <link>
git commit -m "any_message"
git push --set-upstream origin master
```

***Commit & Push:***
```bash
git commit -m "any_message"
git push
```

```meta-bind-button
style: primary
label: Home
action:
  type: open
  link: "[[Home Page]]"
```