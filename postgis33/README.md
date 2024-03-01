```
sudo yum install https://download.postgresql.org/pub/repos/yum/reporpms/EL-7-x86_64/pgdg-redhat-repo-latest.noarch.rpm
sudo yum localinstall geos312-3.12.1-1PGDG.el7.x86_64.rpm
sudo yum localinstall gdal34-libs-3.4.3-4.el7.x86_64.rpm
cd deps
sudo rpm -i --nodeps protobuf-c-devel-1.1.1-2.fc23.x86_64.rpm
sudo yum localinstall protobuf-c-1.1.1-3.2.x86_64.rpm libprotobuf9-2.6.1-10.2.x86_64.rpm libprotobuf-c1-1.1.1-3.2.x86_64.rpm libprotoc9-2.6.1-10.2.x86_64.rpm libprotobuf-c-devel-1.1.1-3.2.x86_64.rpm
cd ../../
sudo yum localinstall postgresql16-contrib-16.2-1PGDG.el7.x86_64.rpm
cd postgis33
sudo yum localinstall postgis33_16-3.3.6-2PGDG.el7.x86_64.rpm
sudo yum remove protobuf-c-devel-1.1.1-2.fc23.x86_64

```
