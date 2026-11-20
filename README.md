# 👋 Hola, soy Luis Miguel Cabrera

### Desarrollador .NET Senior · Full Stack | C# · ASP.NET Core · SQL Server · React

Llevo **más de 9 años** construyendo software de negocio de punta a punta: **base de datos, API, panel e integraciones**.

Mi trabajo principal ha sido en el **sector turístico** — plataformas de reservas, backoffices e integraciones con proveedores —, pero también he construido sistemas para **otros sectores**: un colegio profesional, pymes, financieras, industria, contabilidad, salud y educación.

📍 Santiago de los Caballeros, República Dominicana · Disponible para trabajo remoto (UTC-4)

[![Portafolio](https://img.shields.io/badge/Portafolio-lcabreraportafolio.netlify.app-135BEC?style=for-the-badge&logo=netlify&logoColor=white)](https://lcabreraportafolio.netlify.app/)
[![Contacto](https://img.shields.io/badge/Contacto-Solicitar_cotización-101622?style=for-the-badge)](https://lcabreraportafolio.netlify.app/contacto)

| Años de experiencia | Proyectos en producción | Plataformas ERP / SaaS | Sectores |
| :-----------------: | :---------------------: | :--------------------: | :------: |
| **9+**              | **12**                  | **4**                  | **7+**   |

---

## 🚀 Sobre mí

* 💻 Desarrollador .NET Senior con foco en backend y trabajo en todo el stack
* 👥 He liderado un equipo de 3 desarrolladores en migraciones de plataformas legacy
* ✈️ Plataformas de reservas, backoffices e integraciones para el sector turístico
* 🩺 Sistema de certificados sanitarios del Colegio Dominicano de Médicos Veterinarios
* 🧾 ERPs, facturación electrónica, préstamos y back offices contables
* 🔌 Integraciones con proveedores externos, DGII (e-CF), TSS, Cardnet, Azul y QuickBooks
* 🤖 Automatización de procesos manuales con Playwright
* 🏛️ APIs con Clean Architecture, SOLID, JWT/OAuth y pruebas unitarias
* ☁️ Despliegue con CI/CD en Azure DevOps y en IIS sobre Windows Server
* 🧠 Actualmente construyo una plataforma de IA empresarial en .NET 10

---

# 💼 Experiencia

## Desarrollador Full Stack .NET — SICCDATA

**Julio 2017 – Actualidad** · Plataformas de reservas para el sector turístico

* Lideré un **equipo de 3 desarrolladores** en la migración de las plataformas legacy **Dominicana Tours** y **Tropitours** a React y ASP.NET Core
* Actualmente lidero el desarrollo de **Eurovip**, una nueva plataforma de reservas
* Diseñé una **API de reservas multicanal** que gestiona el ciclo completo de la reserva y es consumida desde varios canales de venta
* Desarrollé una **API central** que unifica en un solo punto el acceso a datos de todos los sitios web
* Construí un **backoffice de carga de contenido e inventario** integrado con proveedores externos (Travelplan, NewBlue y Soltours)
* Automaticé con **Playwright** el envío de documentación: el sistema completa la reserva en el portal del proveedor, descarga el bono y envía al cliente el bono, el seguro y la carta de confirmación
* Optimizo consultas, índices y procedimientos almacenados en **SQL Server**
* Despliego con pipelines de **CI/CD en Azure DevOps** y mantengo los sistemas en producción

---

# ✈️ Proyectos en el sector turístico

```text
   ┌────────────┐   ┌────────────┐   ┌──────────────────┐
   │ Sitios web │   │ Backoffice │   │ Canales de venta │
   └─────┬──────┘   └─────┬──────┘   └────────┬─────────┘
         └────────────────┼───────────────────┘
                          │
              ┌───────────▼────────────┐
              │   API de reservas      │
              │   multicanal + API     │
              │   central de datos     │
              └───────────┬────────────┘
                          │
        ┌─────────────────┼──────────────────┐
        │                 │                  │
  ┌─────▼──────┐   ┌──────▼───────┐   ┌──────▼──────────┐
  │ SQL Server │   │ Proveedores  │   │ Worker          │
  │            │   │ externos     │   │ Playwright      │
  └────────────┘   └──────────────┘   └──────┬──────────┘
                                             │
                                  ┌──────────▼──────────┐
                                  │ Bono · Seguro ·     │
                                  │ Carta al cliente    │
                                  └─────────────────────┘
```

| Proyecto | Qué es | Mi trabajo |
| -------- | ------ | ---------- |
| **Dominicana Tours** | Plataforma de reservas de viajes | Lideré la migración de la plataforma legacy a React y ASP.NET Core |
| **Tropitours** | Plataforma de reservas de viajes | Lideré la migración de la plataforma legacy a React y ASP.NET Core |
| **Eurovip** | Nueva plataforma de reservas | Lidero su desarrollo desde el análisis hasta producción |
| [**Go Caribe**](https://gocaribe.es/) | Agencia de viajes online especializada en el Caribe: paquetes a Punta Cana, Riviera Maya y Jamaica | Sitio de reservas de paquetes vacacionales con ofertas por destino, duración y tipo de habitación |
| [**Nohian Collection**](https://nohiancollection.com/) | Hotel boutique de lujo en Santiago | Sitio web del hotel: presentación de la experiencia y de sus suites (Deluxe, Executive y Nohian Collection Suite) |

---

# 🌎 Proyectos fuera del sector turístico

## ⭐ Colvet — Colegio Dominicano de Médicos Veterinarios

El proyecto que más destaco fuera del turismo. Para el colegio profesional que regula el ejercicio de la medicina veterinaria en República Dominicana construí **dos sistemas**:

### 🩺 [Certificados Colvet](https://certificados.colvet.org/) — emisión y validación de certificados sanitarios

**El reto:** el Colegio necesitaba emitir certificados sanitarios de animales que cualquiera pudiera verificar, y cobrar por ellos en línea.

**Qué construí:**

* Los veterinarios colegiados crean, gestionan y firman digitalmente los certificados desde su cuenta
* Cada certificado se genera en **PDF con código QR**; al escanearlo, cualquier tercero lo valida en una página pública
* **Pagos en línea con Cardnet** para la compra de certificados y los planes de membresía
* Registro de tratamientos por certificado, con catálogos de especies, razas y tipos de tratamiento
* Gestión de colegiados por filial y de usuarios con dos roles: administrador y colegiado
* Consultas y reportes de certificados, y reporte de transacciones de pago para administración
* Recuperación de contraseña por correo

**Stack:** ASP.NET Core MVC · .NET 10 · EF Core + Dapper · SQL Server · Razor · Bootstrap · Cardnet · IIS

### 🏛️ [Colvet.org](https://colvet.org/) — portal institucional

Portal público del Colegio: beneficios de la colegiatura, educación continua, servicios al veterinario (como la certificación para exportación de animales y el plan de pensiones) y el papel del veterinario en la salud pública, la inocuidad alimentaria y el bienestar animal.

---

## 🏢 [MiSoluPymes](https://erp.misolupymes.com/) — ERP para pymes

ERP multiempresa y multisucursal para pymes dominicanas.

**El reto:** las pymes llevaban facturación, inventario, nómina y obligaciones fiscales en herramientas separadas y con procesos manuales ante la DGII y la TSS.

**Qué construí:**

* Facturación electrónica (e-CF), ventas, compras, inventario y cuentas por cobrar por empresa y sucursal
* Altas y bajas de empleados en la TSS automatizadas con un worker en Playwright
* Agenda fiscal con vencimientos, roles y permisos, e integración con QuickBooks

**Stack:** ASP.NET Core 10 · Dapper · SQL Server · Next.js · Playwright

---

## 💳 [Credit Center](https://creditcenter.cloud/) — gestión de préstamos

SaaS de gestión de préstamos, clientes y cobros para financieras y prestamistas.

**El reto:** las financieras controlaban cuotas, mora y cobros en hojas de cálculo, sin trazabilidad ni recibos formales.

**Qué construí:**

* Plataforma multi-tenant: cada financiera opera con sus datos aislados
* Préstamos, calendario de cuotas, cobros y cálculo automático de mora
* Recibos en PDF con código QR, exportación a Excel y contraseñas con Argon2id

**Stack:** ASP.NET Core 10 · Dapper · SQL Server · Next.js · React 19

---

## 📊 [La Mascota Online](https://lamascotaonline.cloud/) — back office contable

Back office contable y administrativo en tiempo real.

**El reto:** la operación dependía de una base de datos en producción y de un sistema externo que había que conciliar a mano cada semana.

**Qué construí:**

* Panel administrativo sobre la base de datos existente, sin interrumpir la operación
* Permisos granulares por usuario y por grupo
* Sincronización semanal de balances con el sistema externo mediante automatización

**Stack:** .NET 10 · EF Core · SQL Server · Next.js · Playwright

---

## 🧩 Más proyectos por sector

| Proyecto | Sector | Descripción |
| -------- | ------ | ----------- |
| [**Allen Dominicana**](https://allen.alltotalit.com/) | Industria / ERP | Sistema de control operativo de planta: contabilidad, logística de exportaciones, recursos humanos y auditoría de usuarios |
| [**Nortruck RD**](https://nortruckrd.com/) | Maquinaria pesada | Catálogo de venta y renta de maquinaria pesada, equipos y repuestos para construcción, minería y logística |
| [**Rodmoq**](http://rodmoq.com/) | Contabilidad y fiscal | Sitio corporativo de una firma de asesoría contable e impositiva: enfoque, servicios y requisitos para iniciar |
| [**Grupo Santa Gema**](https://gruposantagema.com/) | Salud / residencias | Sitios de un grupo de residencias para personas mayores y con discapacidad intelectual, con panel de administración de contenido |
| [**Ya En Clase**](https://yaenclase.netlify.app/) | Educación | Web que lleva la televisión educativa a internet: canales y horarios por nivel (primaria, secundaria y educación especial) |

---

# 🧠 IA empresarial

## EnterpriseAI.Lab — proyecto personal, en desarrollo

Plataforma reutilizable para integrar modelos de lenguaje (**Claude API**) en sistemas empresariales.

* **Stack:** C# · .NET 10 · ASP.NET Core · SQL Server · React + TypeScript
* **En construcción:** API central, RAG sobre documentos, herramientas de consulta a SQL Server, agentes, MCP y panel administrativo

---

# 🛠️ Stack

## 💻 Backend

![C#](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logoColor=white)
![.NET](https://img.shields.io/badge/.NET_10-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![ASP.NET Core](https://img.shields.io/badge/ASP.NET_Core-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)

* C#
* .NET 8 / 10
* ASP.NET Core
* Minimal APIs
* APIs REST
* ASP.NET Core MVC y Razor Pages
* JWT / OAuth
* Swagger / OpenAPI y Scalar
* Dapper y Entity Framework Core
* Node.js y Express

## 🌐 Frontend y móvil

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)

* React y Next.js
* TypeScript y JavaScript
* HTML5 y CSS3
* Tailwind CSS y Bootstrap
* React Native y Expo

## 🗄️ Datos

![SQL Server](https://img.shields.io/badge/SQL_Server-CC2927?style=for-the-badge&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)

* SQL Server: optimización de consultas, índices y procedimientos almacenados
* MySQL y MariaDB
* PostgreSQL y MongoDB
* Modelado de bases de datos y aislamiento de datos por tenant

## 🔌 Integraciones y automatización

* APIs de proveedores externos (Travelplan, NewBlue, Soltours)
* DGII · facturación electrónica (e-CF)
* TSS / SUIR
* Cardnet y Azul (Banco Popular)
* QuickBooks
* Playwright
* PDFs con código QR y exportación a Excel

## ☁️ Cloud y DevOps

* Azure
* Azure DevOps · CI/CD
* IIS en Windows Server
* Netlify
* Git y GitHub

## 🧩 Arquitectura y calidad

* Clean Architecture
* Principios SOLID
* Plataformas multi-tenant, multiempresa y multisucursal
* Pruebas unitarias
* Roles y permisos granulares, auditoría de usuarios

## 🧠 IA (en formación)

* Claude API
* RAG
* Agentes
* MCP

---

# 🏗️ Cómo trabajo

> Primero el negocio, después el código.

* **Primero el negocio** — antes de programar entiendo cómo opera la empresa: quién usa el sistema, qué reportes necesita y qué procesos se pueden automatizar
* **Entregas por etapas** — módulos que se pueden usar pronto, con avances reales cada semana
* **Soporte después de producción** — mantenimiento, ajustes fiscales y nuevas funciones

---

# 🎓 Formación

* **Tecnólogo Superior en Desarrollo de Software** — Instituto Tecnológico de Las Américas (ITLA), 2012 – 2015
* Cursos: Metodología de Desarrollo Ágil (ITLA) · Desarrollador .NET (Microsoft Virtual Academy)
* Idiomas: español nativo · inglés básico (lectura fluida de documentación técnica)

---

# 📫 Conectemos

Disponible para proyectos de:

**Reservas y turismo • ERP • SaaS • Facturación electrónica • Fintech • Integraciones • IA empresarial**

🌐 [lcabreraportafolio.netlify.app](https://lcabreraportafolio.netlify.app/) · ✉️ [Contacto](https://lcabreraportafolio.netlify.app/contacto)
