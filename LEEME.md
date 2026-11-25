# Flyer Onda Uno – versión web (celular)

## 1) Subir a GitHub (una sola vez)
1. Creá una cuenta gratis en https://github.com
2. Botón "New repository" → nombre: flyer-onda-uno → Create repository.
3. Click en "uploading an existing file" y arrastrá TODOS los archivos de esta carpeta
   (app.py, requirements.txt, Procfile, render.yaml, .gitignore) → "Commit changes".

## 2) Publicar en Render (gratis)
1. Creá una cuenta en https://render.com (podés entrar con GitHub).
2. New + → Web Service → elegí tu repositorio flyer-onda-uno.
3. Plan: Free. Render detecta solo la configuración. → Create Web Service.
4. En 3-5 minutos te da un link tipo https://flyer-onda-uno.onrender.com

## 3) (Recomendado) Ponerle contraseña
Como el link es público, cualquiera podría usarlo. En Render:
Environment → Add Environment Variable → ACCESS_CODE = la clave que quieras.
La app te pedirá esa clave al generar cada flyer.

## 4) Instalar en el celular
Abrí el link en Chrome (Android) → menú ⋮ → "Instalar aplicación" / "Agregar a pantalla principal".
Queda con el ícono de Onda Uno, como una app.

## Notas
- Plan gratis: si nadie la usa por ~15 min se "duerme"; la primera vez tarda ~30-50 s en despertar.
- Algunos diarios bloquean pedidos desde servidores en la nube. Si pasa, usá "Opciones" para
  escribir el título a mano o probá otra nota.
- "Compartir / Guardar" abre el menú del celular para mandar el flyer directo a Instagram o a la galería.
- Para tener una APK real: entrá a https://www.pwabuilder.com, pegá tu link y descargá el paquete Android.
