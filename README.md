# CONSOLA-UPDATE-BYPASS

## 🟣 GUATE XITER BYPASS - Sistema de Auto-Actualización

Este repositorio contiene el sistema de actualización automática para **GUATE XITER BYPASS**.

### 📋 Cómo funciona

1. El archivo `version.txt` contiene la versión más reciente
2. Cuando un usuario abre el EXE, este verifica `version.txt`
3. Si hay una versión más nueva, descarga el EXE de los **Releases**
4. Se actualiza automáticamente sin que el usuario haga nada

### 🔄 Cómo actualizar

1. Cambia `APP_VERSION` en `auto_updater.h`
2. Compila el nuevo EXE
3. Actualiza `version.txt` con el nuevo número de versión
4. Crea un nuevo Release en GitHub y sube el EXE

### 📁 Archivos

- `version.txt` — Número de versión actual (los clientes lo verifican)
- `Releases` — EXE compilado más reciente

### 👤 Developer: </>YUVE
