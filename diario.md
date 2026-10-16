# diario.md

| Fecha | Tarea | Participantes | Decisiones | Problemas | Solución | Resultado | Evidencia |
| --- | --- | --- | --- | --- | --- | --- | --- |
| 2026-10-14 | Preparación de VM, disco de LFS y verificación del anfitrión | <Cecilia Basualdo> | Segundo disco de 30 GB (sdb) en SATA dedicado a LFS; libro LFS 13.1-systemd | Disco de LFS quedó en IDE; ERROR: yacc is NOT Bison | Se movió al controlador SATA; se creó /usr/bin/yacc con bison -y | OK: version-check.sh sin errores | evidencias/parte1/ |
