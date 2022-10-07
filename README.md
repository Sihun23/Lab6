# Lecture Note 6 <Git-1> (201933966_양시훈)
## 2022.10.06
---
### Version Control and Collaboration
We need a sysmetic mangagement system for version control and collaboration => **Git**
There are various ways to manage the version and collaboration system.
**<Changes vs Snapshots>**
- Changes : Stotring data as changes to the base version.
- Snapshots : Storing data as snapshonts => **Git's method**
**<Local vs Centralized vs Distributed>**
- Local
- Centralized
- Distributed => **Git's method**

**<3 states in GIT>**
1. Modified
2. Staged
3. Comitted

**Storage in 3 levels**
1. System level : --system option. Affects all uses and repositories on the system.
2. Global level : --global option. Affects all repositories of a current user.
3. Local level : --local opption. Specific to the current repository.
- Each level overrides values in the previous level : system -> global ->


**$ git init**
```sh
$ git init // initialized empty Git repository
```
  
**$ git status**
```sh
$ git status // checking repositoty status
```
  
**$ git add[file_name]**
```sh
$ git add README.md // adding a new file to be staged
```

**$ git rm-cached[file_name]**
```sh
$ git rm--cached history_command.txt // unstaging a file
```
  
**$ git commit -m "commit message"**
```sh
$ git commit -m "initial commit" 
```
  
**$ git branch**
```sh
$ git branch
* master
$ git branch -m master main
$ git branch
* main
$ git status
```
