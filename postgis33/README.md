```
sudo yum install https://download.postgresql.org/pub/repos/yum/reporpms/EL-7-x86_64/pgdg-redhat-repo-latest.noarch.rpm

yum --disablerepo=* --enablerepo=pgdg-common search gdal

yum --disablerepo=* --enablerepo=pgdg-common search geos

yum --disablerepo=* --enablerepo=pgdg-common search proj

sudo yum install proj71 proj72 libgeotiff17 SFCGAL
sudo yum localinstall geos312-3.12.1-1PGDG.el7.x86_64.rpm
sudo yum localinstall gdal34-libs-3.4.3-4.el7.x86_64.rpm
sudo yum localinstall postgis33_16-3.3.6-2PGDG.el7.x86_64.rpm

```
