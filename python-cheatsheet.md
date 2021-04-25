# HTTP Server
| Version | Command                          |
| :------ | :------------------------------- |
| Python2 | python -m SimpleHTTPServer -p 80 |
| Python3 | python3 -m http.server -p 80     |


# Spawn a Shell
## Step 1
| Version | Command                                         |
| :------ | :---------------------------------------------- |
| Python2 | python -c "import pty; pty.spawn('/bin/bash')"  |
| Python3 | python3 -c "import pty; pty.spawn('/bin/bash')" |

## Step 2
Ctrl+Z

## Step 3
```bash
stty raw -echo
```

## Step 4
```bash
fg
```
