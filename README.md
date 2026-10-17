# Agustín Milesi

```typescript
const developer = {
  name: "Agustín Milesi",
  role: "Full Stack Developer",
  location: "Argentina",
  coreStack: ["Next.js", "TypeScript", "PostgreSQL", "Prisma", "Tailwind CSS"],
  focus: ["Sistemas ERP / POS", "Arquitectura SaaS Multi-Tenant", "Sistemas de Alta Concurrencia"],
  currentStatus: "Construyendo soluciones escalables de extremo a extremo"
};
```

---

### `ecosystem.featuredProjects`

#### 01. Retail ERP & POS Engine
> Sistema de gestión comercial y terminal de punto de venta optimizado para operaciones de alta velocidad.
- **Arquitectura:** Next.js 16 (App Router, Turbopack, Server Actions), TypeScript, Neon Serverless Postgres, Prisma ORM, Tailwind CSS.
- **Capacidades:** Soporte para lectores de código de barra y teclado completo, arqueo ciego de caja con auditoría de faltantes/sobrantes, deducción atómica de inventario (ACID), tickets térmicos para 80mm/58mm, y modo oscuro con paletas dinámicas.
- **Enlaces:** [Demo en Producción ↗](https://milesi-erp.vercel.app) · [Repositorio ↗](https://github.com/AgustinMilesi/erp)

#### 02. Customer Inbox & Forms SaaS
> Plataforma SaaS multi-tenant diseñada para centralizar la comunicación y generación de leads para el ecosistema ERP.
- **Arquitectura:** Next.js 16, TypeScript, Neon Serverless Postgres, Prisma ORM, REST API v1, Webhooks firmados.
- **Capacidades:** Aislamiento estricto de datos por workspace (`organizationId`), formularios embebibles vía `<iframe>` y API headless, triaje de mensajes (New, Read, Archived), y webhooks firmados criptográficamente con HMAC-SHA256.
- **Enlaces:** [Demo en Producción ↗](https://saas-am.vercel.app) · [Repositorio ↗](https://github.com/AgustinMilesi/saas)

#### 03. Contact & Lead Capture Portal
> Portal de contacto y captura de leads de alta intención con mitigación activa de spam.
- **Arquitectura:** Next.js 16, TypeScript, Zod, Tailwind CSS, Neon Serverless Postgres, Resend API.
- **Capacidades:** Validación dual en cliente y servidor con esquema Zod compartido, trampa invisible honeypot para bloqueo de bots, sanitización HTML de entradas y despacho inmediato de emails transaccionales.
- **Enlaces:** [Demo en Producción ↗](https://agustinmilesi-contact.vercel.app) · [Repositorio ↗](https://github.com/AgustinMilesi/contact-page)

---

### `system.specifications`

- **Lenguajes & Runtimes:** TypeScript 5, JavaScript (ESNext), Node.js (>=20), SQL.
- **Frameworks & UI:** Next.js 16 (App Router, Turbopack, Server Actions), React 19, Tailwind CSS 4, Zod.
- **Bases de Datos & ORM:** PostgreSQL, Neon Lakebase (conexiones pooled y directas), Prisma ORM.
- **Seguridad & Concurrencia:** Aislamiento multi-tenant por workspace, cookies seguras con prefijo `__Host-`, hash de sesiones con SHA-256, rate limiting persistente en base de datos, operaciones monetarias en centavos enteros (`BigInt`).
- **Infraestructura & Cloud:** Vercel Edge/Serverless, Resend API, Webhooks HMAC-SHA256, REST APIs v1.

---

### `git.contact`

- **LinkedIn:** [linkedin.com/in/agustin-milesi-1982281b6](https://www.linkedin.com/in/agustin-milesi-1982281b6/)
- **Email:** [agusmilesi2002@gmail.com](mailto:agusmilesi2002@gmail.com)
- **Web de Contacto:** [agustinmilesi-contact.vercel.app](https://agustinmilesi-contact.vercel.app)
