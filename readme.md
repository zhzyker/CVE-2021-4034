# CVE-2021-4034
polkit pkexec Local Privilege Vulnerability to Add custom commands  
change to https://github.com/signfind/CVE-2021-4034  

Cancel the /bin/sh interactive shell  
Suitable for one-line command execution in special cases

# Build  
```
gcc cve-2021-4034.c -o cve  
```
# RCE    
> ![image](./CVE-2021-4034.jpg)  
> 

