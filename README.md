# Multi-Threaded Smb Bruteforcer #


```
usage: mtsb.py [-h] --target TARGET [--usersfile USERSFILE] [--user USER] [--passwords PASSWORDS] [--password PASSWORD] [--port PORT] [--threads THREADS] [--verbose]

options:
  -h, --help            show this help message and exit
  --target TARGET, -t TARGET
                        target ip address
  --usersfile USERSFILE, -uf USERSFILE
                        users wordlist
  --user USER, -u USER  single username to use
  --passwords PASSWORDS, -pf PASSWORDS
                        passwords wordlist
  --password PASSWORD, -p PASSWORD
                        single password to use
  --port PORT           smb port (default: 445)
  --threads THREADS     threads to use (default: 100)
  --verbose, -v         verbose the bruteforcing attempts

(M)ulti (T)hreaded (S)MB (B)ruteforcer
```

- example:

`mtsb.py -t 10.10.162.154 --user 'username' -pf wordlist.txt`