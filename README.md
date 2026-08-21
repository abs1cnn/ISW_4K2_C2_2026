# ISW_4K2_C2_2026

Repositorio correspondiente a la materia **Ingeniería de Software - 4K2 - Ciclo 2026**.
Grupo 9

## Participantes

- 85860 - Canaan, Abigail Sara
- 85817 - Calvi, Francisco
- 83573 - Begliardo, Francisco Hugo
- 93686 - Brollo, Lucas Emanuel
- 90023 - Carreras, Nicolás
- 85922 - Marrali, Matias
- 87440 - Mazzucco, Giuliano
- 63903 - Rodríguez, Fernando Marcos

## Reglas de nombrado

| Nombre                  | Regla de nombrado                           | Ubicación                                       | Extensiones admitidas                       |
| ----------------------- | ------------------------------------------- | ------------------------------------------------ | ------------------------------------------- |
| Configuración          | `ISW_[nombre_del_documento].[extensión]` | `00_Configuracion/`                            | `.pdf`                                    |
| Libros                  | `[titulo_del_libro].[extensión]`         | `01_Bibliografia/Libros/`                      | `.pdf`, `.epub`, `.docx`              |
| Papers                  | `[titulo_del_paper].[extensión]`         | `01_Bibliografia/Papers/`                      | `.pdf`                                    |
| Material complementario | `[tema].[extensión]`                     | `01_Bibliografia/Material_Complementario/`     | `.pdf`, `.docx`, `.pptx`, `.xlsx`   |
| Unidades                | `U[numero_de_unidad]`                     | `02_Unidades/`                                 | No aplica (carpeta)                         |
| Teoría                 | `[tema].[extensión]`                     | `02_Unidades/U[numero]/Teoria/`                | `.pdf`, `.pptx`, `.docx`              |
| Práctica               | `[tema].[extensión]`                     | `02_Unidades/U[numero]/Practica/`              | `.pdf`, `.docx`, `.xlsx`              |
| Resúmenes              | `Res_[tema].[extensión]`                 | `02_Unidades/U[numero]/Resumenes/`             | `.pdf`, `.docx`, `.md`                |
| Trabajos prácticos     | `TP[numero]`                              | `03_Trabajos_Practicos/`                       | No aplica (carpeta)                         |
| Consignas               | `[tema].[extensión]`                     | `03_Trabajos_Practicos/TP[numero]/Consigna/`   | `.pdf`, `.docx`                         |
| Desarrollo              | `[tema].[extensión]`                     | `03_Trabajos_Practicos/TP[numero]/Desarrollo/` | `.pdf`, `.docx`, `.xlsx`, `.drawio` |
| Entregas                | `Entrega_TP[numero].[extensión]`         | `03_Trabajos_Practicos/TP[numero]/Entrega/`    | `.pdf`, `.zip`                          |
| Parciales anteriores    | `[año]_[tema].[extensión]`              | `04_Parciales/`                                | `.pdf`                                    |
| Ejercicios              | `Ej_[tema].[extensión]`                  | `04_Parciales/` y `05_Final/`                | `.pdf`, `.docx`                         |
| Finales anteriores      | `[año]_[tema].[extensión]`              | `05_Final/Finales_Anteriores/`                 | `.pdf`                                    |
| Presentaciones          | `[tema].[extensión]`                     | `06_Clases/Presentaciones/`                    | `.pptx`, `.pdf`                         |
| Apuntes                 | `[tema].[extensión]`                     | `06_Clases/Apuntes/`                           | `.pdf`, `.docx`, `.md`                |
| Grabaciones             | `[fecha]_[tema].[extensión]`             | `06_Clases/Grabaciones/`                       | `.mp4`, `.mp3`                          |
| Trabajos de investigación | `TI[numero]`                                 | `07_Trabajos_Investigacion/`                     | No aplica (carpeta)                         |
| Lineamientos             | `[tema].[extensión]`                         | `07_Trabajos_Investigacion/Lineamientos/`        | `.pdf`, `.docx`                             |
| Desarrollo TI            | `[tema].[extensión]`                         | `07_Trabajos_Investigacion/TI[numero]/Desarrollo/` | `.pdf`, `.docx`, `.xlsx`, `.drawio`, `.pptx`  |
| Entregas TI              | `Entrega_TI[numero].[extensión]`             | `07_Trabajos_Investigacion/TI[numero]/Entrega/`   | `.pdf`, `.zip`                              |

## Estructura del repositorio

```text
ISW/
│
├── 00_Configuracion/
│
├── 01_Bibliografia/
│   ├── Libros/
│   ├── Papers/
│   └── Material_Complementario/
│
├── 02_Unidades/
│   └── U<<Nro>>/
│       ├── Notas/
│       ├── Practica/
│       └── Resumenes/
│   
│
├── 03_Trabajos_Practicos/
│   └── TP<<Nro>>/
│       ├── Consigna/
│       ├── Desarrollo/
│       └── Entrega/ 
│
├── 04_Parciales/
│   ├── Primer_Parcial/
│   │   ├── Parciales_Anteriores/
│   │   ├── Ejercicios/
│   │   └── Resumenes/
│   │
│   └── Segundo_Parcial/
│       ├── Parciales_Anteriores/
│       ├── Ejercicios/
│       └── Resumenes/
│
├── 05_Final/
│   ├── Finales_Anteriores/
│   ├── Resumenes/
│   └── Ejercicios/
│
└── 06_Clases/
│   ├── Presentaciones/
│   ├── Apuntes/
│   └── Grabaciones/
│    
└── 07_Trabajos_Investigacion/
    ├── Lineamientos/
    └── TI<<Nro>>/
        ├── Desarrollo/
        └── Entrega/
```
