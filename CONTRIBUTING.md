# Guía de Contribución y Políticas de Equipo

## 👥 Integrantes y Roles

| Nombre completo                     | Rol                       |
|-------------------------------------|----------------------------|
| Meza Vilorio Amairany              | Control de documentación   |
| Romero Aguilar Luis Salvador       | Revisión de código (líder de QA) |
| Torres Bernabé Moisés              | Programador backend        |
| Xocua Márquez César Héctor         | Programador frontend       |
| Zamora Vega Luis Ángel             | Coordinador general / DevOps |

---

## 🚀 Flujo de trabajo colaborativo

1. Crear una **rama nueva** desde `main` para cada nueva tarea, usando nombres claros:
   - `feature/nombre-tarea`
   - `fix/nombre-arreglo`
   - `docs/nombre-documento`

2. Hacer cambios **solo en tu rama**. Nunca trabajes directo en `main`.

3. Usar commits claros y en presente:
   - `test: agrega botón de inicio`
   - `fix: corrige validación en login`
   - `docs: actualiza README con pasos`
   - `doc: actualiza README con pasos`

4. **Hacer Pull Request (PR)** cuando termines tu parte.

5. **Esperar revisión** de al menos 1 compañero (o del QA o Coordinador).

6. Una vez aprobado, hacer merge a `main`.

---

## ✅ Reglas para Pull Requests

1. El título debe comenzar con el tipo de cambio:
   - `feat:`, `fix:`, `docs:`, `test:`, `feature:`

2. La descripción debe incluir:
   - Qué hiciste
   - Qué archivo(s) modificaste
   - Captura de pantalla (si aplica)
   - Cómo probar el cambio

3. No hacer merge sin aprobación, salvo que lo autorice el coordinador.

4. Si hay conflictos, comunícalo y resuélvelo **antes** del merge.

---

## 📌 Ejemplo para hacer Pull Request

### Supongamos que modificaste `README.md` y estás en la rama `fix/actualizar-readme`

#### 1. Sube los cambios:
```bash
git add README.md
git commit -m "docs: actualizar README con instrucciones del login"
git push origin fix/actualizar-readme
