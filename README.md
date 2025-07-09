# PostgREST en Render.com

Este repositorio despliega una instancia de PostgREST conectada a una base de datos PostgreSQL en Render.

### Cómo usar

1. Modifica el archivo postgrest.conf con tu URL real.
2. Sube este repositorio a GitHub.
3. Crea un nuevo *Web Service* en Render:
   - Fuente: tu repo
   - Build Command: (vacío)
   - Start Command: *(Render detecta el CMD del Dockerfile)*
   - Plan: Free está bien
4. Espera que se despliegue y accede vía https://<tu-nombre>.onrender.com

Puedes consultar https://<tu-url>.onrender.com/products si creaste la tabla products.