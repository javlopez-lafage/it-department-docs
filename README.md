# Documentación de Proyectos de TI

Este repositorio centraliza la **documentación técnica** de todos los proyectos de TI de la empresa.  
Aquí encontrarás información organizada sobre arquitectura, bases de datos, CI/CD, infraestructura y procedimientos generales, guías de implementación y solución de errores.

---

## 📂 Estructura del repositorio

- **/docs/arquitectura**  
  Diagramas y descripciones de arquitecturas de sistemas.

- **/docs/base_datos**  
  Modelos de datos, scripts SQL, esquemas y migraciones.

- **/docs/ci_cd**  
  Pipelines de integración y despliegue continuo (GitHub Actions, etc.).

- **/docs/infraestructura_general**  
  Configuración de servidores, contenedores, puertos y servicios (SQL Server, MariaDB, Redis).

- **/docs/procedimientos**  
  Guías paso a paso para instalación, conexión y administración.

- **/docs/proyectos**  
  Documentación específica de cada proyecto:
  - `proyecto_reservas`
  - `proyecto_erp`
  - `proyecto_webapp`
  - etc.

---

## 🎯 Objetivos

- Mantener documentación clara, accesible y versionada.
- Facilitar el onboarding de nuevos miembros del equipo.
- Servir como referencia para auditorías, soporte y evolución de proyectos.
- Asegurar trazabilidad de decisiones técnicas.

---

## 🛠 Buenas prácticas

1. **Versionar la documentación**: cada cambio debe registrarse con un commit.
2. **Usar Markdown**: formato ligero y compatible con GitHub/Notion.
3. **Mantener diagramas actualizados**: usar Draw.io, PlantUML o Mermaid.
4. **Automatizar documentación técnica**: Swagger/OpenAPI para APIs.
5. **Checklist de procesos**: cada paso documentado para replicabilidad.

---

## 📌 Cómo contribuir

1. Clonar el repositorio.
2. Crear una rama para cambios.
3. Editar o crear archivos en `/docs`.
4. Hacer commit y push.
5. Crear un Pull Request para revisión.

---

## 🚀 Configuración inicial

Este repositorio incluye scripts para configurar automáticamente la plantilla de commits y el editor de Git.

### 🐧 Linux/Mac
Después de clonar el repositorio, ejecuta:

```bash
./setup.sh
```

### 🪟 Windows
Después de clonar el repositorio, ejecuta:

```bash
.\setup.ps1
```

### ✅ ¿Qué hace?
- Configura la plantilla de commits (`docs/commit-template.txt`) para que cada commit siga el estándar definido.
- Configura VS Code como editor por defecto de Git (`code --wait`).
- Facilita el onboarding: cada vez que hagas `git commit`, se abrirá VS Code con la plantilla lista para editar.

---

## 📜 Licencia

Este repositorio es de uso interno.  
Si se publica, se recomienda licencia **MIT** o **Apache 2.0** para permitir libre lectura y uso con atribución.
