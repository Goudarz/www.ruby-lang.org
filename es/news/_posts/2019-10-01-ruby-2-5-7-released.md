---
layout: news_post
title: "Ruby 2.5.7 Publicado"
author: "usa"
translator: vtamara
date: 2019-10-01 11:00:00 +0000
lang: es
---

Ruby 2.5.7 ha sido publicado.


Esta versión incluye correcciones de seguridad.
Por favor revise detalles en los temas siguientes.

* [CVE-2019-16255: Una vulnerabilidad de inyeccion de código en Shell#[] y Shell#test]({% link es/news/_posts/2019-10-01-code-injection-shell-test-cve-2019-16255.md %})
* [CVE-2019-16254: Separación de respuesta HTTP en WEBrick (Corrección adicional]({% link es/news/_posts/2019-10-01-http-response-splitting-in-webrick-cve-2019-16254.md %})
* [CVE-2019-15845: Una vulnerabilidad de inyección de NUL en File.fnmatch y File.fnmatch?]({% link es/news/_posts/2019-10-01-nul-injection-file-fnmatch-cve-2019-15845.md %})
* [CVE-2019-16201: Vulnerabilidad de Denegación de Servicio en expresiones regulares de la 'autenticación de acceso con resumen' de WEBrick]({% link es/news/_posts/2019-10-01-webrick-regexp-digestauth-dos-cve-2019-16201.md %})

Vea detalles en la [bitácora de cambios](https://github.com/ruby/ruby/compare/v2_5_6...v2_5_7).

## Descargas

{% assign release = site.data.releases | where: "version", "2.5.7" | first %}

* <{{ release.url.bz2 }}>

      TAMAÑO: {{ release.size.bz2 }}
      SHA1:   {{ release.sha1.bz2 }}
      SHA256: {{ release.sha256.bz2 }}
      SHA512: {{ release.sha512.bz2 }}

* <{{ release.url.gz }}>

      TAMAÑO: {{ release.size.gz }}
      SHA1:   {{ release.sha1.gz }}
      SHA256: {{ release.sha256.gz }}
      SHA512: {{ release.sha512.gz }}

* <{{ release.url.xz }}>

      TAMAÑO: {{ release.size.xz }}
      SHA1:   {{ release.sha1.xz }}
      SHA256: {{ release.sha256.xz }}
      SHA512: {{ release.sha512.xz }}

* <{{ release.url.zip }}>

      TAMAÑO: {{ release.size.zip }}
      SHA1:   {{ release.sha1.zip }}
      SHA256: {{ release.sha256.zip }}
      SHA512: {{ release.sha512.zip }}

## Comentario de la versión

Gracias a todos los que ayudaron con esta versión.

El mantenimiento de Ruby 2.5, incluyendo esta versión,
se basan en el "Acuerdo para una versión estable de Ruby"
de la Asociación Ruby.
