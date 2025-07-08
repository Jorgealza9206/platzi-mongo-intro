## Connect to container

```sh
docker-compose exec mongodb bash
```

## Connect with mongosh

```sh
mongosh ""
```

```sh
show dbs
show collections
```

```sh
use("platzistore")
db.products.find()
```