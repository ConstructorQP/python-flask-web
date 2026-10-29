# Python y Flask: de los fundamentos a webs dinámicas

Recorrido práctico por Python aplicado al desarrollo web: desde los primeros scripts hasta aplicaciones Flask que leen datos de JSON y SQLite y los muestran con plantillas.

Ejercicios del ciclo de ASIR, organizados por temas en orden de dificultad.

## Contenido

| Carpeta | Qué se trabaja |
|---|---|
| `PYTHON/` | Fundamentos: entradas y salidas, operadores, condicionales, bucles, funciones y ejercicios aplicados (calculadoras, estadísticas, planes semanales…) |
| `002-Seleccion y acceso a elementos/FLASK/` | Primeras apps Flask: rutas, varias páginas y paso de datos a plantillas |
| `003-Creacion y modificacion de elementos/` | Webs dinámicas con Jinja2: variables y bucles en plantillas, mini-blog |
| `004-Definición de esquemas/` | Formatos de datos: XML (nodos, anidación) y JSON (lectura desde Python y servidor web con plantillas) |
| `004-Eliminacion de elementos/` | Conexión a SQLite: crear tabla, insertar y leer registros |
| `005-Manipulación de estilos/` | Blog con Flask, SQLite y CSS |
| `006-Ejercicio portafolio/` | Portafolio personal servido con Flask a partir de una base de datos |
| `007-Blog personal/` | Proyecto de blog completo: script SQL, controlador Flask y plantilla HTML/CSS |

## Tecnologías

Python 3 · Flask · Jinja2 · SQLite · JSON · XML · HTML · CSS

## Cómo ejecutar los ejercicios

```bash
git clone https://github.com/ConstructorQP/python-flask-web
cd python-flask-web
pip install flask
```

- Scripts de consola: `python "PYTHON/001-Ejercicios/020-calculadora factura con funciones.py"`
- Apps Flask: entra en su carpeta y ejecuta el `.py`, por ejemplo:

```bash
cd "006-Ejercicio portafolio"
python "003-Mi portafolio.py"
```

Después abre `http://127.0.0.1:5000` en el navegador.

## Proyecto destacado

El blog completo con panel de administración está en su propio repositorio: [flask-blog-admin](https://github.com/ConstructorQP/flask-blog-admin).
