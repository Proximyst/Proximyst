You can sign messages with my [PGP public key](./key.gpg).

Signing guide:

```shell
$ curl --tlsv1.3 --max-redirs 0 https://github.com/Proximyst.gpg | gpg --import -
$ echo 'get your message here' | gpg --encrypt --recipient 'Mariell Hoversholm' --output message.asc
# The message is now in message.asc.
```
