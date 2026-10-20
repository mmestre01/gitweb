# GitWeb

Aplicación educativa que implementa una interfaz web para repositorios, ramas, commits y archivos. Incluye una API Flask con SQLite y un cliente React.

## Desarrollo

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
python main.py
```

En otra terminal:

```bash
cd gitweb-frontend
npm ci
npm start
```

Copia `.env.example` a `.env` para personalizar la base de datos, los orígenes CORS y la URL de la API. Los usuarios y bases locales quedan excluidos de Git.

## Estructura

- `app/routes`: endpoints de usuarios, repositorios, ramas, commits y archivos.
- `app/database.py`: esquema y acceso SQLite.
- `gitweb-frontend`: interfaz React.

Este proyecto es una implementación didáctica y no sustituye un servidor Git de producción.

