# Proyecto Formativo · DSY1107

Esta carpeta contiene el **proyecto transversal e integrador** de la asignatura.

---

## Estructura del Proyecto

```text
proyecto-formativo/
└── <nombre-proyecto>/
    ├── README.md
    ├── src/
    ├── docker-compose.yml / compose.yaml
    └── ...
```

---

## Directrices de Desarrollo

1. **Evolución continua:** El proyecto formativo evoluciona en su propio directorio durante todo el semestre.
2. **Reproducibilidad total:** Debe incluir todos los manifiestos, scripts de arranque, esquemas de bases de datos y configuraciones necesarias para que cualquier persona pueda clonar y ejecutar el sistema desde cero.
3. **Cero secretos:** Todas las credenciales deben gestionarse mediante variables de entorno o archivos de propiedades de ejemplo (ej. `.env.example`, `application-local.yml.example`).
