# Cenotaphio

Archivo de pertenencias y memorias.

## Sitio web

El sitio se publica en GitHub Pages desde [`mixi-app/`](./mixi-app/). El flujo de GitHub Actions lo despliega automáticamente al actualizar la rama `main`.

Después de crear el repositorio, selecciona **Settings → Pages → Build and deployment → Source → GitHub Actions**. La URL del sitio aparecerá en esa misma sección al completarse el primer despliegue.

## Supabase

La aplicación se puede explorar sin iniciar sesión. Para activar cuentas y respaldo, configura `url` y `anonKey` en [`mixi-app/supabase-config.js`](./mixi-app/supabase-config.js) y sigue las instrucciones de [`mixi-app/SUPABASE.md`](./mixi-app/SUPABASE.md). No publiques claves secretas ni `service_role`.
