# Class 3 Reading Assignment

## Git Introduction

Git is the foundation for collaberative work in this field. You can use Git to clone a repository to the current directory in your terminal by using _git clone_ followed by the repository address. You can check the status of the file by using _git status_. If the changes are unstaged, they will appear red. If the changes are staged, they will appear green. After editing a file, the file will be flagged as modified. You can stage the modified file using _git commit -m "description of changes made"_. Finally, you can push the changes to git using _git push origin main_. If you are not quite ready to commit changes but also don't wanna lose made changes, you can use _git stash_ to temporarily hide the changes. When ready to commence working on the changes, use _git stash apply_ to bring them back.

## Sequence

1. git pdw
2. git cd _desired file_
3. git status
4. code .
5. git status
6. Use text editor to make changes, then save changes.
7. git add .
8. git status
9. git commit -m "description of changes"
10. git status
11. git push origin main
