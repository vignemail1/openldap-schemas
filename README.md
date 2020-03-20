# openldap-schemas

Collection of OpenLDAP schemas

## How to easly import schemas into an OpenLDAP server

```
# under Debian/Ubuntu

$ sudo apt install schema2ldif
$ cd schemas
$ sudo ldap-schema-manager -i ./openssh-lpk.schema
```
