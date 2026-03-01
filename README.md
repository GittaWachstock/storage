# storage

Store documents with minio.

Run client:

```bash
    docker exec -it client-2 bash
    npm run dev
```

Run server:

```bash
    docker exec -it server-2 bash
    uvicorn src.main:app --reload --host 0.0.0.0
```
