# Presentacion — T2U2 DWI | GolApuestas

**Repositorio publico:** https://github.com/JaimeP-0/T2U2-DWI

---

## 1. Introduccion

**GolApuestas** es una landing page ficticia de apuestas de futbol, desarrollada con **HTML y CSS** para la materia de Desarrollo Web Integral (DWI).

El proyecto cumple dos objetivos:

- Crear un sitio web funcional, responsive y con navegacion entre paginas.
- Demostrar el uso de **Git y GitHub** con ramas, commits descriptivos, pull requests y flujo de trabajo colaborativo (en este caso, asumiendo los cuatro roles de forma individual).

---

## 2. Objetivo del proyecto

Desarrollar un sitio web de apuestas de futbol donde el usuario pueda:

- Conocer la propuesta de **GolApuestas** (partidos, cuotas y pronosticos).
- Explorar **partidos destacados** con cuotas de ejemplo.
- Ver informacion del **equipo** del proyecto.
- **Registrar apuestas** mediante un formulario con seleccion de partido y pronostico.

Tecnologias utilizadas: **HTML5**, **CSS3** (variables, Flexbox, Grid, media queries) y **Git/GitHub**.

---

## 3. Integrante y roles

| Integrante   | Roles                                                        |
|--------------|--------------------------------------------------------------|
| Jaime Puente | Lider, Documentador, Integrador y Disenador                 |

Proyecto **individual**: un solo integrante asumio los cuatro roles requeridos:

| Rol            | Actividad realizada                                      |
|----------------|----------------------------------------------------------|
| **Lider**      | Planificacion y decisiones del proyecto                  |
| **Documentador** | README, presentacion y documentacion del flujo         |
| **Integrador** | Ramas, pull request y revision de codigo                 |
| **Disenador**  | Estilos visuales, paleta de colores y experiencia de uso |

---

## 4. Estructura del sitio web

El sitio esta dividido en **paginas HTML separadas**:

| Pagina          | Contenido                                      |
|-----------------|------------------------------------------------|
| `index.html`    | Pagina de inicio con seccion hero              |
| `partidos.html` | Tarjetas de partidos con cuotas                |
| `equipo.html`   | Integrante y roles del proyecto T2U2           |
| `apuestas.html` | Formulario para registrar pronosticos          |

**Estilos:**

- `css/estilos.css` — estilos base (layout, colores, responsive).
- `css/diseno.css` — mejoras visuales (efectos, gradientes, animaciones).

**Diseno:** tema oscuro tipo cancha de futbol, con acentos verde (`#00c853`) y dorado (`#ffd600`).

---

## 5. Flujo de trabajo con Git y GitHub

Se utilizo un **Git Flow simplificado** con tres ramas:

```
main ----------------------------------------> (produccion)
  |
  +-- dev --------> desarrollo del sitio completo
  |
  +-- diseno -----> estilos visuales adicionales
```

### Rama `main`

Codigo estable en produccion. Contiene la estructura inicial del proyecto.

### Rama `dev`

Desarrollo del sitio completo:

1. Paginas de partidos, equipo y apuestas.
2. Estilos base (`css/estilos.css`).
3. Documentacion (`README.md` y presentacion).

### Rama `diseno`

Refinamiento visual: vinculacion de `diseno.css` y ajustes en el titulo de la pagina.

---

## 6. Commits descriptivos

Se usaron mensajes claros con prefijos convencionales:

| Prefijo   | Uso                                      | Ejemplo                                              |
|-----------|------------------------------------------|------------------------------------------------------|
| `feat:`   | Nueva funcionalidad o contenido          | `feat: agregar paginas de partidos, equipo y apuestas` |
| `style:`  | Cambios visuales                         | `style: agregar estilos de diseno visual`            |
| `docs:`   | Documentacion                            | `docs: agregar README y presentacion del proyecto`   |

---

## 7. Pull Request y revision de codigo

Se creo un **Pull Request** de la rama `dev` hacia `main`:

- **PR:** https://github.com/JaimeP-0/T2U2-DWI/pull/2
- **Titulo:** feat: integrar sitio completo GolApuestas desde rama dev
- **Revision:** se reviso la estructura HTML, la navegacion entre paginas, los estilos responsive y el README.
- **Resultado:** merge aprobado e integrado a `main`.

---

## 8. Resolucion de conflictos

Durante el desarrollo se simulo un conflicto al modificar el `<title>` de `index.html` en ramas distintas:

| Rama     | Valor del titulo              |
|----------|-------------------------------|
| `dev`    | `GolApuestas - Apuestas deportivas` |
| `diseno` | `GolApuestas | T2U2 DWI`        |

**Resolucion:** se mantuvo `GolApuestas | T2U2 DWI` para conservar coherencia con el nombre del proyecto academico.

---

## 9. Conclusion

El proyecto **GolApuestas** cumple con los requisitos de la practica:

- Sitio web con HTML + CSS, responsive y navegable.
- Repositorio publico en GitHub con ramas `main`, `dev` y `diseno`.
- Commits descriptivos y pull request con revision de codigo.
- Documentacion en README y presentacion del flujo de trabajo.

**Repositorio:** https://github.com/JaimeP-0/T2U2-DWI

**Pull Request:** https://github.com/JaimeP-0/T2U2-DWI/pull/2

---

*T2U2 DWI — Desarrollo Web Integral — 2026*
