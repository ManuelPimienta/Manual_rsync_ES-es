## Resumen de opciones

Comando | salida |
--- | ---
-v, --verbose | aumentar verbosidad |
-q, --quiet | suprime mensajes que no son de error |
--no-motd | suprime daemon-mode MOTD (ver advertencia) |
-c, --checksum | saltar metodo basado en suma de verificación, no mod-time & size 
-a, --archive | modo de archivo; es igual a -rlptgoD (no -H, -A, -X)
--no-OPTION | desactiva una OPCIÓN implícita (por ejemplo, --no-D)
-r, --recursive | recorre recursivamente los directorios
-R, --relative | usar nombres de ruta relativos
--no-implied-dirs | no envía dirs implicados con --relative
-b, --backup | hacer copias de seguridad (ver --suffix & --backup-dir)
--backup-dir=DIR | hace respaldos en la jerarquía basada en DIR
--suffix=SUFFIX | sufijo de copia de seguridad (predeterminado ~ w / o --backup-dir)
