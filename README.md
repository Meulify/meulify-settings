# meulify-settings

Datos de configuración firmados de la app Meulify (un navegador multimedia).
Es una copia de respaldo de los que publica `meulify.top`: la app los usa
cuando su web no responde.

- Solo datos declarativos (JSON). Aquí no hay código ni claves.
- `MAI/audios/` es la copia de respaldo de las locuciones de MAI
  (`meulify.top/api/MAI/audios/`), con las mismas rutas.
- Cada índice (`v1/manifest.json`) va firmado y cada fichero se nombra por su
  SHA-256. La app rechaza cualquier cosa que no venga firmada por Meulify, así
  que modificar o copiar este repositorio no cambia nada en la app.
- `v1/` no se edita a mano: lo genera la herramienta de publicación de Meulify.

## Contacto

Para cualquier solicitud sobre derechos o contenidos: reportes@meulify.top

---

Signed configuration data for the Meulify app (a media browser), mirrored
from `meulify.top` as a fallback. Declarative JSON only: no code, no keys.
`MAI/audios/` is a fallback copy of the MAI voice clips, same paths as on
`meulify.top/api/MAI/audios/`. Every index is signed and every file is named by its SHA-256; the
app ignores anything not signed by Meulify. Rights requests:
reportes@meulify.top
