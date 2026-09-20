# El dominio propio está en pausa a propósito

El archivo `CNAME` está renombrado a **`CNAME.pendiente`**.

**Por qué:** mientras exista `CNAME`, GitHub Pages manda todo a
`luminaiastudio.com`. Y como los registros de DNS todavía no están cargados en
GoDaddy, esa dirección no resuelve y **el sitio no se puede abrir por ningún
lado** — ni siquiera por la dirección provisoria de GitHub.

Sin `CNAME`, el sitio vive en:
**https://lunanidialuna-glitch.github.io/Luminaiastudio/**

## Cómo se vuelve al dominio propio

1. Cargar en GoDaddy los cuatro registros **A** con nombre `@`:
   `185.199.108.153` · `185.199.109.153` · `185.199.110.153` · `185.199.111.153`
2. Y un **CNAME** con nombre `www` → `lunanidialuna-glitch.github.io`
3. Renombrar `CNAME.pendiente` de vuelta a `CNAME` y publicar.
4. En GitHub → Settings → Pages → *Custom domain*, escribir `luminaiastudio.com`
   y esperar a que valide. Después tildar *Enforce HTTPS*.
