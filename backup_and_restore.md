## Respaldo de Configuraciones

### Script de Respaldo
- El script realiza una copia de seguridad del directorio /etc/ a /backup/etc_config/ usando rsync.

### Automatización con Cron
- Ejecutar el respaldo diariamente a las 2:00 AM con el comando:

0 2 * * * /usr/local/bin/backup_script.sh


### Verificación
- Para verificar manualmente:
ls -l /backup/etc_config/
