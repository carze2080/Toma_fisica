# Toma Física de Inventario

App web de toma física de inventario (Firebase + GitHub Pages).

- `index.html`: la app completa.
- `firestore.rules`: reglas de seguridad de Firestore (publicarlas en Firebase Console → Firestore → Reglas).

Novedades: tomas múltiples con comparación entre ellas, y empresas separadas con estado de suscripción.
Para activar el panel de empresas, agrega el campo `superadmin` = `true` (booleano) en tu documento de la colección `usuarios`.
