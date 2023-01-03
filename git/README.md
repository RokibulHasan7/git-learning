## Git Command

## Config
```
git config --global user.name "my_name"
```
```
git config --list
```

## Basics
1. Initialize a project as a git repo.
	```
	git init
	
	```
	
2. See status of file in local repo.
	```
	git status
	```

3. Add file.
	```
	git add <file name>
	```

	To add all files:
	```
	git add .
	```

4. To see the connected repos.
	```
	git remote
	```

5. To add or connect to a remote repo.
	```
	git remote add origin <repo link>
	```
	
6. To commit staged files.
	```
	git commit -m "messege"
	```
	
	
7. To unstaged files.
	```
	git reset
	```
   To unstaged file by file.
   ```
   git restore --staged <file_name>
   ```

8. To push.
	```
	git push -u origin master
	```
	
   After previous command we can push using this command.
   	```
   	git push
   	```
  
9. Fetch the updated version.
	```
	git fetch
	```

10. Pull. This will change the local repo to remote repo.
	```
	git pull
	```
    => bring changes from the remote branch into yours.
    ```
    git pull --rebase
    ```
	
11. To remove file from remote repo without deleting from local repo.
	```
	git rm -r - cached <file_name>
	```

12. To see What is Unstaged.
	```
	git diff
	```
	
13. To change the last commit messege.
	```
	git commit --amend -m "commit_message"
	```
	
14. Show last commit history
	```
	git log
	```
    Show the changes in last commit.
    	```
	git log -p <hash_value_of_commit>
	```
	
### Clone Repo
```
git clone <repo_link>
```
To see the branch of this repo
```
git branch -a
```

	
### Undo Things
```
git commit -m 'Initial commit'
git add forgotten_file
git commit --amend
```
This will endup in a single commit. If you forgot to add some files in first commit then use it to add forgotten files and make it one commit.


### 
