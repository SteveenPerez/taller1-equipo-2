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
(pendiente)

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
(pendiente)