<table align="center"><tr><td colspan="4" align="center" width="9999">

<br/>

# Inteligencia de Negocios: Laboratorio SSIS

<br/>

Laboratorio SSIS para la materia de Inteligencia de Negocios

</td></tr></table>

## Tabla de contenido

- [Inteligencia de Negocios: Laboratorio SSIS](#inteligencia-de-negocios-laboratorio-ssis)
  - [Tabla de contenido](#tabla-de-contenido)
  - [Requisitos](#requisitos)
  - [Instalación](#instalación)
  - [Instrucciones de lecciones](#instrucciones-de-lecciones)
  - [Estilos de commits](#estilos-de-commits)
    - [Formato de commits](#formato-de-commits)

## Requisitos

- [Visual Studio 2019](https://my.visualstudio.com/Downloads?q=visual%20studio%202019&wt.mc_id=o~msft~vscom~older-downloads)
- [SQL Server Integration Services Projects](https://my.visualstudio.com/Downloads?q=visual%20studio%202019&wt.mc_id=o~msft~vscom~older-downloads)
- [Adventure Works](https://utpac.sharepoint.com/:u:/s/2022-BI1IF241/EQHh3nsh2clGuTVUruu5dUkBX9auyC4AlIbXs81JZYspag?e=amXqd7)
- [Sample Currency Data](https://utpac.sharepoint.com/:t:/s/2022-BI1IF241/EfNBC-cb795BmURnzsMX508BHxJhm7ZJDxAEUmXgSa_Q1w?e=j0r2EJ)



## Instalación

Abrir este proyecto desde Visual Studio 2019 con el paquete de

## Instrucciones de lecciones

Todas las instrucciones de las lecciones están en este [enlace](https://learn.microsoft.com/en-us/sql/integration-services/lesson-1-create-a-project-and-basic-package-with-ssis?view=sql-server-ver16)

También para configurar el setup, se puede encontrar en la carpeta de setup.


## Estilos de commits

Se estarán realizando [commits](https://github.com/git-guides/git-commit) de la siguiente manera. Es importante destacar que se siga el estilo de commits de esa manera, de lo contrario no se aceptará el commit al hacer [push](https://git-scm.com/docs/git-push) en el repositorio.

Esto con la finalidad de seguir un orden, está establecido por [expresiones regulares](https://github.com/ziishaned/learn-regex/blob/master/README.md). Sigue este patrón

```
(🐛 FIX|🚀 RELEASE|📖: DOC|👌 IMPROVE|📦 NEW|🧪 TEST|⚙️  PROGRESS): (.*?)[A-z0-9] - [A-z0-9](.*?)*
```

Si desea aprender más de regex leer este [enlace](https://regexr.com/).

### Formato de commits

[ícono] [tipo de commit]: [mensaje] - [descripción]

`🐛 FIX: Mensaje - Arreglo de bug`

`🚀 RELEASE: Mensaje - Nueva versión a producción`

`📖 DOC: Mensaje - Documentación`

`👌 IMPROVE: Mensaje - Mejora de alguna funcionalidad`

`📦 NEW: Mensaje - Nueva característica añadida`

`🧪 TEST: Mensaje - Test generado`

`⚙️ PROGRESS: Mensaje - Se utiliza para hacer save-point`

`🌠 MERGE: Mensaje - Se unen ramas de git`

