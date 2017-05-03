# qcrypt
Simple GPG file encryption

`Usage: qcrypt filename`

## Example

Encrypt:
```
echo "test" > text.txt
./qcrypt text.txt
text.txt encrypted with 3GlCRvccUoobwXZAK3VWyQ==
```

Decrypt:

Enter password when prompted.
```
gpg -o text.txt -d text.txt.gpg
```
