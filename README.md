# Mi primera aplicación web con Django

Aplicación web básica con tres páginas: inicio, login y panel.

## Requisitos
- Python 3 instalado.

## Instalación en Windows (PowerShell)

1. Crear y activar el entorno virtual:

```powershell
python -m venv venv
.\venv\Scripts\Activate.ps1
```

2. Instalar dependencias:

```powershell
pip install -r requirements.txt
```

3. Ejecutar migraciones (opcional para estas páginas, recomendado):

```powershell
python manage.py migrate
```

4. Iniciar el servidor:

```powershell
python manage.py runserver
```

Abrir http://127.0.0.1:8000/

## Rutas
- `/` Página principal
- `/login/` Inicio de sesión (formulario demostrativo)
- `/panel/` Panel con datos enviados desde la vista

## Nota
El formulario de login es únicamente visual/demostrativo; todavía no autentica usuarios.
