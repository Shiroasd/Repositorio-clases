# Manual del DevLog del Estudiante · DSY1107

El **DevLog (Developer Log)** es la bitácora técnica y personal donde registras tu evolución durante el semestre.

---

## 1. ¿Por qué es obligatorio?

- **Visibilidad del aprendizaje:** Permite demostrar no solo el resultado final del código, sino el proceso de razonamiento y diseño.
- **Diferenciación en trabajo grupal:** Cuando se trabaja en equipo, el código es compartido pero el DevLog evidencia el aporte y comprensión personal de cada integrante.
- **Resolución reflexiva de problemas:** Documentar los bloqueos ayuda a consolidar las soluciones y evitar repetir errores.

---

## 2. Formato Obligatorio de Cada Semana

Cada archivo semanal debe ubicarse en `docs/devlog/semana-XX.md` y contener exactamente la siguiente estructura:

```markdown
# DevLog · Semana XX

## Objetivo
¿Cuál era tu meta técnica o conceptual para esta semana?

## Avance
¿Qué lograste construir o configurar concretamente? Menciona clases, endpoints, infraestructura o componentes.

## Bloqueo
¿Qué error, limitación o dificultad técnica enfrentaste y cómo lo abordaste o solucionaste?

## Aprendizaje
¿Qué concepto, patrón o herramienta aprendiste o comprendiste a fondo esta semana?

## Siguiente
¿Cuál es el siguiente paso planificado para la próxima semana?
```

---

## 3. Pautas de Calidad

- **Sé concreto:** Evita respuestas genéricas como *"trabajé en el lab"*. Prefiere: *"Implementé el enrutamiento dinámico en Spring Cloud Gateway y configuré filtros de cabeceras CORS"*.
- **No expongas secretos:** Nunca pegues contraseñas, tokens JWT, claves AWS/GCP o variables `.env` en el DevLog.
- **Actualización oportuna:** Escribe tu entrada semanal al terminar cada clase o ciclo de trabajo mientras las ideas y problemas están frescos.
