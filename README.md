# 📊 Cartas del Dividendo

Web de seguimiento de acciones de dividendo con **datos en tiempo real** via Yahoo Finance.

## ¿Cómo funciona?

- Al cargar la página muestra los datos estáticos de base inmediatamente
- A continuación consulta la API de Yahoo Finance para obtener precios en vivo
- Se actualiza automáticamente **cada 3 minutos**
- Botón 🔄 para actualizar manualmente en cualquier momento

## Datos en tiempo real

| Campo | Fuente |
|-------|--------|
| Precio | Yahoo Finance (live) |
| Var.% diaria | Yahoo Finance (live) |
| PER / PERfut | Yahoo Finance (live) |
| RPD% / DPA | Yahoo Finance (live) |
| Máx52 / Mín52 | Yahoo Finance (live) |
| MM1000 | Estático (actualizar manualmente) |
| %MM1000 | Calculado con precio live y MM1000 estática |

## GitHub Pages

1. Settings → Pages → Source: `main` / `/(root)`
2. URL: `https://<usuario>.github.io/<repo>/`

## Actualizar MM1000

Edita el valor `mm1000` de cada acción en el array `stocks` dentro de `index.html`.
