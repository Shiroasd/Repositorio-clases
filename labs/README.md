# Laboratorios Cloud Native · DSY1107

Esta carpeta alberga los laboratorios de mayor alcance, microservicios y proyectos de infraestructura Cloud Native desarrollados durante el semestre.

---

## Estructura por Laboratorio

Cada laboratorio es una unidad autónoma con su propio proyecto y directorio:

```text
labs/
└── api-gateway/              # Ejemplo de laboratorio
    ├── README.md
    ├── pom.xml / build.gradle
    ├── Dockerfile
    ├── compose.yaml
    ├── src/
    ├── docs/
    └── .gitignore
```

---

## Requisitos Obligatorios del `README.md` de cada Lab

Cada laboratorio debe contar con su propio README detallando:
1. **Objetivo:** Problema técnico o arquitectónico que resuelve el componente.
2. **Arquitectura y Componentes:** Diagrama o descripción de interacción entre servicios.
3. **Requisitos:** Herramientas y versiones mínimas requeridas (Java JDK, Docker, Maven, etc.).
4. **Ejecución y Reproducibilidad:** Comandos exactos para compilar, levantar y verificar el servicio.
5. **Endpoints y Uso:** Contratos OpenAPI, llamadas `curl` o colecciones de prueba.
6. **Configuración sin secretos:** Uso de variables de entorno y perfiles sin publicar credenciales sensibles.
7. **Evidencia y Decisiones:** Capturas/logs de funcionamiento y justificación técnica de las decisiones de diseño adoptadas.

---

## Transferencia Conceptual: Local/Neutral ➔ Cloud Real

Cuando se desarrolle un par de laboratorios (implementación local vs proveedor Cloud), se debe incluir y completar la siguiente matriz:

```markdown
## Del laboratorio conceptual al laboratorio cloud

| Concepto | En local/neutral | En cloud |
|---|---|---|
| Service Discovery | Eureka / Consul | AWS Cloud Map / GCP Service Directory |
| API Gateway | Spring Cloud Gateway | AWS API Gateway / Kong Gateway |
| Configuración Centralizada | Spring Cloud Config | AWS AppConfig / SSM Parameter Store |
| Mensajería Asíncrona | RabbitMQ / Kafka Local | AWS SQS / SNS / GCP PubSub |

### Qué cambió
...

### Qué se mantuvo
...
```

> **Nota:** No basta con documentar clics en una consola; se evalúa la comprensión técnica y la transferencia de conceptos.
