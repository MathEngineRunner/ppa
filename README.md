# mathenginerunner PPA repo

# How to use

Original:

```console
$ curl -s --compressed "https://mathenginerunner.github.io/ppa/ubuntu/KEY.gpg" | gpg --dearmor | sudo tee /etc/apt/trusted.gpg.d/mathenginerunner.gpg >/dev/null
$ sudo curl -s --compressed -o /etc/apt/sources.list.d/mathenginerunner.list "https://mathenginerunner.github.io/ppa/ubuntu/mathenginerunner.list"
$ sudo apt update
```

## References

Code snippet:

```console
$ echo "deb [signed-by=/etc/apt/trusted.gpg.d/mathenginerunner.gpg] https://mathenginerunner.github.io/ppa/ubuntu ./" > mathenginerunner.list
```

- https://assafmo.github.io/2019/05/02/ppa-repo-hosted-on-github.html
