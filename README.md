### Quick add certs
```
mkdir certs
openssl req -x509 -newkey rsa:4096 -keyout certs/selfsigned.key -out certs/selfsigned.crt -days 365 -subj '/CN=localhost' -nodes
```
