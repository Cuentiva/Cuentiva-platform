# 🏢 Cuentiva Platform

<p align="center">
  <img src="assets/logo.png" alt="Cuentiva Logo" width="160"/>
  <br>
  <strong>Plataforma Inteligente de Gestión de Recaudo y Administración Residencial</strong>
  <br>
  <em>Solución integral para urbanizaciones, condominios y conjuntos residenciales.</em>
</p>

<p align="center">
  <a href="https://github.com/Cuentiva/Cuentiva-platform/releases/tag/v1.0.0">
    <img src="https://img.shields.io/badge/Versión-v1.0.0-00C853?style=for-the-badge&logo=github&logoColor=white" alt="Versión v1.0.0" />
  </a>
  <img src="https://img.shields.io/badge/Plataformas-Android%20%7C%20Linux%20%7C%20Windows-007ACC?style=for-the-badge" alt="Plataformas" />
  <img src="https://img.shields.io/badge/Seguridad-TLS%20%2F%20AES-blueviolet?style=for-the-badge" alt="Seguridad" />
</p>

---

## 🌟 Características Principales

* 📶 **Operación Fuera de Línea (Offline-First)**: Registro de cobros y consultas sin depender de conexión permanente a internet, con sincronización automática en la nube al recuperar señal.
* 🖨️ **Impresión Térmica Bluetooth**: Emisión instantánea de comprobantes de pago físicos en impresoras térmicas portátiles (58mm / 80mm) con código QR de verificación.
* 📍 **Rutas Inteligentes de Cobro**: Organización dinámica por etapas, manzanas y viviendas, optimizando los tiempos del cobrador.
* 📅 **Modalidades Flexibles**: Soporte para planes de recaudo semanales, quincenales y mensuales adaptados a la comunidad.
* 🛡️ **Trazabilidad y Seguridad**: Comprobantes firmados criptográficamente para evitar duplicidades y fraudes.

---

## 📦 Descargas Oficiales (v1.0.0)

| Plataforma | Tipo de Paquete | Formato | Tamaño | Enlace de Descarga |
| :--- | :--- | :--- | :--- | :--- |
| **Android** | Teléfonos y Tablets | `.apk` | ~63.3 MB | [📥 Descargar para Android](https://github.com/Cuentiva/Cuentiva-platform/releases/download/v1.0.0/cuentiva-mobile-v1.0.0.apk) |
| **Linux Desktop** | Binario Portable (x64) | `.tar.gz` | ~11.6 MB | [📥 Descargar para Linux](https://github.com/Cuentiva/Cuentiva-platform/releases/download/v1.0.0/cuentiva-desktop-linux-x64-v1.0.0.tar.gz) |
| **Windows Desktop** | Portable / Instalador (x64) | `.exe` / `.zip` | *En preparación* | [💻 Ver detalles de Windows](#-windows-desktop) |
| **Verificación** | Sumas Criptográficas | `.txt` | 200 B | [📄 Ver SHA256SUMS.txt](https://github.com/Cuentiva/Cuentiva-platform/releases/download/v1.0.0/SHA256SUMS.txt) |

---

### 🔒 Sumas de Verificación Criptográfica (SHA-256)

Para validar que los instaladores descargados no han sido alterados:

```bash
sha256sum -c SHA256SUMS.txt
```

**Hashes Oficiales:**
```text
c36089ac0ca5a383ff4bb1ee2f2629b14ddea28a0fb5277e7380e43e8f81e284  cuentiva-mobile-v1.0.0.apk
49430dd1b5576b0a313b9c5f302910c32a2887473f8eb5795d32101590491377  cuentiva-desktop-linux-x64-v1.0.0.tar.gz
```

---

## 🚀 Guías de Instalación y Uso

### 📱 Android (Teléfonos y Tablets)

1. Descargue el instalador `cuentiva-mobile-v1.0.0.apk` en su dispositivo.
2. Abra el archivo desde el gestor de descargas de su navegador o explorador de archivos.
3. Si el sistema muestra una advertencia sobre aplicaciones de fuentes desconocidas, seleccione **Ajustes** y active la opción **Permitir desde esta fuente**.
4. Toque **Instalar** y luego **Abrir** para iniciar la plataforma.

---

### 🐧 Linux Desktop

El paquete para Linux es totalmente autónomo y no requiere instalación ni privilegios de administrador:

```bash
# 1. Descomprimir el archivo descargado
tar -xzf cuentiva-desktop-linux-x64-v1.0.0.tar.gz -C cuentiva/
cd cuentiva

# 2. Ejecutar la aplicación
./civica_pago_mobile
```

**Requisitos mínimos**: Distribución Linux x86_64 con entorno gráfico estándar (librería `libgtk-3`, presente en Ubuntu, Debian, Fedora, Arch, Manjaro, Linux Mint, etc.).

---

### 🪟 Windows Desktop

La versión de escritorio para Windows está diseñada para equipos de administración y cajas de recaudo en oficina. 
* Se distribuye como instalador independiente (`.exe`) que crea accesos directos en el menú de inicio y escritorio.
* Próximamente disponible para descarga directa en esta sección.

---

## 📋 Requisitos de Sistema Recomendados

* **Dispositivos Móviles (Cobradores en Ruta)**:
  * Android 8.0 (Oreo) o superior.
  * Conectividad Bluetooth 4.0+ (para impresoras térmicas portátiles).
  * 2 GB de memoria RAM o superior.
* **Equipos de Escritorio (Administración y Auditoría)**:
  * Procesador x86_64 dual core a 1.5 GHz o superior.
  * 4 GB de memoria RAM.
  * Pantalla con resolución mínima de 1280x720.

---

## 📞 Soporte y Contacto

Para consultas comerciales, soporte de implementación o capacitación para su comunidad residencial:
* **Organización**: Cuentiva Platform
* **Portal Oficial**: [https://github.com/Cuentiva](https://github.com/Cuentiva)

---

<p align="center">
  <strong>Cuentiva Platform — Eficiencia, transparencia y control para su comunidad.</strong><br>
  © 2026 Cuentiva. Todos los derechos reservados.
</p>