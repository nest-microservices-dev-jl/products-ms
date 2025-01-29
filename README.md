# Product Microservice

## Dev

1. Clonar el repositorio
2. Instalar dependencias
3. Crear un archivo `.env` basado en el `env.template`
4. Ejecutar migración de prisma `npx prisma migrate dev`
5. Levantar el servidor de NATS
```
docker run -d --name nats-server -p 4222:4222 -p 8222:8222 nats
```
6. Ejecutar `npm run start:dev`
7. El archivo para probar la API está en el repositorio git del gateway `(api_Insomnia_2025-01-28.json)`