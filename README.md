# git-practice
a practice repo for club members to clone, commit, branch, push, and fetch to and from.

## Installation:
Git (command line version):
- [Git Website](https://git-scm.com/downloads)

Graphic User Interfaces:
- [GitHub Desktop](https://desktop.github.com)
- Built in to Editor: ex. [Visual Studio Code](https://code.visualstudio.com/Download)

## Activities:
We will do the following basic actions using git to add our name/identifier to the list of git graduates in git-grad.txt

### Clone: 
Download the repository to our computer.

```bash
git clone https://github.com/UBCO-Aerospace-Club/git-practice
```

### Pull:
Sync changes from the main repository to our computer.

```bash
git pull
```

### Branch:
Make a copy of the main code to focus on one set of changes.  ex. servo code addition.

```bash
git branch <youraliashere>
git checkout <youraliashere>
```

### Commit:
"Save" your changes to your working branch with a description of what you've changed.

Open git-grad.txt and add your alias, then save the file

```bash
git add git-grad.txt
git commit -m "Adding <youraliashere> to git-grad.txt"
```

### Merge:
Take the branch you've completed working on and add it's changes back to the main branch.  This may occur in merge conflicts that you would have to edit manually.  In reality this would be completed by the person who owns the project.

```bash
git checkout main
git merge <youraliashere>
```

### Push:
We now want to push our changes to github so that others can see them when they do a git pull from their local repository.

```bash
git push
```


