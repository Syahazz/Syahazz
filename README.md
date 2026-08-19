<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=180&section=header&text=Hey,%20I'm%20Syahrul!%20👋&fontSize=42&fontColor=fff&animation=twinkling&fontAlignY=32&desc=Flutter%20by%20day%20·%20Velrox%20by%20night&descAlignY=55&descSize=18" width="100%"/>

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=A855F7&center=true&vCenter=true&random=false&width=620&lines=Flutter+Developer+%F0%9F%92%99;Full-stack+TypeScript+%E2%9A%99%EF%B8%8F;Solo+Founder+%40+Velrox+%E2%98%81%EF%B8%8F;Math+grad+turned+builder+%F0%9F%A7%AE;Jakarta-based+%F0%9F%87%AE%F0%9F%87%A9" alt="Typing SVG" />
</a>

<br/>

![Profile Views](https://komarev.com/ghpvc/?username=Syahazz&color=blueviolet&style=for-the-badge&label=PROFILE+VIEWS)
[![GitHub followers](https://img.shields.io/github/followers/Syahazz?style=for-the-badge&color=purple&labelColor=1a1a2e)](https://github.com/Syahazz)

</div>

---

## About me

```dart
class Syahrul extends Developer {
  final String name     = "Mochammad Syahrul Azhar";
  final String alias    = "Syahazz";
  final String location = "Jakarta, Indonesia 🇮🇩";
  final String dayJob   = "IT & Flutter @ PT Massindo International";
  final String nightJob = "Solo founder @ Velrox (velrox.cloud)";

  final List<String> funFacts = [
    "Math grad who fell into code and stayed",
    "Ships Flutter apps at Massindo, product at Velrox after hours",
    "Powered by coffee and curiosity",
    "Yes, I name my bugs before fixing them",
  ];

  String get currentlyBuilding => "Wilayah ID + Velrox ERP";
  bool   get openToCollaborate => true;
}
```

---

## Tech stack

<div align="center">

**Mobile**

![Flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white)
![Riverpod](https://img.shields.io/badge/Riverpod-00BCD4?style=for-the-badge&logo=dart&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)

**Web & API**

![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Hono](https://img.shields.io/badge/Hono-E36002?style=for-the-badge&logo=hono&logoColor=white)
![Bun](https://img.shields.io/badge/Bun-000000?style=for-the-badge&logo=bun&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)

**Data & infra**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![Drizzle](https://img.shields.io/badge/Drizzle-C5F74F?style=for-the-badge&logo=drizzle&logoColor=black)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Rails](https://img.shields.io/badge/Rails-CC0000?style=for-the-badge&logo=rubyonrails&logoColor=white)

**Tools**

![Cursor](https://img.shields.io/badge/Cursor-000000?style=for-the-badge&logo=cursor&logoColor=white)
![macOS](https://img.shields.io/badge/macOS-000000?style=for-the-badge&logo=apple&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)

</div>

Rails shows up where an existing API already lives (Alita). New Velrox products are TypeScript: Next.js, Hono, Bun, PostgreSQL.

---

## Featured

### [Velrox](https://velrox.cloud) — product platform, self-hosted

Brand home at **velrox.cloud**. Apps sit on subdomains, running on a VPS with Docker + Caddy — not a generic “AI hosting” product.

| Surface | What it is |
| --- | --- |
| [velrox.cloud](https://velrox.cloud) | Brand landing + careers board (Next.js) |
| [erp.velrox.cloud](https://erp.velrox.cloud) | Multi-tenant ERP for Indonesia: finance, HR/payroll (PPh 21, BPJS), inventory |
| [wealth.velrox.cloud](https://wealth.velrox.cloud) | Wealth Checker web app |

**ERP stack:** Next.js · Hono · PostgreSQL · Drizzle · Redis · Better Auth · Docker

---

### Wilayah ID — Indonesian regions + postal codes

Portfolio API and playground: **provinsi → kabupaten/kota → kecamatan → desa/kelurahan → kode pos**.

- 38 provinces, 514 kab/kota, 7.285 districts, 83.762 villages, 83.762 postal codes
- Cascade form, search, reverse postal lookup, Leaflet map
- Data from [cahyadsn/wilayah](https://github.com/cahyadsn/wilayah) + [cahyadsn/wilayah_kodepos](https://github.com/cahyadsn/wilayah_kodepos) (MIT), Kepmendagri 2025 — not a scrape of a commercial maps API

Endpoints: `/api/provinsi`, `/api/kabupaten`, `/api/kecamatan`, `/api/desa`, `/api/wilayah/{kode}`, `/api/kodepos/{kodepos}`, `/api/cari`

---

## Projects

| Project | Description | Stack |
| --- | --- | --- |
| [**Velrox ERP**](https://erp.velrox.cloud) | Self-hosted multi-tenant ERP (PSAK, PPh 21 TER, BPJS). Core, Auth, Finance, HR, Inventory, System are live; Sales / Procurement / Manufacturing still scaffold. | `Next.js` `Hono` `PostgreSQL` |
| [**Velrox Landing**](https://velrox.cloud) | Brand homepage; careers proxied to the ERP public API | `Next.js` `Tailwind` |
| **Wilayah ID** | Regions + postal-code API and playground (portfolio) | `Next.js` `TypeScript` |
| [**Wealth Checker**](https://github.com/Syahazz/wealth-checker) | Personal finance tracker with freedom levels 0–6. Live at [wealth.velrox.cloud](https://wealth.velrox.cloud) | `Next.js` `Hono` `PostgreSQL` |
| [**Wealth Checker Mobile**](https://github.com/Syahazz/wealth-checker-mobile) | Flutter companion for the same product | `Flutter` `Riverpod` |
| [**Alita Pricelist**](https://github.com/Syahazz/alita) | Field sales app: dynamic pricelist, cart, checkout, PDF quotes, order approvals | `Flutter` `Riverpod` `Firebase` |
| **Sleep Center** | Flutter store app for Massindo’s mattress brand | `Flutter` `Firebase` |
| [**Pengumuman TKA**](https://pengumuman-tka.vercel.app) | Public TKA announcement site | `React` `Vite` |
| **Nocta Spine** | On-device pose-detection MVP for a mattress showroom | `ML` `Browser` |

---

## Stats

<div align="center">
  <img height="165" alt="GitHub stats" src="https://github-readme-stats.vercel.app/api?username=Syahazz&show_icons=true&theme=tokyonight&hide_border=true" />
  <img height="165" alt="Top languages" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Syahazz&layout=compact&theme=tokyonight&hide_border=true&langs_count=6" />
</div>

---

## Currently

- **Building** → Wilayah ID (API + playground) and Velrox ERP modules
- **Shipping at work** → Flutter apps for Massindo Group (Alita Pricelist, Sleep Center)
- **Running** → self-hosted stack on the Velrox VPS (landing, ERP, Wealth Checker)
- **Recharging** → mobile games & gacha (don’t judge)

---

## Connect

<div align="center">

[![Website](https://img.shields.io/badge/velrox.cloud-7C3AED?style=for-the-badge&logo=vercel&logoColor=white)](https://velrox.cloud)
[![GitHub](https://img.shields.io/badge/GitHub-Syahazz-181717?style=for-the-badge&logo=github)](https://github.com/Syahazz)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:syahrul@velrox.cloud)

</div>

---

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Syahazz/Syahazz/output/github-contribution-grid-snake-dark.svg?v=1" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Syahazz/Syahazz/output/github-contribution-grid-snake.svg?v=1" />
  <img alt="github-snake" src="https://raw.githubusercontent.com/Syahazz/Syahazz/output/github-contribution-grid-snake.svg?v=1" />
</picture>

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=100&section=footer" width="100%"/>

</div>
