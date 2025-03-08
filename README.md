# Ejecutar en prod

1. Copiar el archivo .env.example y renombrar a .env - rellenar los datos

```
cp .env.example .env
```

2. Crear network de docker

```
docker network pg-network
```

3. Run

```
docker-compose up -d
```
