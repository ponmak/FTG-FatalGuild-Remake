# FTG-FatalGuild-Remake
เว็บรับจ้างงานสาระพัน ไอ่เชน project 100ล้าน garuntee กินทามะเรียกพ่อ เกิดใหม่เป็นเว็บสุดเทพ

## Installation

1. $python -m venv ./venv/
2. $.\venv\scripts\Activate whatever you want
3. Install [OSGeo4W](https://download.osgeo.org/osgeo4w/v2/osgeo4w-setup.exe) in whatever you want and go change path in setting.py
4. Install [postgresql](https://www.enterprisedb.com/downloads/postgres-postgresql-downloads)
5. Setup postgresql by using [GeoDjango](https://docs.djangoproject.com/en/5.0/ref/contrib/gis/install/#windows) to be a guide for you except "Modify Windows environment"
6. $psql -U postgres
7. $CREATE DATABASE "FTG_DATABASE";
8. $CREATE USER ichain WITH PASSWORD '//in setting';
9. $GRANT ALL PRIVILEGES ON DATABASE FTG_DATABASE  TO ichain;
10. $ALTER USER ichain WITH SUPERUSER
11. $python manage.py createsuperuser

## opening
1. %psql FTG_DATABASE ichain
2. $.\venv\scripts\Activate whatever you want
3. %python.exe or python3 mysite\manage.py runserver

