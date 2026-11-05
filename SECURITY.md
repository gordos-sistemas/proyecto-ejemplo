
# Política de seguridad — Gordos Sistemas

La seguridad de nuestros proyectos y de sus usuarios
es una responsabilidad compartida.

## Reportar vulnerabilidades

Si encontrás una vulnerabilidad de seguridad:

1. No publiques detalles técnicos explotables en Issues,
   Discussions, Pull Requests ni canales públicos.
2. No intentes acceder a datos o sistemas sin autorización.
3. Utilizá GitHub Private Vulnerability Reporting
   cuando esté habilitado en el repositorio.
4. Si no está habilitado, contactá de forma privada
   a los maintainers para acordar un canal seguro.

Incluí, cuando sea posible:

- Descripción del problema.
- Componentes y versiones afectados.
- Pasos mínimos para reproducirlo de forma segura.
- Impacto potencial.
- Recomendaciones de mitigación.

No compartas credenciales reales ni datos personales
en los reportes.

## Credenciales y secretos

Está prohibido incorporar al repositorio:

- Tokens de API.
- Contraseñas.
- Claves SSH privadas.
- Credenciales de bases de datos.
- Archivos .env con secretos reales.
- Certificados y claves privadas.
- Backups con información sensible.

Utilizá variables de entorno y gestores de secretos.

Los archivos de ejemplo, como .env.example,
deben contener exclusivamente valores ficticios.

## Si se expone un secreto

1. Avisá inmediatamente a los responsables.
2. Revocá o rotá la credencial comprometida.
3. Revisá el alcance de la exposición.
4. Eliminá el secreto del código y evaluá
   la limpieza del historial de Git.
5. Documentá el incidente por un canal privado.

Eliminar un commit no garantiza que el secreto
deje de estar expuesto.

## Revisión de seguridad

Los proyectos deben incorporar progresivamente:

- Revisión humana de Pull Requests.
- Escaneo de secretos.
- Análisis de dependencias.
- CI automatizado.
- Permisos mínimos para GitHub Actions.
- Protección de ramas principales.

## Divulgación responsable

Los detalles de vulnerabilidades no corregidas
deben tratarse mediante canales privados.

La publicación de avisos de seguridad se coordinará
con los maintainers responsables del proyecto.
