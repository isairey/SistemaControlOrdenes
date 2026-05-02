# 🛠️ MAPOS — Sistema de Gestión

![MapOS](https://raw.githubusercontent.com/RamonSilva20/mapos/master/assets/img/logo.png)

[![Versión](https://img.shields.io/badge/version-4.53.2-blue?style=for-the-badge)]()
[![Licencia](https://img.shields.io/badge/license-Apache-green?style=for-the-badge)]()
[![Issues](https://img.shields.io/github/issues/RamonSilva20/mapos?style=for-the-badge)]()
[![Contribuidores](https://img.shields.io/github/contributors/RamonSilva20/mapos?style=for-the-badge)]()

---

## 🚀 Descripción

**MAPOS** es un sistema de gestión completo (ERP ligero) diseñado para empresas que necesitan administrar:

- 📦 Órdenes de servicio  
- 👥 Clientes  
- 🧾 Facturación  
- 📊 Reportes  
- 💼 Procesos administrativos  

Cuenta con una interfaz moderna, escalable y fácil de usar.

---

## 🌐 Vista previa

![Dashboard](https://raw.githubusercontent.com/RamonSilva20/mapos/master/docs/dashboard.png)

---





## ⚙️ Requisitos

- PHP >= 8.4  
- MySQL >= 5.7 / 8.0  
- Composer >= 2  

---

## 📦 Instalación (Manual)

1. Clonar repositorio:
```bash
git clone https://github.com/isairey/SistemaControlOrdenes
.git
```
Copiar a tu servidor (XAMPP / Apache)
Instalar dependencias:
```
composer install --no-dev
```
Abrir en navegador:
```
http://localhost/mapos
```
Completar asistente de instalación

---

## 🐳 Instalación con Docker
```
cd docker
docker-compose up --force-recreate
```
Acceder:
```
App → http://localhost:8000
PhpMyAdmin → http://localhost:8080
Configuración:
Host: mysql
Usuario: mapos
Contraseña: mapos
Base de datos: mapos
```
---

## ⚡ Instalación automática

```Windows
PowerShell -command "& { iwr https://raw.githubusercontent.com/RamonSilva20/mapos/master/install.bat -OutFile MapOS_Install.bat }; .\MapOS_Install.bat"
Linux
curl -o MapOS_Install.sh -L https://raw.githubusercontent.com/RamonSilva20/mapos/master/install.sh && chmod +x MapOS_Install.sh && ./MapOS_Install.sh
```
---

## 🔄 Actualización

- Hacer backup del sistema
- Reemplazar archivos
- Ejecutar:
- composer install --no-dev
- Actualizar base de datos desde el sistema

---

## 🧠 Funcionalidades

- Gestión de clientes
- Control de órdenes
- Facturación
- Reportes
- Sistema de usuarios
- Envío de correos
- Backup integrado

---

## 🧪 Comandos útiles
```
php index.php tools
```
### 🧱 Tecnologías

- PHP (CodeIgniter)
- MySQL
- Bootstrap
- jQuery

---

## 🤝 Contribuir

- Fork del repositorio
- Crear rama
- Commit
- Pull Request
- ⭐ Estadísticas

---


## 👨‍💻 Autor
<img src="https://avatars.githubusercontent.com/isairey?s=115"><br><sub>Isai Reyes</sub>

---

## 📄 Licencia

Apache License
