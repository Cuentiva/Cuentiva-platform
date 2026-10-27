# 🏢 Cuentiva Platform

<p align="center">
  <img src="assets/logo.png" alt="Cuentiva Logo" width="140"/>
  <br>
  <img src="assets/nombre1.png" alt="Cuentiva" width="220"/>
  <br><br>
  <strong>Plataforma Inteligente de Gestión de Recaudo y Administración Residencial</strong>
  <br>
  <em>Solución integral para urbanizaciones, condominios y conjuntos residenciales.</em>
</p>

<p align="center">
  <a href="https://github.com/Cuentiva/Cuentiva-platform/releases/tag/v0.3.1">
    <img src="https://img.shields.io/badge/Versión-v0.3.1-00C853?style=for-the-badge&logo=github&logoColor=white" alt="Versión v1.0.0" />
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

## 📦 Descargas Oficiales (Versión Oficial v0.3.1)

| Plataforma | Versión | Fecha | Formato | Tamaño | Enlace de Descarga |
| :--- | :---: | :---: | :---: | :---: | :--- |
| 📱 **Android** | `v0.3.1` | 27/Oct/2026 | `.apk` | ~67 MB | [📥 **cuentiva-mobile-v0.3.1.apk**](https://github.com/Cuentiva/Cuentiva-platform/releases/download/v0.3.1/cuentiva-mobile-v0.3.1.apk) |
| 🐧 **Linux Desktop** | `v0.3.1` | 27/Oct/2026 | `.tar.gz` (x64) | ~15 MB | [📥 **cuentiva-desktop-linux-x64-v0.3.1.tar.gz**](https://github.com/Cuentiva/Cuentiva-platform/releases/download/v0.3.1/cuentiva-desktop-linux-x64-v0.3.1.tar.gz) |
| 🪟 **Windows Desktop** | `v0.3.1` | 27/Oct/2026 | `.zip` (x64) | ~16 MB | [📥 **cuentiva-desktop-windows-x64-v0.3.1.zip**](https://github.com/Cuentiva/Cuentiva-platform/releases/download/v0.3.1/cuentiva-desktop-windows-x64-v0.3.1.zip) |
| 🌐 **Aplicación Web** | `v0.3.1` | 27/Oct/2026 | `PWA / Web` | En línea | [🚀 **Abrir Cuentiva Web (PWA)**](https://cuentiva.github.io/Cuentiva-platform/) |
| 📄 **Verificación** | `v0.3.1` | 27/Oct/2026 | `.txt` | 306 B | [📄 **SHA256SUMS.txt**](https://github.com/Cuentiva/Cuentiva-platform/releases/download/v0.3.1/SHA256SUMS.txt) |

---

### 🔒 Sumas de Verificación Criptográfica (SHA-256)

Para validar que los instaladores descargados no han sido alterados:

```bash
sha256sum -c SHA256SUMS.txt
```

**Hashes Oficiales:**
```text
aca88e7fd0ffcda98f5bb35d0d4d14d429ce11b98f251cf0527308a199cbfefe  cuentiva-desktop-linux-x64-v0.3.1.tar.gz
159e3e259cc7c2338ff1d1f91e0d2507ed7f62759afab669ebd157fd46efc3b9  cuentiva-desktop-windows-x64-v0.3.1.zip
f829a375e760909a3794463c709b7584683af5862e1099d375158382921dd7ee  cuentiva-mobile-v0.3.1.apk
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

### 🪟 Windows Desktop (Windows 10 / 11 de 64 bits)

La versión de escritorio para Windows está diseñada para administradores, contadores y cajas de recaudo en oficina:

1. Descargue el archivo **`cuentiva-desktop-windows-x64-v1.0.0.zip`**.
2. Haga clic derecho sobre el archivo descargado y seleccione **Extraer todo...**.
3. Abra la carpeta extraída y haga doble clic en **`civica_pago_mobile.exe`**.
4. ¡Listo! La aplicación se iniciará al instante conectada a la nube.

> *Nota: Es una aplicación totalmente portable; no requiere permisos de administrador ni instalación invasiva en el sistema.*

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
