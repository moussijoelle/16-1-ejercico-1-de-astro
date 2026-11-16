# Bio personal — ejercicio 16.1 (Astro)

Primera práctica con Astro del curso: una página de bio sencilla, con Tailwind.

## Qué hace

Es una tarjeta de presentación. Sale mi nombre, el rol (Front-End), una foto, un texto sobre mí, el email, el teléfono y los iconos de GitHub y LinkedIn.

## Cómo probarlo

Hace falta Node (el proyecto pide 22.12 o superior) y pnpm.

```sh
pnpm install
pnpm dev
```

Si quieres ver la versión de producción:

```sh
pnpm build
pnpm preview
```

También está subida aquí: https://astro-16-1-bio.netlify.app

## Cómo lo construí

Todo está en `src/pages/index.astro`. Usé Astro para montar la página y Tailwind (`@tailwindcss/vite`) para el diseño. Los estilos base van en `src/styles/global.css`. En este ejercicio no separé componentes: era para pillar el setup de Astro + Tailwind.

## Cómo comprobarlo

No hay tests automáticos. Lo miro en el navegador con `pnpm dev` (o en el enlace de Netlify): que cargue la bio, la foto, el contacto y los enlaces.

---

Moussi Joelle · [github.com/moussijoelle](https://github.com/moussijoelle)
