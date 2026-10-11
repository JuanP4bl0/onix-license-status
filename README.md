# Estado de licencias de Onix
Este repositorio público contiene únicamente identificadores SHA-256 de claves aleatorias y fechas de vencimiento. No contiene código de Onix, claves legibles ni nombres de personas.
El archivo `licenses.txt` empieza con `ONIX-LICENSES-1`. Cada línea siguiente usa `SHA256_HEX,UNIX_EXPIRY_UTC`. La fecha `0` significa sin vencimiento. Eliminar una línea revoca esa clave; cambiar su fecha modifica el vencimiento.
Las claves deben generarse con 160 bits aleatorios. Una clave corta o elegida manualmente puede recuperarse a partir de su hash público. Solo el propietario debe editar `licenses.txt`.
