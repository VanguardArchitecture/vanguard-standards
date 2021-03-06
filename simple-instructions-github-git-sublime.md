# Simple Instructions for Github, Git + Sublime

These are instructions on how to navigate Git for simple updates. It doesn't address branching, merging, conflicts or any of the advanced items.

[Alt A: Github Edit](#alt-a-edit-on-github)

[Alt B: CLI + Sublime](#alt-b-command-line--sublime)

## Alt A: Edit on Github

1. Nav to Repo
2. Select File to Edit
3. Edit File
4. Commit Changes

### Navigate to the Repo

![Repo Nav](./images/a-repo-nav.jpg)

### Select the File to Edit

![Select File to Edit](./images/b-file-edit.jpg)

### Edit the File

![Edit File](./images/c-file-edit-2.jpg)

### Commit Changes

![Commit Changes](./images/d-file-commit.jpg)

## Alt B: Command Line / Sublime

1. Nav to Repo
2. Copy Repo Address
3. Open Terminal or Command Line and navigate to code folder
4. Git Clone the Repo (paste from Repo Address)
5. Use Sublime (or other Text Editor) to make changes
6. Use Git commands to Commit
  ```
  git add .

  git commit -m "your changes message"

  git push
  ```

### Navigate to the Repo you want to use

![1-Repo-Nav](./images/1-repo-nav.jpg)

### Copy the Repo Address

![2-Repo-Copy](./images/2-repo-copy.jpg)

### Open a terminal or command line, navigate to your local code folder.

### Git Clone the Repo

Example:
```
git clone https://github.com/VanguardArchitecture/cf-config.git
```

### Use Sublime to make Changes
Or use whatever editor you'd like to use.

### Use git commands to commit

```
git add .

git commit -m "Your message here"

git push
```

![Git CLI](./images/4-git-cli.jpg)
