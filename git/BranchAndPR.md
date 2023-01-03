### Clone a repo
```azure
git clone <repo_link>
```

### Create a new branch
```azure
git branch <new_branchName>
```

### checkout branch
```azure
git checkout new_branchName
```
### add some files
```azure
echo 'hello word' > hello.txt
echo 'golang' > golang.txt
echo 'c++' > c++.txt
```

### Push the changes to the remote repo
**add files**
```azure
git add .
```
**commit**
```azure
git commit -m "messege for commit"
```
**push**
```azure
git push --set-upstream origin <new_branchName>
```

### Pull request
Then go Github and send Pull request.
Follow this link: https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request
