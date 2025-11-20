# MiAppTS

Una aplicación móvil construida con React Native, Expo y TypeScript.

## Requisitos Previos

Antes de comenzar, asegúrate de tener instalados:

- **Node.js** (versión 18 o superior): [Descargar](https://nodejs.org/)
- **npm** (incluido con Node.js) o **yarn**

## Scripts Disponibles

### Iniciar la aplicación en modo desarrollo

```bash
npx expo start
```

Escanea el código QR con la aplicación Expo Go en tu dispositivo móvil.

### Ejecutar en Android

```bash
npm run android
```

Requiere Android SDK instalado y configurado.

### Ejecutar en iOS

```bash
npm run ios
```

Solo disponible en macOS. Requiere Xcode instalado.

### Ejecutar en Web

```bash
npm run web
```

## Estructura del Proyecto

```
MiAppTS/
├── App.tsx          # Componente principal de la aplicación
├── index.ts         # Punto de entrada de la aplicación
├── app.json         # Configuración de Expo
├── tsconfig.json    # Configuración de TypeScript
├── package.json     # Dependencias y scripts
├── .gitignore       # Archivos ignorados por Git
└── assets/          # Recursos de la aplicación (imágenes, etc.)
```

## Tecnologías Utilizadas

- **React Native** (v0.81.5)
- **Expo** (v54.0.25)
- **TypeScript** (v5.9.2)
- **React** (v19.1.0)

## Desarrollo

Este proyecto está configurado con TypeScript en modo estricto (`"strict": true`), lo que proporciona una mejor seguridad de tipos durante el desarrollo.

## Notas Importantes

- La aplicación está optimizada para ejecutarse en Expo Go
- Se soporta la nueva arquitectura de React Native (`newArchEnabled: true`)
- En Android, está habilitado el modo edge-to-edge

## Troubleshooting

Si tienes problemas de conexión con Expo:

1. Asegúrate de que tu dispositivo y computadora están en la misma red
2. Reinicia el servidor: `npm start` y presiona `r`
3. Limpia la caché: `npm start -- --clear`
