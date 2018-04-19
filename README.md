# Alpine Linux Repository

This repositories are experimental. Use them on your own risk!

## Add repositories

### AWS

Add `https://zaidan.github.io/alpine-linux-zaidan/aws` to your `/etc/apk/repositories`:

```bash
# echo 'https://zaidan.github.io/alpine-linux-zaidan/aws' >> '/etc/apk/repositories'
```

### PHP

Add `https://zaidan.github.io/alpine-linux-zaidan/php` to your `/etc/apk/repositories`:

```bash
# echo 'https://zaidan.github.io/alpine-linux-zaidan/php' >> '/etc/apk/repositories'
```

## Install public key

* Save the repository public key to `/etc/apk/keys`

```bash
# cd /etc/apk/keys
# wget https://zaidan.github.io/alpine-linux-zaidan/firas%40zaidan.de-5ad7457d.rsa.pub
```

* Verify `sha512sum` of `firas@zaidan.de-5ad7457d.rsa.pub`:
```bash
55462fb94c5207f16876f965b3b326ea85991fe75fec256ed75ba81e05e31045c216d53a1da67681d67a3ed63a678845a4818f50806e7548e0db4a24e5e5dba6
```
