# shutit-airflow
airflow for other base images

If you want a CentOS-based image:
```
docker build -t airflow .
```

Or if you want to try a different base:

```
pip install shutit
[edit config/build.cnf to change the base_image entry]
cd bin
./build.sh
```
