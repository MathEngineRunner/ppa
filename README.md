# mathenginerunner PPA repo

echo "deb [signed-by=/etc/apt/trusted.gpg.d/mathenginerunner.gpg] https://mathenginerunner.github.io/ppa/ubuntu ./" > mathenginerunner.list

# How to use

```console
$ curl -SsL https://mathenginerunner.github.io/ppa/ubuntu/KEY.gpg | sudo apt-key add -
$ sudo curl -SsL -o /etc/apt/sources.list.d/mathenginerunner.list https://mathenginerunner.github.io/ppa/ubuntu/mathenginerunner.list
$ sudo apt update
```

## References

- https://assafmo.github.io/2019/05/02/ppa-repo-hosted-on-github.html

