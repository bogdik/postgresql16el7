# RPM packages Postgresql 16 for Centos 7

```
sudo yum localinstall postgresql16-16.2-1PGDG.el7.x86_64.rpm postgresql16-libs-16.2-1PGDG.el7.x86_64.rpm postgresql16-server-16.2-1PGDG.el7.x86_64.rpm
```

for postgresql16-llvmjit need 

```
wget http://dl.fedoraproject.org/pub/epel/epel-release-latest-7.noarch.rpm

sudo yum localinstall epel-release-latest-7.noarch.rpm

sudo yum install llvm5.0
```





