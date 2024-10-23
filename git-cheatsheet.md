### Basic Shell commands

| command                  | functionality                                                              |
| ------------------------ | -------------------------------------------------------------------------- |
| `ls`                     | list the content of the current directory                                  |
| `cd <foldername>`        | change directory into a folder                                             |
| `cd ..`                  | change into the parent folder                                              |
| `cd ~`                   | change into your home directory                                            |
| `pwd`                    | print the current directory path                                           |
| `touch example.md`       | create a file called "example.md"                                          |
| `mkdir newFolder`        | create a folder called "newFolder"                                         |
| `mv <oldname> <newname>` | move or rename a file                                                      |
| `rm <filename>`          | delete a file permanently (there is no trash bin to recover files!)        |
| `open .`                 | open the current folder in the finder                                      |
| `cat <filename>`         | prints the content of a specific file                                      |
| `curl <url>`             | prints the received content from the specified url. (try `curl ipinfo.io`) |

### Markdown Examples

| Element                         | Markdown Syntax                         |
| ------------------------------- | --------------------------------------- |
| Level 1 headline                | `# Level 1 headline`                    |
| Level 2 headline                | `## Level 2 headline`                   |
| Level 5 headline                | `##### Level 5 headline`                |
| list item                       | `- list item`                           |
| [ ] done                        | `[ ] checkbox`                          |
| [x] done                        | `[x] checkbox`                          |
| **bold text**                   | `**bold text**`                         |
| _italicized text_               | `_italicized text_`                     |
| [link](https://www.example.com) | `[link text](https://www.example.com)`  |
| image                           | `![description of image](url to image)` |
| block quote                     | `> block quote`                         |
| divider                         | `---`                                   |
| `inline code block`             | `` `inline code block` ``               |
| `code block`                    | ` ``` code block ``` `                  |

### git-cli and remote

| Git command               | Git task                                         |
| ------------------------- | ------------------------------------------------ |
| `git status`              | List all files that have changed and their state |
| `git add <filename>`      | Add a file to the stage                          |
| `git commit -m "add foo"` | Create a commit including all staged files       |
| `git log --oneline`       | Show the commit history                          |

<img src="assets/untracked-to-committed.png" alt="untracked to committed" width="400">
<img src="assets/modified-to-committed.png" alt="modified to committed" width="400">

### Git `branch` commands

| command                      | functionality                        |
| ---------------------------- | ------------------------------------ |
| `git switch -c <branchname>` | create a new branch and switch to it |
| `git switch <branchname>`    | switch branches                      |
| `git branch`                 | list your branches                   |
| `git branch -a`              | list all branches (local and remote) |
| `git branch -d <branchname>` | delete a branch                      |

<img src="assets/git-basics-branching-workflow.png" width="900">
