# Guía de Contribución – Proyecto GitHub Flow

Este documento establece las políticas y buenas prácticas que todos los colaboradores deben seguir para contribuir correctamente al proyecto.

---

## Flujo de trabajo

Usamos **GitHub Flow**. Todo cambio debe:

1. Crearse en una rama distinta a `main`.
2. Subirse al repositorio remoto.
3. Pasar por un Pull Request (PR).
4. Ser revisado y aprobado por al menos un compañero.
5. Ser mergeado a `main` solo si cumple con las reglas.

---

## Nomenclatura de ramas

| Tipo       | Prefijo       | Ejemplo                        |
|------------|----------------|--------------------------------|
| Funcionalidad | `feature/`     | `feature/registro-usuarios`     |
| Corrección    | `fix/`         | `fix/error-login`              |
| Documentación | `doc/`         | `doc/manual-usuario`           |
| Pruebas       | `test/`        | `test/boton-de-envio`          |

---

## Reglas para commits

- Los mensajes deben ser claros y usar prefijos estándar:

| Tipo   | Ejemplo de mensaje                                |
|--------|---------------------------------------------------|
| `feat:`   | `feat: agregar formulario de registro`             |
| `fix:`    | `fix: corregir validación en login`                |
| `docs:`   | `docs: crear manual de usuario`                   |
| `test:`   | `test: pruebas para botón de envío`               |

---

## Pull Requests (PR)

- Cada rama debe abrir un PR hacia `main`.
- El título debe describir brevemente el cambio (`feat:`, `fix:`, etc.).
- La descripción debe explicar lo que se hizo.
- Se debe asignar mínimo **1 revisor** (compañero o profesor).
- El PR debe ser aprobado antes del merge.
- Si se solicitan cambios, el autor debe hacerlos antes de hacer merge.

---

## Revisión de código

- Leer los cambios con atención.
- Comentar errores, mejoras o dudas.
- No aprobar sin haber revisado.
- Solo hacer merge si todo está claro y probado.

---

## Limpieza de ramas

- Después de hacer merge, eliminar la rama si ya no se usará.
- Las ramas deben mantenerse actualizadas con `main`.

---

## Reglas protegidas

- Nadie puede hacer `push` directo a `main`.
- Todos los cambios deben pasar por Pull Request.
- No se permite `force push` ni eliminar `main`.

---

Gracias por contribuir de forma ordenada y profesional 🙌
