# GolApuestas — T2U2 DWI

## Objetivo del proyecto

Desarrollar una pagina web estatica con **HTML y CSS** para **GolApuestas**, un sitio ficticio de apuestas de futbol. El usuario puede consultar partidos destacados con cuotas, conocer al equipo del proyecto y registrar pronosticos mediante un formulario.

El proyecto tambien demuestra el uso de **Git y GitHub** con flujo de ramas, pull requests, revision de codigo y resolucion de conflictos.

## Integrantes y roles

| Integrante   | Roles                                                        |
|--------------|--------------------------------------------------------------|
| Jaime Puente | **Lider**, **Documentador**, **Integrador** y **Disenador** |

> Proyecto individual: un solo integrante asumio los cuatro roles requeridos.

| Rol            | Responsabilidad                                              |
|----------------|--------------------------------------------------------------|
| **Lider**      | Planificacion y decisiones del proyecto                      |
| **Documentador** | README, presentacion y documentacion del flujo             |
| **Integrador** | Ramas, pull request y revision de codigo                     |
| **Disenador**  | Paleta de colores, estilos visuales y experiencia de usuario |

## Flujo de trabajo usado

Se utilizo un **Git Flow simplificado** con tres ramas:

```
main ----------------------------------------> (produccion)
  |
  +-- dev --------> desarrollo de paginas y estilos base
  |
  +-- diseno -----> mejoras visuales y estilos adicionales
```

1. **Rama `main`:** codigo estable listo para entrega (estructura inicial).
2. **Rama `dev`:** desarrollo de paginas (`partidos.html`, `equipo.html`, `apuestas.html`) y estilos base (`css/estilos.css`).
3. **Rama `diseno`:** refinamiento visual con `css/diseno.css` y ajustes en el titulo de `index.html`.
4. **Conflicto:** al integrar `diseno` en `dev`, hubo conflicto en el `<title>` de `index.html`; se resolvio manteniendo `GolApuestas | T2U2 DWI`.
5. **Pull Request:** se abrio un PR de `dev` hacia `main`, se reviso el codigo (rol integrador) y se hizo merge.
6. **Commits:** mensajes descriptivos con prefijos `feat:`, `style:`, `docs:` y `merge:`.

## Estructura del sitio

| Pagina          | Contenido                                      |
|-----------------|------------------------------------------------|
| `index.html`    | Pagina de inicio con seccion hero              |
| `partidos.html` | Partidos destacados con cuotas                 |
| `equipo.html`   | Integrante y roles del proyecto                |
| `apuestas.html` | Formulario para registrar pronosticos          |

**Repositorio:** https://github.com/JaimeP-0/T2U2-DWI
