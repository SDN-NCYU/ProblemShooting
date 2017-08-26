# Problem Shooting
## Problem : Mininet and Ryu use the same port (6633)
### Solution :
    Give Ryu another port to runnint app.
    $ ryu-manager --ofp-tcp-listen-port 5555 --verbose apps.py
    
---
---

## Problem : SSH For git
### Solution : 
    $ ssh-keygen -t rsa
    $ cd .ssh\
    $ cat id_rsa.pub

---
---

## Problem : GitHub@Switch account in a computer
### Solution :
    $ git pull
    Do some modify....
    $ git config user.name "KShih"
    $ git config user.email "kontonsine@gmail.com"
    $ git add .
    $ git commit -m "Some msg"
    $ git push
