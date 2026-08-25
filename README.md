# DSY1107 · Repositorio del Estudiante

**Asignatura:** DSY1107  
**Sección:** 003D  
**Estudiante:** Gaspar Toro  
**Package raíz personal:** `cl.duoc.gtoro`

---

## Seguimiento
- [DevLog](docs/devlog/)

---

## Estructura del Repositorio

```text
DSY1107-003D-gaspar-toro/
├── README.md                 # Documentación raíz del repositorio
├── .gitignore                # Exclusiones de artefactos compilados, temporales y secretos
├── docs/                     # Documentación transversal y DevLog
│   ├── README.md
│   ├── DEVLOG-ESTUDIANTE.md
│   └── devlog/
│       ├── README.md
│       ├── template.md
│       └── semana-01.md
├── practica/                 # Práctica corta organizada por conceptos
│   └── README.md
├── labs/                     # Laboratorios Cloud Native modulares
│   └── README.md
├── proyecto-formativo/       # Proyecto integrador transversal del semestre
│   └── README.md
├── desafios/                 # Retos y desafíos formativos
│   └── README.md
└── evaluaciones/             # Evaluaciones sumativas del semestre
    ├── README.md
    ├── ep1/
    ├── ep2/
    ├── ep3/
    └── eft/
```

---

## Relación entre Evidencias

| Evidencia | Propósito |
|---|---|
| **Código / Configuración** | Qué construiste. |
| **Commits** | Cómo fue cambiando a lo largo del tiempo. |
| **README** | Cómo se reproduce, ejecuta y evalúa cada componente. |
| **DevLog** | Qué ocurrió, qué aprendiste, dificultades superadas y próximos pasos. |

---

## Flujo Git Mínimo

Al comenzar a trabajar:
```bash
git pull
```

Al terminar una sesión o hito relevante:
```bash
git status
git add .
git commit -m "feat(área): descripción concisa del cambio"
git push
```

> **Regla:** Debe existir un solo `.git` en la raíz del repositorio personal.

---

## Checklist de Cumplimiento

- [x] Repositorio público con nomenclatura oficial (`DSY1107-003D-gaspar-toro`).
- [x] Estructura base de carpetas y `.gitignore` sin secretos configurados.
- [ ] `docs/devlog/` actualizado con la entrada semanal correspondiente.
- [ ] DevLog estructurado con: Objetivo, Avance, Bloqueo, Aprendizaje y Siguiente.
- [ ] DevLog sin secretos ni credenciales sensibles.
- [ ] Labs y proyectos contienen todo lo necesario para reproducir su ejecución.
- [ ] Conceptos y transferencias local → cloud documentados adecuadamente.
- [ ] Todos los READMEs requeridos creados y actualizados.
- [ ] Commits y pushes verificados en GitHub.
