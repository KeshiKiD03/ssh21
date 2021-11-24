
# SSH server
## @edt ASIX M06-ASO Curs 2021-2022

### SSH Images:

 * **keshikid03/ssh21:base**


``` 
docker run --rm --name ldap.edt.org -h ldap.edt.org -p 389:389 --net 2hsix -d keshikid03/ldap21:group
docker run --rm --name ssh.edt.org -h ssh.edt.prg --net 2hsix -d keshikid03/ssh21:base
```
