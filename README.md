# Proyecto de Despliegue de Diana

Este repositorio contiene los archivos necesarios para realizar un despliegue simple en un servidor remoto.

## Contenido del repositorio

- `saludo.txt`: Un archivo de texto con un mensaje de saludo.
- `deploy.sh`: Script para realizar el despliegue del archivo de saludo al servidor.
- `README.md`: Este archivo con instrucciones básicas de uso.

## Requisitos

- Tener Git instalado.
- Tener configurado acceso por SSH al servidor remoto.
- Tener `scp` y `ssh` disponibles (incluidos por defecto en Git Bash o WSL en Windows, o en sistemas Unix).

## Instrucciones

### 1. Clonar el repositorio

```bash
git clone https://github.com/dCarolina12/Despliegue_Electiva3/edit/master/README.md
cd REPO-NOMBRE
VER  CONTENIDO SALUDO
cat saludo.txt

dar permiso al scrip despliegue y ejercutarlo
chmod +x deploy.sh
./deploy.sh
