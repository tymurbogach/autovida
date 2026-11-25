# AutoVida — Gestión para taller mecánico

Proyecto real para el taller del padre: todo tipo de trabajo mecánico.
Objetivo doble: resolver un problema real + aprender a fondo React/Next.js como junior.

## Estado
Repo recién creado. Stack en decisión (ver abajo). Sin código aún.

## Idea inicial (a refinar)
- Clientes, vehículos (matrícula, VIN, km)
- Órdenes de trabajo / reparaciones: diagnóstico → presupuesto → aprobación → reparación → entrega
- Citas, historial por vehículo, fotos del antes/después
- Presupuestos y facturas simples, control de estado de pago
- Recordatorios: ITV, revisiones, cambios de aceite

## Stack propuesto (pendiente de confirmar contigo)
- Frontend + Backend: Next.js 15 (App Router) + TypeScript
- UI: Tailwind CSS + shadcn/ui
- Base de datos: PostgreSQL + Prisma + Docker
- Auth: Auth.js (NextAuth v5)
- Deploy: Docker en tu Raspberry Pi / NAS, como haces con JobPilot y LazyTripZ

## Roadmap de aprendizaje
1. Fase 0: modelo de datos y maqueta (clientes → vehículos → órdenes)
2. Fase 1: CRUD completo + auth básica
3. Fase 2: presupuestos/facturas PDF, fotos, buscador por matrícula
4. Fase 3: tests, CI, deploy en tu homelab

> Este README es el punto de partida. Lo evolucionamos cuando definamos el alcance MVP.
