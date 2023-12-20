# Directory

```
front/
├── README.md
├── app/                # React/Next.js app
├── docker-compose.yml  # to dev
└── dockerfile          # to dev
```

# dockerfile/docker-compose.yml
Build ubuntu18.04 to development, includes nodejs.

Using:
```
docker compose build
docker compose up -d
docker exec -it my-node-app /bin/bash
```



