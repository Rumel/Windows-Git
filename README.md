# Windows Git Tips

#### Pull Requests are welcomed


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