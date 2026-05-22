# PuntoFiel — Role-Based Loyalty Platform for Local Businesses

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
  <em>Customers earn and redeem rewards with QR, while owners manage staff, catalog, promotions, and audit activity with clarity.</em>
</p>

<p align="center">
  <a href="README.md">🇬🇧 English</a> · <a href="README.es.md">🇪🇸 Español</a>
</p>

---

## About

A role-based loyalty mobile app for local businesses. Customers earn and redeem rewards with QR codes, while owners manage staff, products, rewards, raffles, and promotions. It balances customer engagement with day-to-day administrative control, making loyalty simple for users and useful for businesses.

## Features

- Registration and authentication for customers and business owners
- QR code generation and scanning for contactless point accumulation
- Reward system managed by each business
- Owner dashboard with customer loyalty insights
- Role-based access: customers, employees, and owners
- Data security with PostgreSQL Row Level Security (RLS)

## Tech Stack

| Layer | Technology |
|-------|-----------|
| Framework | React Native + Expo |
| Language | TypeScript |
| UI | gluestack-ui + NativeWind |
| State | TanStack Query + Zustand |
| Backend | Supabase (Auth, PostgreSQL, RLS) |
| Architecture | Clean Architecture |
| Linter | Biome |

## Quick Start

```bash
git clone https://github.com/chrisssp/puntofiel-mobile-app.git
cd puntofiel-mobile-app
pnpm install
cp .env.example .env
pnpm start
```

## License

GPL v3 — see [LICENSE](LICENSE) for details.

## Acknowledgments

**Authors:**

- [@chrisssp](https://github.com/chrisssp) — Christian Serrano
