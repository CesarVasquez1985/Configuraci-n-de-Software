# Documento de Diseño del Software (SDD)

## 1. Arquitectura General
El sistema sigue una arquitectura modular, separando la configuración, la documentación y el código fuente para facilitar el mantenimiento y la escalabilidad.

## 2. Componentes Principales

- **Frontend (src/index.html):** Página principal que muestra el mensaje de bienvenida y la versión del proyecto.
- **Configuración (config/config.example):** Archivo de ejemplo para definir variables de entorno y parámetros de personalización.
- **Documentación (docs/SRS, docs/SDD):** Documentos técnicos que guían el desarrollo y mantenimiento.

## 3. Decisiones Técnicas

- Se utiliza HTML puro para la interfaz inicial, permitiendo una rápida visualización y fácil extensión futura.
- La configuración se externaliza para evitar hardcoding y facilitar la personalización.
- La documentación se mantiene en Markdown para facilitar la colaboración y el versionado.

## 4. Diagrama de Componentes

```
+-------------------+
|  index.html       |
+-------------------+
         |
         v
+-------------------+
|  config.example   |
+-------------------+
```

## 5. Justificación

- La simplicidad inicial permite iterar rápidamente y establecer una base clara.
- La separación de responsabilidades mejora la mantenibilidad y la colaboración.

---

> Para requisitos detallados, consulte `/docs/SRS/SRS_v1.md`.
