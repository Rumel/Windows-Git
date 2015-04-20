# Windows Git Tips

#### Pull Requests are welcomed

## Learning Git
* [Try Git](https://try.github.io/levels/1/challenges/1)
* [Pro Git](http://git-scm.com/book/en/v2)
* [Learn Git Branching](http://pcottle.github.io/learnGitBranching/)

## Tips

Set up your username and email.
```bash
$ git config --global user.name "Dalton Dick"
$ git config --global user.email "daltondick2010@gmail.com"
```

If you don't have ssh set up then you'll want to store your credentials.
Run this.
```bash
$ git config --global credential.helper wincred
```

Windows can be a real pain with line endings.
Run this to help with that.
```bash
$ git config --global core.autocrlf true
```

Git status can be slow on Windows for a large project.
Run these commands to fix that.

```bash
$ git config --global core.preloadindex true
$ git config --global core.fscache true
$ git config --global gc.auto 256
```

## Git Clients
* [Github for Windows](https://windows.github.com/)
  - Bundles [PoshGit](https://github.com/dahlbyk/posh-git)
* [Sourcetree](http://www.sourcetreeapp.com/)