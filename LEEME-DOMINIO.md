# El dominio propio — conectado el 20/09/2026

`CNAME` contiene `luminaiastudio.com`. GitHub Pages lo lee de ahí y sirve el
sitio en el dominio propio.

## Lo que se cargó en GoDaddy

| Tipo | Nombre | Valor |
|---|---|---|
| A | `@` | `185.199.108.153` |
| A | `@` | `185.199.109.153` |
| A | `@` | `185.199.110.153` |
| A | `@` | `185.199.111.153` |

Se borró el registro `A @ → WebsiteBuilder Site`, que mandaba el dominio a la
página de GoDaddy.

**Verificado:** `luminaiastudio.com` resuelve a las cuatro direcciones de GitHub
Pages.

## El `www` quedó sin tocar — a propósito

El registro `CNAME www → luminaiastudio.com` **GoDaddy no lo deja editar ni
borrar** (el ícono de editar y el de borrar aparecen deshabilitados).

**No bloquea nada.** Los cuatro registros `A` son los que hacen funcionar
`luminaiastudio.com`, que es la dirección que se comparte. El `www` sólo haría
que `www.luminaiastudio.com` también ande.

**Si en algún momento se quiere resolver:** el registro se destraba desde
*Servicios → Sitio web* de GoDaddy, desvinculando el WebsiteBuilder del dominio;
después se puede editar. No vale la pena hacerlo hasta que haga falta.

## Si alguna vez hay que volver atrás

Renombrar `CNAME` a `CNAME.pendiente` y publicar. El sitio vuelve a
`https://lunanidialuna-glitch.github.io/Luminaiastudio/`.
