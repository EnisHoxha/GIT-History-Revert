# GIT-History-Revert

List of commands to revert your github repo git history

Commands:

```bash
$> git checkout --orphan <any_branch_name> #except current branch you want to revert git history
$> git add -A
$> git commit -am <your_commit_message>
$> git branch -D main
$> git branch -m main
$> git push -f origin main
$> git gc --aggressive --prune=all
```

Attention: In this example im reverting git history in branch main,in you project replace "main" with your current git branch you want to revert git history.
