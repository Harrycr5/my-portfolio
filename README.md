# Harry Cobos — Portfolio

Portfolio bilingüe hecho con Astro y desplegado en GitHub Pages.
Los iconos de tecnologías y redes sociales se sirven como imágenes WebP locales desde `public/images/webp/`.

## Desarrollo local

Necesitas Node.js 22.23.4 o posterior.

```sh
npm install
npm run dev
```

La versión en español está en `/my-portfolio/` y la versión en inglés en `/my-portfolio/en/`.

## Compilar y previsualizar

```sh
npm run build
npm run preview
```

## Publicar gratis en GitHub Pages

El workflow de GitHub Actions despliega automáticamente al hacer push a `main`.

1. En GitHub, abre **Settings → Pages**.
2. En **Build and deployment → Source**, selecciona **GitHub Actions**.
3. Haz push a `main`; revisa el avance en la pestaña **Actions**.

La dirección publicada será <https://harrycr5.github.io/my-portfolio/>.

---

# Harry Cobos — Portfolio

Bilingual Astro portfolio deployed to GitHub Pages.

Run `npm install` and `npm run dev` for local development. Build with `npm run build`.
To publish, set **Settings → Pages → Source** to **GitHub Actions**; pushes to `main`
will deploy automatically.
