# Docker Commands

## Create Containers

```bash
docker create --name web-server nginx
docker create --name linux-tester alpine sleep 3600
```

---

## Start Containers

```bash
docker start web-server linux-tester
```

---

## Execute Commands

```bash
docker top web-server

docker exec linux-tester mkdir /app
docker exec linux-tester touch /app/test.txt
```

...
