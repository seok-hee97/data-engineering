# Data Engineering course


#### Docker
docker-tutorial folder

- Docker Getting 
https://docs.docker.com/get-started/


#### SQL   
- practice used by docekr image(postgres)     
```
docker pull postgres

docker run --name  data-engineering-postgres -e POSTGRES_PASSWORD=secret -d postgres

docker exec -u postgres data-engineering-postgres createdb postgres-db

docker exec -it data-engineering-postgres psql -U postgres -d postgres-db
```

#### elt

custom_elt_project


#### dbt
dbt(Data Build Tool)
```

```



#### [reference]

- [Data Engineering Coures for Beginners(freecodecamp)](https://www.youtube.com/watch?v=PHsC_t0j1dU&t=15s)

