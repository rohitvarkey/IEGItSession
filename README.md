Repository for IE git session. This describes the general procedure for contributing to a open source project.
Fork the repo. 
Go to https://github.com/rohitvarkey/IEGItSession.git and click on fork.
Clone the repo. 
```bash
git clone <url>
```
Now make branch, make changes and push your code.

```bash
git checkout -b <branchname>
```

Make Changes, add changed files and commit them.
```bash
git add .
git commit -m "Message describing commit"
```
Merge changes back to master
```bash
git checkout master
git merge <branchname>
```

Push back to repo
```bash
git push origin master
```

Now open a pull request by going to https://github.com/rohitvarkey/IEGItSession.git and clicking pull request.

##Resources
https://wildlyinaccurate.com/a-hackers-guide-to-git
http://justinhileman.info/article/git-pretty/
