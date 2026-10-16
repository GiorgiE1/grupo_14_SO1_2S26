# Diario de trabajo – Grupo 14

**Materia:** Sistemas Operativos 1  
**Fecha de inicio:** 16/10/2026  
**Manual:** Linux From Scratch 13.1-systemd  
**Fuente:** https://www.linuxfromscratch.org/lfs/view/13.1-systemd/

## Registro de actividades

| Fecha | Tarea | Participantes | Decisiones | Problemas | Solución | Resultado | Evidencia |
|---|---|---|---|---|---|---|---|
| 16/10/2026 | Preparación de VM | Jorge Estigarribia | Rocky Linux 9.8, 4 CPU, 12 GB RAM, BIOS y dos discos separados de 50 y 30 GB | Ninguno | No aplica | VM instalada con SSH funcionando | anfitrion.txt |
| 16/10/2026 | Preparación del anfitrión | Jorge Estigarribia | Instalación mínima y herramientas de desarrollo | Editor nano no instalado | Instalación mediante dnf | Entorno de compilación preparado | anfitrion.txt |
| 16/10/2026 | Preparación del disco LFS | Jorge Estigarribia | Segundo disco de 30 GB, MBR, ext4 y montaje en /mnt/lfs | Ninguno | No aplica | Montaje automático verificado | disco-lfs.txt |
| 16/10/2026 | Verificación del anfitrión | Jorge Estigarribia | Manual LFS 13.1-systemd | yacc no reconocido como Bison | Creación del wrapper /usr/bin/yacc | version-check.sh sin errores | version-check.txt |
| 16/10/2026 | Revisión de erratas y seguridad | Jorge Estigarribia | Mantener LFS 13.1-systemd durante todo el TP | Se identificaron avisos de seguridad | Consultar avisos pertinentes durante la construcción | Erratas y avisos revisados | Sitios oficiales de LFS |

## Erratas y avisos de seguridad

- Erratas generales de LFS 13.1-systemd: sin correcciones publicadas al momento de la consulta.
- Avisos de seguridad consultados: sa-13.1-045 (expat), sa-13.1-044 (python) y sa-13.1-046 (openssl).
- Se revisarán los avisos pertinentes antes de instalar los paquetes afectados.

**Fuentes consultadas:**

- https://www.linuxfromscratch.org/lfs/errata/13.1-systemd/
- https://www.linuxfromscratch.org/lfs/
