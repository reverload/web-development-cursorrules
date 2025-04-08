# CursorRules: Next.js 15 + React 19 + Shadcn UI + Tailwind CSS

Este repositorio contiene un conjunto de reglas (`cursorrules`) optimizadas para desarrollar proyectos frontend modernos enfocados en UX/UI con Next.js 15 (App Router), React 19, Shadcn UI, Tailwind CSS, y otras librerías complementarias como Radix UI y Tanstack Query.

## 📖 Introducción

Las `cursorrules` definen estándares claros para asegurar la consistencia, calidad, accesibilidad, rendimiento y simplicidad en proyectos frontend.

Estas reglas están divididas en:

- **Reglas Core**: Aplican globalmente a todos los archivos.
- **Reglas Satélite**: Aplican específicamente según globs (carpetas o patrones de archivos).

## 🚀 Stack Tecnológico

- **Framework:** Next.js 15 (App Router)
- **Librería UI:** React 19
- **Componentes UI:** Shadcn UI (sobre Radix UI)
- **Estilado:** Tailwind CSS
- **Gestión de Estado y Datos:** Tanstack Query, Zustand, nuqs
- **AI Integrations:** Vercel AI SDK
- **Tipado:** TypeScript

## 🗂️ Estructura de reglas

- 📌 **Core Rules (`/**/*.*`):**
  - Diseño basado en el Design System (Shadcn, Tailwind).
  - Énfasis en simplicidad y elegancia.
  - Uso preferente de React Server Components (RSC).
  - Accesibilidad total (ARIA, navegación teclado, semántica HTML).
  - Responsividad mobile-first.
  - Uso estricto de TypeScript y tipado seguro.
  - Gestión de estado óptima (contextos, Zustand, nuqs).
  - Manejo eficiente de errores y loading states.
  - Integraciones limpias y aisladas (lib).

- 📌 **App Routes (`app/**/*.*`):**
  - Componentes por defecto en servidor (mínimo `use client`).
  - Organización clara de rutas y layouts.
  - Server Actions para mutaciones y formularios.
  - Manejo de caché inteligente en datos.

- 📌 **Componentes (`components/**/*.*`):**
  - Uso prioritario de Shadcn UI y Radix.
  - Reusabilidad y composición efectiva.
  - Tailwind CSS únicamente para estilado.

- 📌 **Hooks (`hooks/**/*.*`):**
  - Encapsulación de lógica compleja y reutilizable.
  - Integración directa con Tanstack Query.

- 📌 **Utilidades (`utils/**/*.*`):**
  - Funciones puras y sin efectos secundarios.
  - Claridad y reusabilidad.

- 📌 **Estilos (`styles/**/*.*`):**
  - Configuración estricta de Tailwind.
  - Uso limitado de CSS global, siempre justificado.

- 📌 **Tipos (`types/**/*.*`):**
  - Tipos globales claros y específicos.
  - Organización por dominio y reutilización máxima.

- 📌 **Librerías Externas (`lib/**/*.*`):**
  - Interfaces limpias para integraciones (Vercel AI, API clients).
  - Encapsulación de detalles complejos.

- 📌 **Rutas API (`app/api/**/*.*`):**
  - API Routes mínimas y claramente delimitadas.
  - Validación estricta y manejo correcto de HTTP.

## 📌 Uso de CursorRules

### ¿Cómo usar estas reglas?

1. Copia o integra estas reglas en la configuración del proyecto o herramienta.
2. Revisa cada regla para comprender cómo aplicarlas en tu día a día.
3. Usa herramientas como ESLint, Prettier y TypeScript configuradas según estos estándares.

### Ventajas al seguir estas reglas:

- **Calidad y mantenibilidad:** Código legible y fácil de modificar.
- **Rendimiento:** Optimización automática al seguir Server Components y buenas prácticas.
- **Accesibilidad:** Cumplimiento de estándares que aseguran aplicaciones accesibles.
- **Colaboración:** Facilita el trabajo en equipo gracias a convenciones claras.

## ✅ Validación y Mejora Continua

- Integra revisiones de código para asegurar cumplimiento.
- Actualiza regularmente estas reglas según avances tecnológicos o nuevas mejores prácticas.

---

¡Usa estas reglas para asegurar que tu proyecto Next.js + React se mantenga limpio, eficiente y agradable de trabajar!

