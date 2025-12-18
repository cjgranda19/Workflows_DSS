# Workflows_DSS

Sistema automatizado de análisis de seguridad de código mediante GitHub Actions y Machine Learning.

## Descripción

Este repositorio implementa workflows de CI/CD que utilizan un modelo de Machine Learning para detectar vulnerabilidades en código fuente. El sistema analiza automáticamente archivos modificados en Pull Requests y notifica los resultados via Telegram.

## Características

- **Pipeline de Seguridad**: Escaneo automático de código en Pull Requests (.py, .java, .js, .c, .cs)
- **Auto-Merge**: Fusión automática de la rama `dev` a `main` si pasa todas las verificaciones de seguridad
- **Notificaciones Telegram**: Alertas instantáneas sobre el estado de los análisis de seguridad
- **Detección ML**: Clasificación de vulnerabilidades usando modelos entrenados de scikit-learn

## Workflows

### 1. Security Scan on Pull Requests
Analiza archivos modificados en PRs hacia las ramas `dev`, `test` y `main`.

### 2. Auto-Merge Dev to Main
Realiza un escaneo completo de seguridad antes de fusionar cambios de `dev` a `main`.

### 3. Telegram Notifications
Envía notificaciones al grupo de Telegram con los resultados de los análisis.

## Integrantes

- Carlos Granda
- Erick Moreira
- Kevin Coloma