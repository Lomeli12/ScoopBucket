# ScoopBucket
A bucket to install my programs using Scoop (http://scoop.sh/)

## How to use

1. If you haven't already, install [Scoop](http://scoop.sh/).
```powershell
Set-ExecutionPolicy RemoteSigned -scope CurrentUser
iwr -useb get.scoop.sh | iex
```

2. Add this repo as a scoop bucket with the following command.
```
scoop bucket add lomeli-bucket https://github.com/Lomeli12/ScoopBucket
```

3. Install a program and enjoy.
```
scoop install plummod
```

### Whenever you want to update any of these applications, just use the following commands:
```
scoop update
scoop update *
```
