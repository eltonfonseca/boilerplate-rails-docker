## Boilerplate Rails With Docker

#### Create Application

```bash
$ docker-compose run web rails new . --force --no-deps --database=postgresql
```

#### Create Application in API Mode

```bash
$ docker-compose run web rails new . --api --force --no-deps --database=postgresql
```
