### Git Command

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
	
11. To remove file from remote repo without deleting from local repo.
	```
	git rm -r - cached <file_name>
	```


