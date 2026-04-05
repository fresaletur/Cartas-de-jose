# 📊 Cartas del Dividendo

Web de seguimiento de acciones de dividendo con datos actualizados manualmente.

## Características

- Tabla interactiva con 33 acciones (Europa + EEUU)
- Filtros por sector, mercado y divisa
- Ordenación por cualquier columna
- Panel de detalle al clicar una fila (precio, medias móviles, valoración)
- Colores semáforo para RPD, PER y distancia a MM1000
- Compatible con GitHub Pages

## Columnas

| Campo | Descripción |
|-------|-------------|
| Precio | Precio de cierre |
| Var.% | Variación diaria |
| PER | Price to Earnings Ratio |
| RPD% | Rentabilidad por dividendo |
| MM1000 | Media móvil 1000 sesiones |
| %MM1000 | % del precio respecto a la MM1000 |
| Máx52 / Mín52 | Rango de 52 semanas |
| PERfut | PER estimado futuro |
| DPA | Dividendo por acción |

## Uso en GitHub Pages

1. Sube el repositorio a GitHub
2. Ve a **Settings → Pages**
3. En *Source* selecciona la rama `main` y carpeta `/root`
4. Tu web estará disponible en `https://<usuario>.github.io/<repo>/`

## Actualización de datos

Edita el array `stocks` en `index.html` con los nuevos valores.

---
*Datos actualizados manualmente · Abril 2026*
