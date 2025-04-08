# quotes
A repository of quotes from students who want to try git commands.

## Project Setup

### Configurations

Run the following on your chosen terminal to set up commits and remote connections:

```
git config --global user.name "Your Name"
git config --global user.email "your@email.com"
```

### Git Cloning

To create a local copy of an online repository, run this command:

```
git clone https://github.com/Ayumu098/quotes.git
```

## Local Changes

### Git Branches

To create a new branch in your repository, run the following command:

```
git switch -c feature/my-feature
```

### Git Staging

If you make a new file, remove, or create changes (example: making a new file `src/stephen_singer.py`), run the following command to add the change in staging or list of files that should be recorded:
```
git add src/stephen_singer.py
```

To check all changes done so far, run the following command:

```
git status
```

To stage all changes, run the following command:
```
git add .
```

### Git Commit

To make a checkpoint or save the changes in staging, run the following command:
```
git commit -m "Describe changes (Verb - Subject - Details)"
```

## Remote Syncing

### Git Pull

Ensure the local `main` branch is in sync with the remote version, and run the following command:
```
git switch main
git pull --rebase origin main
```

Do the same process for the current local feature branch:

```
git switch feature/my-feature
git pull --rebase origin main
```

### Git Push

Finally, reflect the changes in the feature branch to the online repository with this command:

```
git push origin feature/my-feature
```


### Pull Request

To merge the feature's changes with the `develop` branch, make a pull request on your chosen online repository platform. You can also do this in the console, but this is better for code reviews and tests.



