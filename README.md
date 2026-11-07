# Impulse-X — Rocket Tec

Landing estática para el equipo de cohetería Impulse-X, lista para GitHub Pages.

## Estructura

```
index.html
.gitignore
assets/
  impulse-x-logo.png
  musica.mp3
```

> Renombra `_gitignore` a `.gitignore` si lo subes a mano (GitHub web no permite subir archivos que empiecen con punto desde el explorador en algunos casos).

## Fecha de lanzamiento

- **Desde la página:** botón *Cambiar fecha* → elige fecha y hora → *Guardar*. Se guarda en ese navegador y se agrega `?fecha=...` al enlace; usa *Copiar enlace* para compartirlo con la fecha ya puesta.
- **Para todos los visitantes:** en `index.html`, escribe la fecha en `data-launch` de `<section id="countdown">`, con formato `2026-12-15T18:00:00-07:00`.

## Música

`assets/musica.mp3` se reproduce en bucle con botón de pausa y volumen. Los navegadores bloquean el autoplay, así que empieza con el primer clic o toque del visitante.

## Publicación

1. Repositorio público `F1025_503` en `DENZJG08`, rama `main`.
2. **Settings → Pages → Deploy from a branch → main / (root)**.
3. Sitio en `https://denzjg08.github.io/F1025_503/`.
