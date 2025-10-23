# Flujo GitFlow - Vianey

## Diagrama del Flujo GitFlow

## Pasos Realizados

### 1. Estructura Inicial
- git init
- Crear app.txt con versión inicial
- Primer commit en master

### 2. Rama Develop
- git checkout -b develop
### 3. Feature Branches
- feature/login: Funcionalidad de login
- feature/reportes: Sistema de reportes
- feature/info: Información empresarial
- feature/contacto: Datos de contacto

### 4. Release
- git checkout -b release/v1.0
- Preparar versión 1.0 estable

### 5. Merge Final
- release/v1.0 → master
- Etiquetar versión
## Diagrama en Texto
```
master     o---o---o---o (release/v1.0)
           |   |   |   |
develop    o---o---o---o---o---o
           |   |   |   |   |   |
features   o   o   o   o   o   o
          login repo info cont release
```
