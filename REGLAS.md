# Reglas

Valen para todos los repos de matcarfer. La misma copia está en `biblioteca` (antes `library`) y en `llaves`.

## Todos los repos públicos

1. Menos es más: descripción corta y simple, con fotos.
2. El link de descarga va al principio, grande y fácil de ver.
3. Español por defecto (`README.md`) y un link a inglés (`README.en.md`).
4. TODOS los repos llevan la licencia completa en español (`LICENSE`) y en inglés (`LICENSE.en`). En el README va resumida en una línea, con link.
5. Todas las apps son de código cerrado: código en un repo privado `<App>-source`; el público `<App>` solo tiene README, licencia, privacidad, fotos y la descarga en Releases.
6. Mismo modelo de licencia y mismos links de colaboración en el repo y dentro de la app, siempre en este orden: Cafecito (https://cafecito.app/matcarfer), Matecito (https://www.matecito.co/matcarfer), Mercado Pago (https://link.mercadopago.com.ar/matcarfer), Ko-fi (https://ko-fi.com/matcarfer), Patreon (https://www.patreon.com/matcarfer). En `.github/FUNDING.yml` el mismo orden.
7. En Releases queda SOLO la última versión. Las anteriores se borran.
8. Nombre público: matcarfer. Sin datos personales. Única excepción: el email de contacto, solo en el repo de la demo de cada app paga.
9. Las llaves de firma no se publican nunca.
10. Compatibilidad como rango: "Compatible con Android X a Y". Y es la última versión probada de verdad. Nunca "X+".
11. Todo repo público lleva topics.
12. Ninguna demo menciona a un cliente: nombre, logo y colores propios.
13. Antes de modificar, mostrar qué se va a hacer y cómo, y esperar el OK.
14. ID interno de toda app Android propia: `io.github.matcarfer.<app>` (minúsculas, sin guiones ni espacios). El nombre visible no lleva matcarfer. Al migrar no importa tener que desinstalar la versión anterior.

## Biblioteca (`biblioteca`)

1. Español primero: `README.md` en español, `README.en.md` en inglés. Todo cambio va en los dos.
2. Una tabla por categoría: Android, Windows. Nada de gaming: va en `biblioteca-gaming`. Dentro de cada una, pagas (con demo gratis) primero y gratis después. Una sección sin apps no se muestra.
3. El email de contacto no va en la biblioteca.
4. Dentro de cada sección, orden alfabético. A la izquierda del nombre va el ícono de la app.
5. Columnas: Nombre (con link) y Descripción, de un renglón corto. Sin versión ni fecha; los detalles van en el repo.
6. Solo links al repo de cada app, nunca a la descarga. La biblioteca no tiene releases.
7. Cada app tiene su propia licencia, en su repo y dentro de la app.

## Biblioteca gaming (`biblioteca-gaming`)

1. Mismas reglas que `biblioteca`, solo para gaming. Secciones: Android, Trainers.
2. Aclarar al pie que las donaciones no corresponden a LD Studio.

## Al publicar una app

1. Probarla en los celulares y sacar las fotos ahí.
2. En Descargas de cada celular queda solo el último APK de esa app.
3. Verificar la firma, la descarga y los links. Actualizar la biblioteca que corresponda.
