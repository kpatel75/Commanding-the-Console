# Commanding the Console

## Tips and Tricks

- Making Commits:
    - Commit messages should be short and maningful-
    - Make freuqent commits
- VS Code Keyboard Shortcuts
    - **CTRL** + **`** for toggling the termibal window
    - **CTRL** + **k** followed by **s** "to Save All"

    ![Commit Messages](https://imgs.xkcd.com/comics/git_commit.png)
    
    ## Git Commands
    
    - `git init` - This command is used to initialize (set up) a git repository in the current directory.
    when a git repository is set up, there will be a hidden folder named ".git" that contains all the history of commits for the repository.
    - `git add .` - This command is used to stage un-tracked and modified file for a commit. If a file is not being tracked (and is not listed in .gitignore), this command will mark the file as a new item for the repository to track. If a file has been modofied, then this command will mark it as ready to be commited.
    - `git staus` - This command is used to give you the status of your code repository.
    - `git commit -m "message"` - The commit comand is used to save staged files to the repository. When a commit occurs, all of the files staged for committal are compaired against the last commit, and the changes between them becomes the new commit. Additionally. the user is identified for the commit (typically by a user name and email) - this is called blame.
    - `git pull` - This command is used to get a remote repository and merge it with the local repository. Remote repositories are typically hosted online.
    - `git push` - This command is used to take the local repository and send/merge it with a remote repository.
