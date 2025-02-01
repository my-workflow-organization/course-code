Commands to encrypt:
-------------------
gpg --symmetric --cipher-algo AES256 secret.json
 

Decrypt: 
-------
gpg --decrypt --passphrase="12345678" --output decrypted.json secret.json.gpg