<div align="center">

# 💒 QR Wedding Seating SaaS

### Sistema Profesional Multi-Tenant de Asignación de Mesas para Bodas

[![Next.js](https://img.shields.io/badge/Next.js-14-black?style=for-the-badge&logo=next.js)](https://nextjs.org/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5-blue?style=for-the-badge&logo=typescript)](https://www.typescriptlang.org/)
[![Prisma](https://img.shields.io/badge/Prisma-5-2D3748?style=for-the-badge&logo=prisma)](https://www.prisma.io/)
[![Tailwind](https://img.shields.io/badge/Tailwind-3-38B2AC?style=for-the-badge&logo=tailwind-css)](https://tailwindcss.com/)
[![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](LICENSE)

**[🚀 Demo en Vivo](#) • [📖 Documentación](RESUMEN-SAAS.md) • [💰 Pricing](#pricing) • [🎯 Roadmap](SAAS-FEATURES.md)**

</div>

---

## 🎯 ¿Qué es QR Wedding Seating?

Sistema **SaaS profesional** que permite a novios y wedding planners gestionar la asignación de mesas de forma inteligente usando códigos QR. Los invitados escanean el QR y encuentran su mesa al instante. **Sin confusiones, sin filas, sin estrés.**

### ✨ Características Principales

<table>
<tr>
<td width="50%">

#### 📱 Para Invitados
- ✅ Escanean QR y ven su mesa
- ✅ Check-in con PIN
- ✅ Mobile-first
- ✅ Sin apps, solo web

</td>
<td width="50%">

#### 🎨 Para Organizadores
- ✅ Dashboard profesional
- ✅ Drag & drop interactivo
- ✅ Analytics en tiempo real
- ✅ Import/Export CSV

</td>
</tr>
</table>

---

## 💰 Planes de Suscripción {#pricing}

<table>
<tr>
<th width="33%">Free</th>
<th width="33%">Pro ⭐</th>
<th width="33%">Enterprise</th>
</tr>
<tr>
<td>

**$0/mes**

- 1 evento
- 50 invitados
- QR básico
- Dashboard básico

</td>
<td>

**$49/mes**

- 5 eventos
- Invitados ilimitados
- Personalización completa
- Analytics avanzados
- PDF profesional
- Soporte prioritario

</td>
<td>

**$199/mes**

- Eventos ilimitados
- White-label
- Dominio personalizado
- API access
- SMS notifications
- Soporte 24/7

</td>
</tr>
</table>

---

## 🚀 Demo Rápido

### Vista Invitado
```
1. Invitado escanea QR en la entrada
2. Escribe su nombre
3. Ve su mesa asignada
4. Confirma llegada con PIN
```

### Dashboard Admin
```
1. Login al dashboard
2. Crea mesas y asigna invitados
3. Drag & drop para reorganizar
4. Ve analytics en tiempo real
5. Descarga QR para imprimir
```

---

## 🛠️ Stack Tecnológico

<div align="center">

| Frontend | Backend | Database | Styling | Deploy |
|----------|---------|----------|---------|--------|
| Next.js 14 | Next.js API | Prisma ORM | Tailwind CSS | Netlify |
| React 18 | NextAuth | PostgreSQL | shadcn/ui | Supabase |
| TypeScript | Zod | SQLite (dev) | Lucide Icons | Vercel |

</div>

---

## 📦 Instalación Rápida

### Requisitos
- Node.js 18+
- npm o yarn
- PostgreSQL (o Supabase)

### Setup en 5 minutos

```bash
# 1. Clonar repositorio
git clone https://github.com/TU-USUARIO/qr-wedding-seating-saas.git
cd qr-wedding-seating-saas

# 2. Instalar dependencias
npm install

# 3. Configurar variables de entorno
cp .env.example .env
# Edita .env con tus credenciales

# 4. Configurar base de datos
npx prisma db push
npx prisma db seed

# 5. Iniciar servidor
npm run dev
```

Abre [http://localhost:3000](http://localhost:3000) 🎉

---

## 🎨 Screenshots

<div align="center">

### Landing Page
![Landing Page](https://via.placeholder.com/800x400/667eea/ffffff?text=Landing+Page+Profesional)

### Dashboard PRO
![Dashboard](https://via.placeholder.com/800x400/764ba2/ffffff?text=Dashboard+con+Analytics)

### Vista Invitado
![Vista Invitado](https://via.placeholder.com/800x400/f093fb/ffffff?text=Vista+Mobile+Invitado)

</div>

---

## 📚 Documentación Completa

### 🚀 Para Empezar
- [**LISTO-PARA-DEPLOY.md**](LISTO-PARA-DEPLOY.md) - Estado del proyecto y próximos pasos
- [**INICIO-RAPIDO.md**](INICIO-RAPIDO.md) - Deploy en 3 pasos (27 min)
- [**DEPLOY-GITHUB-NETLIFY.md**](DEPLOY-GITHUB-NETLIFY.md) - Guía completa paso a paso

### 💼 Negocio
- [**RESUMEN-SAAS.md**](RESUMEN-SAAS.md) - Resumen ejecutivo y proyecciones
- [**MARKETING-PLAN.md**](MARKETING-PLAN.md) - Plan de marketing completo
- [**SAAS-FEATURES.md**](SAAS-FEATURES.md) - Características SaaS detalladas

### 🔧 Técnica
- [**API-REFERENCE.md**](API-REFERENCE.md) - Referencia completa de API
- [**CARACTERISTICAS-PRO.md**](CARACTERISTICAS-PRO.md) - Features PRO
- [**COMANDOS-RAPIDOS.md**](COMANDOS-RAPIDOS.md) - Comandos útiles

### 📖 Más Documentación
- [**INDICE-DOCUMENTACION.md**](INDICE-DOCUMENTACION.md) - Índice completo (20+ docs)

---

## 🎯 Características Destacadas

### 🏢 Multi-Tenant Architecture
- Organizaciones con múltiples usuarios
- Roles y permisos (Owner, Admin, Member)
- Aislamiento completo de datos
- Múltiples eventos por organización

### 📊 Analytics Avanzados
- Tracking de eventos en tiempo real
- Métricas de llegadas
- Gráficos interactivos
- Exportación de reportes

### 🎨 Personalización Total
- Colores personalizados
- Logo personalizado
- 4 temas (elegant, modern, rustic, beach)
- Mensajes personalizados
- Dominio personalizado (Enterprise)

### 🗺️ Mapa Interactivo
- Drag & drop para asignar invitados
- Vista visual de mesas
- Indicadores de ocupación
- Reorganización en tiempo real

### 📧 Notificaciones (Próximamente)
- Email automáticos
- SMS (Enterprise)
- Webhooks
- Integraciones (Zapier, Make)

---

## 💡 Casos de Uso

### 👰 Para Novios
```
Problema: Organizar 200 invitados, familias complicadas
Solución: Plan Pro por 2 meses ($98)
Resultado: Setup en 30 min, 0 confusiones, invitados felices
```

### 💼 Para Wedding Planners
```
Problema: Gestiona 30 bodas/año, proceso manual
Solución: Plan Enterprise ($199/mes)
Resultado: Ahorra 10 horas por boda, puede cobrar más
ROI: $15,000/año
```

### 🏨 Para Venues
```
Problema: 100 eventos/año, quejas frecuentes
Solución: Plan Enterprise + Custom
Resultado: 90% menos quejas, mejores reviews
```

---

## 📈 Proyecciones de Negocio

| Año | Usuarios Free | Usuarios Pro | Usuarios Enterprise | Ingresos Anuales |
|-----|---------------|--------------|---------------------|------------------|
| 1   | 1,000         | 100          | 5                   | **$70,000**      |
| 2   | 5,000         | 750          | 25                  | **$500,000**     |
| 3   | 20,000        | 4,000        | 100                 | **$2,600,000**   |

### 💰 Ventajas Competitivas
- **50% más barato** que la competencia ($49 vs $99-299)
- **Setup en 5 minutos** vs horas de capacitación
- **Soporte en español** (mercado desatendido)
- **Features únicos** (drag & drop, analytics, QR inteligente)

---

## 🚀 Roadmap

### ✅ Fase 1: MVP (Completado)
- [x] Sistema base de asignación de mesas
- [x] Dashboard profesional
- [x] Vista invitado con QR
- [x] Import/Export CSV
- [x] Features PRO (drag & drop, analytics)

### ✅ Fase 2: SaaS (Completado)
- [x] Multi-tenant architecture
- [x] Landing page profesional
- [x] 3 planes de suscripción
- [x] Analytics avanzados
- [x] Personalización de marca

### 🔄 Fase 3: Monetización (En Progreso)
- [ ] Integración Stripe
- [ ] Sistema de pagos
- [ ] Billing dashboard
- [ ] Trial de 14 días

### 📅 Fase 4: Crecimiento (Q1 2025)
- [ ] Email notifications
- [ ] Onboarding wizard
- [ ] Team collaboration
- [ ] API v1

### 📅 Fase 5: Escala (Q2 2025)
- [ ] SMS notifications
- [ ] White-label completo
- [ ] Custom domains
- [ ] Mobile apps

---

## 🤝 Contribuir

¡Las contribuciones son bienvenidas! Por favor:

1. Fork el proyecto
2. Crea tu feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit tus cambios (`git commit -m 'Add some AmazingFeature'`)
4. Push a la branch (`git push origin feature/AmazingFeature`)
5. Abre un Pull Request

---

## 📄 Licencia

Este proyecto está bajo la Licencia MIT - ver el archivo [LICENSE](LICENSE) para más detalles.

---

## 🌟 Agradecimientos

- [Next.js](https://nextjs.org/) - Framework React
- [Prisma](https://www.prisma.io/) - ORM
- [Tailwind CSS](https://tailwindcss.com/) - Styling
- [shadcn/ui](https://ui.shadcn.com/) - Componentes UI
- [Lucide](https://lucide.dev/) - Iconos

---

## 📞 Contacto y Soporte

### Para Usuarios
- 📧 Email: support@qrweddingseating.com
- 💬 Chat: En vivo 9am-6pm
- 📖 Docs: [Documentación Completa](INDICE-DOCUMENTACION.md)

### Para Ventas (Enterprise)
- 📧 Email: sales@qrweddingseating.com
- 📞 Phone: +1 (555) 123-4567
- 📅 Calendar: [Agendar Demo](https://calendly.com/qrweddingseating)

---

## 🎉 ¡Listo para Lanzar!

Este proyecto es un **SaaS completo** listo para:
- ✅ Vender suscripciones
- ✅ Escalar a miles de usuarios
- ✅ Generar ingresos recurrentes
- ✅ Competir con soluciones enterprise

**Potencial de ingresos:** $2.6M en 3 años

---

<div align="center">

### ⭐ Si te gusta este proyecto, dale una estrella en GitHub

**[🚀 Ver Demo](#) • [📖 Documentación](RESUMEN-SAAS.md) • [💬 Contacto](#contacto-y-soporte)**

---

**Hecho con ❤️ para tu día especial** 💒✨

</div>
