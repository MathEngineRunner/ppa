# MathToolExecutor PPA repo

echo "deb [signed-by=/etc/apt/trusted.gpg.d/mathtoolexecutor.gpg] https://mathtoolexecutor.github.io/ppa/ubuntu ./" > mathtoolexecutor.list

# How to use

```console
$ curl -SsL https://mathtoolexecutor.github.io/ppa/ubuntu/KEY.gpg | sudo apt-key add -
$ sudo curl -SsL -o /etc/apt/sources.list.d/mathtoolexecutor.list https://mathtoolexecutor.github.io/ppa/ubuntu/mathtoolexecutor.list
$ sudo apt update
```

## References

- https://assafmo.github.io/2019/05/02/ppa-repo-hosted-on-github.html
