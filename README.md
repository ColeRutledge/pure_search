# Management Repo for Flask/React API App
## appacademy capstone


### To gain access to postgres inside container:
```bash
docker container exec -it db /bin/sh
psql -U capstone_app -W capstone_db
```
### To populate DB with seeder data:
```bash
docker container exec -it api /bin/sh
python3 database.py
```
