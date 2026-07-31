# Sistema de Inventario para Ferretería — Grupo 12

**Grupo #12 — Ingeniería de Software I**
**Docente:** Ms. Carlota Delgado Vera  
**Universidad Agraria del Ecuador** | 3SA | Julio 2026

---

## Descripción del proyecto

Sistema web para la gestión de inventarios de una ferretería, permitiendo el control de productos, proveedores, entradas y salidas de stock, así como la generación de reportes básicos. Desarrollado bajo el **modelo incremental** con 4 incrementos en 14 semanas.

## Objetivo general

Diseñar la documentación y los prototipos de un sistema de control de inventario para ferretería, aplicando los principios de Ingeniería de Software para modelar la solución.

## Integrantes del equipo

| Nombre | Rol |
|--------|-----|
| Henry Pazmiño | Líder de proyecto / Backend |
| Cindy Ayoví | Frontend / Documentación |
| José Malavé | Base de datos / Pruebas |

## Funcionalidades principales

1. **Gestión de productos:** ABM (Altas, Bajas y Modificaciones) con código, nombre, categoría, precio y stock.
2. **Control de existencias:** Actualización automática del stock al registrar entradas y salidas.
3. **Gestión de proveedores:** Registro de proveedores con datos de contacto.
4. **Alertas de stock mínimo:** Notificaciones visuales cuando un producto baja del límite.
5. **Reportes básicos:** Exportación de inventario y movimientos en PDF y Excel.

## Herramientas utilizadas

| Herramienta | Versión | Propósito |
|-------------|---------|-----------|
| Python | 3.11 | Lenguaje de programación |
| Flask | 3.x | Framework web backend |
| MySQL | 8 | Base de datos relacional |
| Bootstrap | 5 | Framework frontend |
| Git / GitHub | — | Control de versiones |
| Draw.io | — | Diagramas UML y prototipado |
| Visual Studio Code | — | IDE de desarrollo |

## Entregables

La carpeta `entregables/` contiene los documentos finales de cada incremento del proyecto:

- **Entregable1_Propuesta_Grupo12_Ferreteria.pdf** — Incremento 1: Propuesta, RF/RNF, WBS, RACI
- **entregable2_grupo12_ferreteria.pdf** — Incremento 2: Arquitectura 3 capas, diagramas UML, modelo E-R
- **Entregable3_Grupo12_Ferreteria.pdf** — Incremento 3: Prototipado responsive en Figma
- **Entregable4_Grupo12_Ferreteria.pdf** — Incremento 4: Pruebas, riesgos, documentación final

## Presentación

`Presentacion_IngSoftware_Grupo12.pptx` — Slides de la exposición del proyecto (13 diapositivas).

## Estructura del repositorio

```
├── design/           # Diseño UX, mockups, diagrama de clases
├── docs/             # Requisitos, cronograma, casos de uso
├── entregables/      # Documentos PDF finales del proyecto
├── src/              # Código fuente (Flask + MySQL)
├── tests/            # Pruebas unitarias
└── README.md
```

## Estado actual del proyecto

📌 **Completado.** Los 4 incrementos fueron desarrollados: Análisis → Diseño → Desarrollo → Cierre. Documentación, prototipos y presentación finalizados.
