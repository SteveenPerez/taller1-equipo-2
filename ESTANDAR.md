# Estándar de codificación Equipo 2

Lenguaje(s) del proyecto formativo: PHP, HTML5, CSS3, JavaScript, SQL (MySQL)

## 1. Nombrado

| Elemento | Convención | Ejemplo |
| :--- | :--- | :--- |
| Variables | `camelCase` | `$nombreUsuario` / `nombreUsuario` |
| Funciones y métodos | `camelCase` + verbo | `calcularTotal()`, `registrarCita()` |
| Clases | `PascalCase` | `UsuarioController`, `ReservaModel` |
| Constantes | `UPPER_SNAKE_CASE` | `MAX_INTENTOS`, `DB_HOST` |
| Archivos | `kebab-case` | `procesar-login.php`, `estilos-panel.css` |
| Carpetas | `kebab-case` | `controladores`, `vistas` |
| Tablas y campos BD | `snake_case` | `usuarios`, `fecha_registro` |

* **Idioma:** Todos los identificadores se escriben en **español**, sin tildes ni letra `ñ` (ej. `contrasena`, `ano_ingreso`).

## 2. Formato

* **Indentación:** 4 espacios (sin tabulaciones).
* **Comillas:** Comillas simples (`'...'`) por defecto en PHP y JavaScript; comillas dobles (`"..."`) en atributos HTML y cadenas con interpolación de variables.
* **Largo máximo de línea:** 100 caracteres.
* **Llaves:** Llave de apertura en línea nueva para clases y métodos en PHP (PSR-12); llave de apertura en la misma línea para estructuras de control (`if`, `for`, `while`), funciones JS y reglas CSS[cite: 1].

## 3. Comentarios y documentación
Cuándo comentar: Cuando el código sea difícil de entender o tenga procesos importantes. Los comentarios deben ser claros y breves.

Cómo documentar funciones: Explicar qué hace la función, qué datos recibe (parámetros) y qué resultado devuelve.

Qué debe tener el README: Nombre del proyecto, descripción, objetivos, requisitos, instrucciones de instalación y uso, y nombres de los integrantes.

## 4. Estructura de carpetas
La estructura de carpetas sirve para organizar los archivos del proyecto y facilitar su mantenimiento.

Una organización básica puede ser:
Proyecto/
│
├── src/          # Código fuente
├── docs/         # Documentación
├── tests/        # Pruebas del proyecto
├── assets/       # Imágenes y recursos
├── README.md     # Información del proyecto
└── .gitignore    # Archivos que no se deben subir

Importancia: Mantener las carpetas organizadas facilita encontrar archivos, trabajar en equipo y realizar modificaciones al proyecto.

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