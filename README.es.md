# PuntoFiel — Plataforma de Fidelización Basada en Roles para Negocios Locales

<p align="center">
  <img src="assets/logos/logo-variante-horizontal-ligth.png" alt="PuntoFiel Logo" width="150"/>
</p>

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
  <em>Los clientes ganan y canjean recompensas con QR, mientras los dueños administran personal, catálogo, promociones y auditan actividad con claridad.</em>
</p>

<p align="center">
  <a href="README.md">🇬🇧 English</a> · <a href="README.es.md">🇪🇸 Español</a>
</p>

---

## Acerca de

Aplicación móvil de fidelización basada en roles para negocios locales. Los clientes ganan y canjean recompensas con códigos QR, mientras que los dueños administran personal, productos, recompensas, rifas y promociones. Diseñada para equilibrar el compromiso del cliente con el control administrativo diario.

## Funcionalidades

- Registro y autenticación para clientes y dueños de negocios
- Generación y escaneo de códigos QR para acumulación de puntos sin contacto
- Sistema de recompensas gestionado por cada negocio
- Panel de control para dueños con información de clientes leales
- Acceso basado en roles: clientes, empleados y dueños
- Seguridad de datos con PostgreSQL Row Level Security (RLS)

## Stack Tecnológico

| Capa | Tecnología |
|------|-----------|
| Framework | React Native + Expo |
| Lenguaje | TypeScript |
| UI | gluestack-ui + NativeWind |
| Estado | TanStack Query + Zustand |
| Backend | Supabase (Auth, PostgreSQL, RLS) |
| Arquitectura | Clean Architecture |
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
