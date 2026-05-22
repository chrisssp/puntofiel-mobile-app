# PuntoFiel — Plataforma de Fidelización Basada en Roles

<p align="center">
  <img src="https://img.shields.io/badge/React_Native-20232A?logo=react&logoColor=61DAFB" alt="React Native">
  <img src="https://img.shields.io/badge/Expo-000020?logo=expo&logoColor=white" alt="Expo">
  <img src="https://img.shields.io/badge/Supabase-3ECF8E?logo=supabase&logoColor=white" alt="Supabase">
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white" alt="PostgreSQL">
  <img src="https://img.shields.io/badge/gluestack--ui-00A3FF?logo=styled-components&logoColor=white" alt="gluestack-ui">
  <img src="https://img.shields.io/badge/TanStack_Query-FF4154?logo=react-query&logoColor=white" alt="TanStack Query">
  <img src="https://img.shields.io/badge/License-GPL_v3-0298c3?logo=gnu&logoColor=white" alt="GPL v3">
</p>

<p align="center">
  <em>Plataforma de fidelización para negocios locales con autenticación por roles y sistema de puntos vía QR</em>
</p>

<p align="center">
  <a href="README.md">🇬🇧 English</a> · <a href="README.es.md">🇪🇸 Español</a>
</p>

---

## Acerca de PuntoFiel

Una aplicación móvil de fidelización basada en roles para negocios locales. Los clientes ganan y canjean recompensas con códigos QR, mientras que los dueños administran personal, catálogo, promociones y auditan actividad. Diseñada para equilibrar el compromiso del cliente con el control administrativo, haciendo que la fidelización sea simple para los usuarios y útil para los negocios.

## Funcionalidades

- Registro y autenticación para clientes y dueños de negocios
- Generación y escaneo de códigos QR para acumulación de puntos
- Sistema de recompensas gestionado por cada negocio
- Panel de control para que los negocios vean sus clientes más leales
- Roles: clientes, empleados y dueños con diferentes permisos
- Seguridad con RLS (Row Level Security) de PostgreSQL

## Stack Tecnológico

| Capa | Tecnología |
|------|-----------|
| Framework | React Native + Expo |
| Lenguaje | TypeScript |
| UI | gluestack-ui + NativeWind |
| Estado | TanStack Query + Zustand |
| Backend | Supabase (Auth, PostgreSQL, RLS) |
| Linter | Biome |

## Inicio rápido

```bash
git clone https://github.com/chrisssp/puntofiel-mobile-app.git
cd puntofiel-mobile-app
pnpm install
cp .env.example .env
pnpm start
```

## Licencia

GPL v3 — ver [LICENSE](LICENSE) para más detalles.

## Agradecimientos

**Autores:**

- [@chrisssp](https://github.com/chrisssp) — Christian Serrano
