# Guía de Mensajes de Commit

Esta guía define el estilo de commits para el equipo, basada en Conventional Commits.

## Formato
prefijo(<área>): <descripción breve>

---

## 📂 Tipos de commit

| Prefijo   | Uso                          | Ejemplo |
|-----------|------------------------------|---------|
| feat:     | Nueva funcionalidad          | feat(reservas): agregar validación de fechas |
| fix:      | Corrección de errores        | fix(sql): corregir conflicto de puerto en MariaDB |
| docs:     | Cambios en documentación     | docs(readme): añadir instrucciones de instalación |
| style:    | Cambios de formato (no funcionales) | style(css): ajustar márgenes en formulario |
| refactor: | Reestructuración de código   | refactor(api): simplificar lógica de reservas |
| test:     | Cambios en pruebas           | test(ci): agregar pruebas unitarias para pipeline |
| chore:    | Tareas menores (dependencias, configs) | chore(deps): actualizar versión de Docker |

---

## ✅ Buenas prácticas
- Usar **imperativo**: "add banner" en lugar de "added banner".
- Ser **específico**: evitar "update" o "changes".
- Mantener **consistencia** en todo el equipo.
- Título breve (~50 caracteres).
- Cuerpo opcional para explicar el **porqué** del cambio.
- Footer opcional para referencias a tickets/issues.

---

## 📖 Ejemplo completo
     docs(assets): mover banner corporativo a carpeta docs/assets
