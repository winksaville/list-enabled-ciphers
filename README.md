# List enabled ciphers fori a server supporting SSL/TLS

Executing `ciphers.sh` will list the enabled SSL/TLS ciphers for a server
```
$ ./ciphers.sh 127.0.0.1 8989
tls1_2 ECDHE-RSA-AES256-GCM-SHA384: 	OK
tls1_2 ECDHE-RSA-CHACHA20-POLY1305: 	OK
tls1_2 ECDHE-RSA-AES128-GCM-SHA256: 	OK
tls1_2 ECDHE-RSA-AES256-SHA384: 	OK
tls1_2 ECDHE-RSA-AES128-SHA256: 	OK
```

# Acknowledgements
ciphers.sh is based on [Using openSSL to determine which Ciphers are Enabled on a Server](https://securityevaluators.com/knowledge/blog/20151102-openssl_and_ciphers/) from [securityevaluators.com](https://securityevaluators.com/)
