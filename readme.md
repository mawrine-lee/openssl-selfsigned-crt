# Generate ssl self signed certificate with openssl 

## How to use it

1. Copy/create script on your computer/server

2. Give permission

```
chmod +x ssl-gen.sh
```

3. Running script 

```
./ssl-gen.sh example.com
```

## Notes: 
1. Valid for 1 years.
2. Using domain.crt and domain.key as cert.
3. For manual trusted in ubuntu copy rootCA.crt to /etc/ssl/certs/, then update-ca-certificates, relogin.
4. For manual trusted in firefox browser, insert rootCA.crt file to certificates settings in browser, then try to reopen.
