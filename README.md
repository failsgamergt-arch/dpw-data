# DJ Pool World - datos

- `pools.json`: catalogo publico (dias, artistas y nombres de los packs). **No lleva enlaces.**
- `pools.enc`: los datos completos con los enlaces de descarga, cifrados. Solo pueden abrirlos los administradores y los suscriptores.
- `keys.json`: quien puede abrir `pools.enc` (cada acceso va cifrado; no contiene nombres ni emails en claro).
- `access.json`: cuentas de administrador (cifradas).

No editar a mano: se cambia desde el panel admin (admin.html) o con `node tools/pools-cli.js` del repo principal, que validan y cifran todo antes de guardar.
