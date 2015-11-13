# gb
Bash script for handling multiple git repos
```
gb <cmd> <path (Optional)>
```
Check status in all directories
``` 
gb status
```
**or**
```
gb status /path/to/repo/root
````

## Available commands
### pull
pulls remote branch 
```
gb pull
````
#### status 
Checks the status of a repo. If it's in sync with remote and if there is any uncommited code
```sh
gb status
```
