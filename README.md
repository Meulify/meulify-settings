# meulify-settings

Datos de configuración firmados de la app Meulify (un navegador multimedia).
Es una copia de respaldo de los que publica `meulify.top`: la app los usa
cuando su web no responde.

- Solo datos declarativos (JSON). Aquí no hay código, ni contenido
  multimedia, ni claves.
- Cada índice (`v1/manifest.json`) va firmado y cada fichero se nombra por su
  SHA-256. La app rechaza cualquier cosa que no venga firmada por Meulify, así
  que modificar o copiar este repositorio no cambia nada en la app.
- No se edita a mano: lo genera la herramienta de publicación de Meulify.

## Contacto

Para cualquier solicitud sobre derechos o contenidos: reportes@meulify.top

---

Signed configuration data for the Meulify app (a media browser), mirrored
from `meulify.top` as a fallback. Declarative JSON only: no code, no media,
no keys. Every index is signed and every file is named by its SHA-256; the
app ignores anything not signed by Meulify. Rights requests:
reportes@meulify.top
