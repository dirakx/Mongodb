# Mongodb
mongodb doc/dev

* mongodump --host localhost --port 27017 --out db_15.09.2017
* mongodump -h localhost --db tranquera --out /tmp/db_backup_13.12.2016/
* mongorestore data/vendorportaldb_15.09.2017/
* docker run -td --network vendorportal_default --name mongodb6_tools -p 12346:12346 --link vendorportal_vendorportal-mongodb-prod_1  vendorportal/mongo-tools /bin/bash -c "socat -dddd TCP-LISTEN:12346,reuseaddr,fork TCP:vendorportal_vendorportal-mongodb-prod_1:27017"




