## Connect to container 

```sh
docker-compose exec mongodb bash 
```

## Connect with Mongosh

```sh
mongosh "mongodb://root:root123@localhost:27017/?authMechanism=DEFAULT&tls=false"
mongosh "mongodb+srv://prisadmin:prisadmin123@mongodb101.jmalqv3.mongodb.net/test"
```

```sh
show dbs
show collections
```

```sh
use("platzi_store")
db.products.find()
```