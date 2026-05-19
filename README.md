# Intro

This is WIP, this isn't really useful to anyone yet, aside from me.
Mostly my notes for now

# Caches

## Faster followup builds

Avoid having to deal with downloading packages again and some artifacts

```bash
mkdir mkosi.cache mkosi.pkgcache
```

# Passwords/passphrases

```bash
echo "zuperzecure" > mkosi.rootpw
echo "reallyzecure" > mkosi.passphrase
```

# Create SecureBoot keys

```bash
mkosi genkey
```

mkosi.crt and mkosi.key will be created
