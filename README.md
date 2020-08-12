# PureSearch
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


## Heroku Commands
- Add heroku.yml & Dockerfile
- Swap for gunicorn in entrypoint.sh
- Commit changes

```bash
heroku create
# change app name on heroku
git remote rm heroku
git remote add {remote-name} {remote-url}
heroku stack:set container -r {remote-name}

git push {remote-name} master
git push {remote-name} {branch}:master
heroku logs --tail -r {remote-name}
```
