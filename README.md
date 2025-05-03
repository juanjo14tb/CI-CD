# Proyecto CI/CD con GitHub Actions

Este proyecto configura un flujo de trabajo de CI/CD utilizando **GitHub Actions** para desplegar una aplicación de manera automática en un servidor Ubuntu mediante una conexión SSH segura.

## Requisitos

- **Ubuntu Server** configurado con acceso SSH.
- **Node.js** y **npm** instalados en el servidor.
- **GitHub repository** con acceso a GitHub Actions.
- **Llaves SSH** configuradas en GitHub para la conexión al servidor.

## Tecnologías

- **GitHub Actions** para CI/CD.
- **Node.js** y **npm** para la gestión de la aplicación.
- **PM2** para la gestión de la aplicación en el servidor.
- **SSH** para la conexión remota.

## Instalación

### 1. Clonar el repositorio

Clona el repositorio a tu máquina local:

```bash
git clone https://github.com/tu_usuario/ci-cd.git
cd ci-cd
