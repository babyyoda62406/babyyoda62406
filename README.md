Construyo productos completos y los dejo funcionando en producción: la API, la
app móvil, el panel web y el servidor donde corre todo.

Trabajo en remoto desde La Habana, en la franja GMT-4, a jornada completa,
parcial o por proyecto.

## Sobre lo que no se ve aquí

Casi todo mi trabajo vive en repositorios privados: producto de empresa y
encargos de clientes. Lo que sí puedo enseñar son versiones públicas saneadas de
cuatro de esos productos, con el mismo código y la misma arquitectura, y con los
datos del cliente sustituidos.

## Proyectos

**[demo-beauty-suite](https://github.com/babyyoda62406/demo-beauty-suite)** —
SaaS multi-tenant de marca blanca para centros de belleza. 48.000 líneas entre
API y web, 54 entidades, 17 módulos de dominio. NestJS 10, Prisma, PostgreSQL 16,
Redis con BullMQ, Stripe, Next.js 15, Docker multi-etapa.

**[demo-crm-voz](https://github.com/babyyoda62406/demo-crm-voz)** —
CRM inmobiliario donde las operaciones repetitivas se dictan: se habla al
micrófono, un modelo traduce la frase en una llamada a una herramienta del CRM y
la acción queda registrada. NestJS, TypeORM, React 19, ElevenLabs. 169 tests.

**[demo-fintech](https://github.com/babyyoda62406/demo-fintech)** —
Plataforma de remesas y libro de caja. 134 tests centrados en el dinero:
redondeo simétrico, sumas sin deriva, idempotencia del webhook, atomicidad de
los asientos. NestJS, Prisma, PostgreSQL, Next.js 15.

**[demo-wa-agent](https://github.com/babyyoda62406/demo-wa-agent)** —
Agente de WhatsApp con tool-calling: el modelo decide qué herramienta llamar y
con qué argumentos. Registro de herramientas con inyección, reintentos con
espera creciente, topes por conversación y comandos bloqueados. Bun, Hono,
Vercel AI SDK, Redis. 127 tests.

## Stack

TypeScript desde 2022. NestJS, Prisma y TypeORM sobre PostgreSQL. React,
Next.js y React Native con Expo. Docker, Redis, Kafka. Despliegue propio en VPS
con CI/CD por webhooks. Jest y Supertest en las API, Maestro en móvil.

## Contacto

deivistm62406@gmail.com · WhatsApp +53 58831892
