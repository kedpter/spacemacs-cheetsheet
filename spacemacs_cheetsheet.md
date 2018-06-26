
## SPACEMACS CHEETSHEET

| SHORTCUT                | DESCRIPTION                                                |
| ----------------------- | ---------------------------------------------------------- |
| `Basic`                 |                                                            |
| SPC f e R               | reload config                                              |
| SPC SPC                 | search command                                             |
| SPC f t                 | open nerd tree                                             |
| g r                     | nerd tree refresh                                          |
| SPC q q                 | quit emacs                                                 |
|                         |                                                            |
| `Project`               | (folder .git is considered as project)                     |
| SPC p p                 | project open                                               |
| SPC p h                 | project find file                                          |
|                         |                                                            |
| `Window`                |                                                            |
| SPC w /                 | split window vertically                                    |
| SPC w -                 | split window horizontally                                  |
| SPC $N                  | switch to window $N (nerd tree as 0)                       |
| SPC w c                 | window close                                               |
|                         |                                                            |
| `Buffer`                |                                                            |
| SPC TAB                 | buffer switch to previous                                  |
| SPC b b                 | buffer browse (Helm mini; lists buffers & recent files)    |
| SPC b d                 | buffer delete                                              |
| SPC b M                 | buffer move to another window                              |
|                         |                                                            |
| `file`                  |                                                            |
| SPC f f                 | new file + file find                                       |
| SPC f s                 | file save                                                  |
|                         |                                                            |
| `bookmark`              |                                                            |
| SPC f b                 | helm window with bookmarkds                                |
|                         | `C-d` delete                                               |
|                         | `C-e` edit                                                 |
|                         | `C-f` toggle filename location                             |
|                         | `C-o` open in another window                               |
|                         |                                                            |
| `programing stuff`      | like vim (calls evil folder)                               |
| zc                      | code fold                                                  |
| zo                      | code unfold                                                |
| za                      | code fold toggle                                           |
| SPC v                   | expand region                                              |
| s (                     | put parens around a region                                 |
| SPC s e                 | multiple cursors                                           |
| g c c                   | comment                                                    |
|                         |                                                            |
| `python`                |                                                            |
| SPC m =                 | format code (PEP)                                          |
| SPC m g g               | go to definition                                           |
| SPC m g a               | go to assignment                                           |
| SPC m g b               | jump back                                                  |
| SPC m g u               | navigate between usages                                    |
| SPC m d b               | toggle a breakpoint                                        |
| SPC m h h               | quick documentation                                        |
| SPC m h H               | open documentation in firefox                              |
| SPC m r i               | remove unused imports with autoflake                       |
| SPC m r I               | sort imports with isort                                    |
| SPC e v                 | flycheck verify setup                                      |
| SPC e l                 | flycheck toggle error list                                 |
| SPC m c c               | execute current file in a comint shell                     |
| `iPython inferior REPL` |                                                            |
| SPC m s i               | start REPL process                                         |
| SPC m s r               | send region and keep code buffer focused                   |
| SPC m s b               | send buffer and keep code buffer focused                   |
| CTRL+j                  | next item in REPL history                                  |
| CTRL+j                  | previous item in REPL history                              |
| `live-py-mode`          |                                                            |
| SPC m l                 | Toggle live-py-mode                                        |
| `python-pyenv`          |                                                            |
| SPC m v s               | set a pyenv environment                                    |
| SPC m v u               | unset a pyenv environment                                  |
| pyenv local             | `pyenv local 2.7.6` create a file called `.python-version` |
|                         | spacemacs search in parent directories for this file       |
|                         | and automatically set the pyenv version                    |
| `test`                  | looking for `.git` or `setup.py`                           |
| SPC m t a (A)           | launch all tests of the project (A as Debug mode)          |
| SPC m t b (B)           | launch all tests of the current buffer                     |
| SPC m t t (T)           | launch the current test (function)                         |
|                         |                                                            |
| `template`              |                                                            |
| SPC SPC yas-new-snippet | new snippet                                                |
|                         |                                                            |
