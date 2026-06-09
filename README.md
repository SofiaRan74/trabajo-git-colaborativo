# Trabajo Colaborativo con Git y GitHub

## Integrantes y Roles

| Integrante   | Rol          |
| ------------ | ------------ |
| Sofía Rangel | Líder        |
| Raúl Fraire | Documentador |
| Daniel Nolberto | Integrador   |
| Alicia Delgadillo | Diseñador    |

## Descripción del Proyecto

Este proyecto consiste en una página web sencilla desarrollada con HTML y CSS con el objetivo de practicar el uso de Git y GitHub para el control de versiones, el trabajo con ramas, la integración de cambios mediante Pull Requests y la resolución de conflictos.

## Estructura del Proyecto

```text
trabajo-git-colaborativo/
│
├── README.md
├── index.html
└── css/
    └── estilos.css
```

## Flujo de Trabajo

### 1. Creación del Repositorio

Se creó un repositorio en GitHub llamado **trabajo-git-colaborativo**, el cual sirve como espacio central para almacenar y administrar el proyecto.

### 2. Asignación de Roles

Para simular un entorno de trabajo colaborativo se asignaron los siguientes roles:

* Líder
* Documentador
* Integrador
* Diseñador

### 3. Desarrollo del Proyecto Web

Se desarrolló una página web básica utilizando:

* HTML para la estructura del sitio.
* CSS para el diseño y estilos visuales.

### 4. Creación de Ramas

Se implementó una estrategia de trabajo basada en ramas para separar los cambios realizados durante el desarrollo.

#### Rama Principal

* **main**

  * Contiene la versión estable y consolidada del proyecto.

#### Ramas de Desarrollo

* **dev**

  * Utilizada para agregar nuevas funcionalidades y contenido al sitio web.

* **diseno**

  * Utilizada para realizar modificaciones relacionadas con el diseño y la apariencia visual.

### 5. Cambios Realizados

#### Rama dev

* Se agregó una sección de características del proyecto.
* Se incorporó contenido adicional a la página principal.

#### Rama diseno

* Se modificó el diseño visual del sitio.
* Se agregó un color de fondo.
* Se realizaron mejoras estéticas mediante CSS.

### 6. Pull Request

Se creó un Pull Request para integrar los cambios realizados en la rama **dev** hacia la rama **main**.

Este proceso permitió revisar los cambios antes de incorporarlos a la versión principal del proyecto.

### 7. Resolución de Conflictos

Para demostrar el manejo de conflictos, se realizaron modificaciones sobre la misma línea del archivo `index.html` en diferentes ramas.

Al intentar fusionar las ramas, GitHub detectó un conflicto de fusión debido a que ambos cambios afectaban la misma sección del código. Posteriormente se revisó el conflicto y se seleccionó la versión final que debía conservarse.

## Ramas Utilizadas

| Rama   | Propósito                                |
| ------ | ---------------------------------------- |
| main   | Versión principal y estable del proyecto |
| dev    | Desarrollo de nuevas funcionalidades     |
| diseno | Modificaciones de diseño y estilos       |

## Historial de Commits

Durante el desarrollo se utilizaron mensajes descriptivos siguiendo buenas prácticas:

```bash
docs: agregar asignación de roles
feat: agregar página principal
style: agregar estilos iniciales
feat: agregar sección de características
style: mejorar diseño visual de la página
update: cambiar título principal en main
update: modificar encabezado principal en diseno
fix: resolver conflicto de fusión
```

## Tecnologías Utilizadas

* HTML5
* CSS3
* Git
* GitHub

## Conclusión

La realización de esta práctica permitió comprender el funcionamiento de Git y GitHub en un entorno colaborativo, aplicando conceptos como control de versiones, trabajo con ramas, integración de cambios mediante Pull Requests y resolución de conflictos durante el desarrollo de software.
