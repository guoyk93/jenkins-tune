# jenkins-tune

[![BMC Donate](https://img.shields.io/badge/BMC-Donate-orange)](https://www.buymeacoffee.com/vFa5wfRq6)

Disable jenkins signature verification for `update-center.json`

# Usage

* Put `jenkins-tune-1.0.jar` at somewhere reachable.

* Edit `/etc/init.d/jenkins` or other start-up script, append `JAVA_OPTS`

```
-javaagent:/path/to/elasticsearch-tune-1.0.jar`
```

# Blog (CN)

https://blog.csdn.net/u011426433/article/details/106095221

# Credits

Guo Y.K., MIT License
