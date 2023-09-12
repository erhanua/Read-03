# Read-03

## 1. What is Version Control?
Version control is a system that tracks changes to files and projects over time. It's especially used in software development processes, but it can be applied to any type of file.

Git is known as a distributed version control system (DVCS). This means that every developer has a complete copy of the project on their local machine. This provides users with the following advantages:

- **Offline Access**: Developers can work without being connected to the internet because the entire change history is stored on the local machine.
- **Parallel Work**: Multiple developers can work simultaneously on different features or fixes in the same project.
- **Speed**: Since all operations are local, git is very fast.
- **Rollback**: If a mistake is made, the version history provided by git allows for easy rollback to a previous state.
- **Branching and Merging**: Git facilitates the creation of branches for working on different features or fixes and merging those branches back into the main codebase.

## 2. What is cloning in Git?
"Cloning" in the context of Git refers to the process of creating a local copy of a remote repository. When you clone a repository, you're essentially downloading the entire project, including its codebase and version history, to your local machine.

```bash
git clone [repository-url]
```

## 3. What is the command to track and stage files?
In Git, the command to track and stage files is:

```bash
git add [filename or path]
```

Here's a breakdown:

- **Track New Files**: If you have a new file that hasn't been tracked by Git yet, you can use the `git add` command to start tracking it.

  Example:
  ```bash
git add newfile.txt
```

- **Stage All Changes**: If you want to stage all changes in the repository (new files, modifications, and deletions), you can use

```bash
git add .
```

## 4. What is the command to take a snapshot of your changed files?
The command to take a snapshot of your changed files in Git is:

```bash
git commit -m "Your descriptive message here"
```

## 5. What is the command to send your changed files to Github?
The command to send your changed files (commits) to GitHub is:

```bash
git push
```
