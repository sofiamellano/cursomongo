
#Connect al container
```sh
        docker-compose exec mongodb bash
```

# Conect con mongo

```sh 
    	mongosh "mongodb://root:root123@localhost:27017/?tls=false"
```

```sh
        show dbs
        show collection
```

```sh
        use ("isp20_store")
        db.products.find()
```

