# NoSQL Explorer Releases

Repositorio público de artefactos generados para NoSQL Explorer. El código fuente y las
contribuciones viven en el repositorio privado `emmarquez_meli/nosql-explorer`; este repositorio
no contiene código de la aplicación.

## Descargar

- [Última versión estable](https://github.com/emiliano7724/nosql-explorer-releases/releases/latest)
- [Todas las versiones](https://github.com/emiliano7724/nosql-explorer-releases/releases)

Cada release estable contiene:

- `NoSQL-Explorer-<versión>-macOS.dmg`: instalador para Apple Silicon.
- `appcast.xml`: metadata firmada correspondiente a esa versión.

El release técnico
[`appcast-feed`](https://github.com/emiliano7724/nosql-explorer-releases/releases/tag/appcast-feed)
mantiene el feed acumulado que Sparkle consulta para detectar actualizaciones. No es una versión
instalable.

## Publicación

Los artefactos se generan desde el repositorio fuente, se validan y se firman con EdDSA antes de
publicarse. Cuando la GitHub App publicadora esté configurada, el workflow de Release será el único
actor autorizado para cargar versiones; los binarios y el appcast no deben construirse ni editarse
manualmente en este repositorio.
