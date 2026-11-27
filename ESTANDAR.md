# Estándar de codificación Equipo 2

Lenguaje(s) del proyecto formativo: PHP, HTML5, CSS3, JavaScript, SQL (MySQL)

## 1. Nombrado
(pendiente)

## 2. Formato
(pendiente)

## 3. Comentarios y documentación
(pendiente)

## 4. Estructura de carpetas
(pendiente)

## 5. Git: ramas, commits y pull requests

### Convención de ramas
Cada tarea o entrega debe desarrollarse en una rama independiente creada desde `main`, siguiendo el formato `<tipo>/<descripcion-corta>`:
* `feat/<nombre-funcionalidad>`: para nuevas características o secciones.
* `fix/<descripcion-error>`: para corrección de errores.
* `docs/<descripcion-cambio>`: para cambios en documentación o fichas (ej. `docs/visita-maicol-tovar`).
* `chore/<tarea>`: para configuraciones o mantenimiento (ej. `chore/editorconfig`).

### Convención de commits (Conventional Commits)
Los mensajes de commit deben ser claros, en español y seguir la estructura `<tipo>: <descripción>`:
* `feat:` nuevas funcionalidades o archivos principales.
* `fix:` corrección de errores en código o formato.
* `docs:` cambios en archivos `.md` o documentación.
* `chore:` tareas de configuración como `.editorconfig` o `.gitignore`.

### Flujo de Pull Requests (PR)
1. **No hacer push directo a `main`:** todos los cambios entran mediante Pull Request hacia la rama `main` del repositorio principal.
2. **Título del PR:** debe seguir el formato de Conventional Commits (ej. `docs: visita de maicol-tovar (Equipo 3)`).
3. **Revisión:** el líder del equipo o al menos un compañero revisa los cambios antes de hacer **Merge**.
4. **Sincronización:** mantener la rama actualizada con `main` antes de abrir el PR para evitar conflictos.