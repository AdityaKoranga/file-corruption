# file-corruption

file is correct or not for tar?
```bash
tar -tf <file-name>.tar.gz > /dev/null
```

if no output, which means file is fine

Checksums and integrity checking:

```bash
md5sum <file_name>
```
```bash
sha256sum <file_name>
```
It will provide hash values, which you can even take for future reference to check whether file was changes or not.
