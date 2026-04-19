# Base App

## Descripción del proyecto

Plantilla web **Next.js + Firebase** pensada como punto de partida para SaaS, paneles o aplicaciones con login, áreas protegidas, tema claro/oscuro y componentes UI coherentes (Tailwind, shadcn/ui).

## Problema que resuelve

Reduce semanas de trabajo repetitivo (autenticación, layout, integración Firebase, formularios validados, notificaciones) cuando necesitás validar una idea o entregar un MVP sin reinventar la base técnica en cada proyecto.

## Stack

- Next.js (App Router), TypeScript, Tailwind CSS, shadcn/ui  
- Firebase (Auth, Firestore, Storage), TanStack Query, Zustand, React Hook Form + Zod, Sonner  

## Requisitos

- Node.js LTS  

## Instalación

```bash
npm install
npm run dev
```

Abre [http://localhost:3000](http://localhost:3000). Scripts útiles: `build`, `start`, `lint`, `format`.

## Variables de entorno

Creá `.env.local` con las variables `NEXT_PUBLIC_FIREBASE_*` y lo que necesite tu instancia Firebase (revisá `lib/firebase/`). No hay `.env.example` en la raíz de este repo; podés tomar como guía el archivo equivalente en otros proyectos del workspace o la consola de Firebase.

## Documentación adicional

Si el repo incluye `GETTING_STARTED.md` u otros `.md`, sirven como ampliación de la plantilla.
