# If you want to UNDO things? --amend is here for you!
- Sometimes you need to modify finished commit. 
- But you don't want to make dirty log, such as 'Oh I forgot a.txt file'
- Three below lines are recorded as one commit.

- git commit -m "initial commit"
- git add forgotten_file
- git commit --amend

## How to change file state to Unstage

## commit을 했는데 취소하고 싶을땐?
- git reset --soft HEAD^
- 의미: commit을 취소하고 해당 파일들은 staged 상태로 워킹 디렉터리에 보존