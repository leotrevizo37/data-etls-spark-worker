# data-etls-spark-worker
Easy to use configuration ro deploy spark nodes (tmp)

to start type:
```bash
docker compose --env-file compose-helper/.env -f compose-helper/docker-compose.spark-worker.yml up -d --scale spark-worker=2
```