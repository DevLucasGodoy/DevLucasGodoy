# Olá, eu sou o Lucas Godoy 👋

**Desenvolvedor Sênior · CEO & Fundador da [First Class Dev](https://www.firstclassdev.com.br) · Sócio & Head de Tecnologia na TG Distribuidora**

Construo software que roda em produção e resolve problema de negócio: sites, sistemas sob medida, integrações com ERP e plataformas SaaS próprias. Moro em Dourados, MS, e atendo clientes no Brasil, nos EUA e na Argentina.

🌐 [Portfólio](https://devlucasgodoy.vercel.app) · 💼 [LinkedIn](https://www.linkedin.com/in/devlucasgodoy/) · 🏢 [First Class Dev](https://www.firstclassdev.com.br)

---

## 🛠️ Stack

[![Stack](https://skillicons.dev/icons?i=nextjs,react,ts,tailwind,vite,nodejs,nestjs,express,dotnet,python,fastapi,postgres,mysql,mongodb,prisma,supabase,docker,aws,vercel,cloudflare,git&perline=11)](https://skillicons.dev)

| Área | Tecnologias |
|---|---|
| **Frontend** | Next.js 16 (App Router), React 19, TypeScript, Tailwind CSS 4, Vite, shadcn/ui, Motion, TanStack Query, next-intl |
| **Mobile** | Expo, React Native, expo-router, EAS |
| **Backend** | Node.js, NestJS, Express, .NET 8 (Dapper), Python/FastAPI, Delphi |
| **Dados** | PostgreSQL (Neon, Supabase), Oracle, SQL Server, MySQL, MongoDB, Firebird, Drizzle, Prisma |
| **Auth & segurança** | Better Auth, Auth.js, JWT, MFA/TOTP, Row Level Security, cookies HMAC, rate limit, LGPD |
| **Integrações** | Pix (AbacatePay), Resend, Google Gemini, BRAPI, Binance, PageSpeed Insights |
| **Infra** | Vercel, AWS, Docker, Cloudflare R2, Vercel Blob, PWA (Serwist) |
| **Qualidade** | Vitest, Playwright, xUnit, migrations versionadas, CI |
| **Fiscal & ERP** | NF-e, NFC-e, NFS-e, CT-e, MDF-e, SPED, CNAB, Oracle WinThor |

---

## 🚀 Produtos próprios no ar

| Projeto | O que é | Stack |
|---|---|---|
| [**Syncro OS**](https://www.syncroos.com.br) | Suíte de gestão sobre o ERP WinThor para distribuidoras: força de vendas, pedidos, compras, financeiro e RH, com dados espelhados na nuvem. | Next.js 16, .NET 8, Neon, Oracle, SQL Server, Playwright, xUnit |
| [**FC Noivos**](https://fcnoivos.vercel.app) | Planejamento de casamento: site para convidados e painel para os noivos, com RSVP, orçamento, plano de mesas e Pix. | Next.js 16, Neon, Cloudflare R2, AbacatePay |
| [**Velaris**](https://www.velaris.dev.br) | CRM e gestão para agências e PMEs: do primeiro contato ao contrato, com projetos, chamados, financeiro e DRE. | React 19, Vite, Express, Neon, Gemini |
| [**First Care**](https://www.firstcare.app.br) | Gestão clínica com prontuário eletrônico, agenda, financeiro e relatórios, com RLS e foco em LGPD. | React, Vite, Supabase (Auth, Storage, RLS) |
| [**FC Converter**](https://fcconverter.vercel.app/pt) | Conversor de imagens, áudio, vídeo e documentos 100% no navegador: os arquivos nunca saem do dispositivo. | Next.js 16, FFmpeg (WebAssembly), pdf.js |

### Destaques técnicos

- **SyncroAgent (Syncro OS):** ETL em .NET 8 que espelha Oracle e SQL Server no Postgres de forma incremental, com outbox que grava de volta no ERP preservando operador e auditoria.
- **Segurança no Syncro OS:** login com a senha do WinThor, MFA/TOTP, escopo por filial, permissão por módulo e tela e log de auditoria.
- **FC Converter:** nenhuma rota de API de conversão; FFmpeg compilado para WebAssembly roda tudo no cliente.
- **FC Noivos:** uploads validados pelo conteúdo real do arquivo (magic bytes), comprovantes em bucket privado e senhas com scrypt.

---

## 🧩 Projetos para clientes

| Projeto | Entrega | Stack |
|---|---|---|
| [**TG Distribuidora**](https://www.tgdistribuidora.com.br) | Site e catálogo de distribuidora com 4 unidades em MS, migrado de PHP legado, com SEO local. | Next.js 16, Tailwind 4, React Leaflet |
| [**Derrex**](https://www.derrex.com.br) | Loja, painel administrativo e app nativo iOS/Android para marca de suplementos. | Next.js 15, Prisma, Auth.js, Expo, Cloudflare R2 |
| [**Nova Civil Engenharia**](https://www.novacivil.com.br) | Site institucional com galeria de projetos, FAQ pesquisável e formulário com resposta automática. | Next.js 16, shadcn/ui, Framer Motion |
| [**Welcome Vistos**](https://www.welcomevistos.com.br) | Landing page de consultoria de vistos para 8 países, com eventos de conversão. Cliente desde 2023. | React, Vite 7, shadcn/ui, TanStack Query |
| [**Cortseg**](https://cortseg.vercel.app) | Landing page B2B de fabricante de concertinas, com formulário que leva ao WhatsApp. | Next.js 15, Tailwind CSS |

---

## 🧪 Em desenvolvimento

| Projeto | O que é | Stack |
|---|---|---|
| **RadarB3** | Terminal de análise quantitativa para B3, cripto e ações dos EUA, com alertas, backtesting e insights por IA. | Next.js 16, Neon, Recharts, Gemini |
| **FC Pay** | Gateway e orquestrador de pagamentos Pix e cartão, multi-tenant, sobre PSPs licenciados. | NestJS, Zod, PostgreSQL com RLS |
| **FC Academy** | Plataforma de cursos multi-tenant, com um site personalizável para cada escola. | Next.js 16, Drizzle, Better Auth |
| **FC Moments** | Galeria colaborativa de eventos: convidados enviam fotos e vídeos por QR Code. | Next.js 16, Neon com RLS, Cloudflare R2 |
| **Servix** | CRM e operação para pequenos prestadores: ordens de serviço, agenda e financeiro. | Next.js 15, Drizzle, Auth.js |
| **Duo Class** | Finanças do casal: contas, divisão de despesas, dívidas e metas. | React 19, Vite, Neon Auth, RLS |

Também: [**First Class Wood**](https://first-class-wood.vercel.app), extensão do Chrome que remove barras pretas em monitores ultrawide (React, Vite, MV3), e o [**First Class Insight**](https://fcnews.vercel.app), blog e biblioteca digital em MDX.

Detalhes de cada projeto no [portfólio](https://devlucasgodoy.vercel.app/pt/work).

---

## 💼 Experiência

| Período | Cargo | Empresa |
|---|---|---|
| 2026 – hoje | Sócio & Head de Tecnologia | TG Distribuidora |
| 2021 – hoje | CEO & Fundador | First Class Dev |
| 2022 – 2026 | Analista de Implantação de ERP (estágio → N1 → N2 → implantação) | Ganso Sistemas |
| 2021 – 2023 | Técnico em Informática | IFMS |

## 📚 Formação

- Tecnólogo em Análise e Desenvolvimento de Sistemas — UNIASSELVI
- Técnico em Informática — IFMS

## 📬 Contato

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/devlucasgodoy/)
[![WhatsApp](https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)](https://wa.me/5519996168818?text=Ol%C3%A1!%20Vim%20atrav%C3%A9s%20do%20GitHub.)
[![Telegram](https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/DevLucasGodoy)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:lucas.moraes.godoy@gmail.com)
