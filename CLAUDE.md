# Trueque Kampaoh — Landing Page

## Qué es este proyecto

Landing page de conversión para el programa **Trueque** de Kampaoh. La propuesta: artistas, profesores de yoga, magos, músicos, pintacaras y otros talentos dinamizan uno de los campings de Kampaoh con sus actividades a cambio de alojamiento gratuito para ellos y un acompañante.

URL producción prevista: `es.kampaoh.com/trueque`

## Marca Kampaoh

- **Tagline:** "Camping, fácil y bonito" / "Camping sin líos"
- **Tono:** Cercano, informal, aventurero, positivo. Tuteo siempre.
- **Paleta:** verde bosque (#1B4332), verde medio (#2D6A4F), verde claro/salvia (#74C69D), arena cálida (#F4E4C1), naranja/ámbar CTA (#E76F51), crema (#FDFCF8)
- **Tipografía:** Playfair Display (headings), Inter (body)
- **Web referencia:** https://es.kampaoh.com

## Estructura de la landing

1. **Hero** — Headline de impacto + CTA scroll to form
2. **El trueque** — Explicación del concepto en 3 columnas
3. **¿Quién puede participar?** — Grid animado de perfiles (artista, yoga, magia, música, teatro...)
4. **Cómo funciona** — 3 pasos visuales
5. **Qué obtienes** — Beneficios: noche gratis + acompañante + experiencia única
6. **Formulario de solicitud** — Nombre, email, disciplina, descripción, destino, fechas
7. **Footer** — Links Kampaoh

## Stack técnico

- Single-file HTML (index.html) con CSS y JS embebidos
- Sin dependencias externas salvo Google Fonts e Iconos (SVG inline)
- Animaciones con Intersection Observer (no libraries)
- Formulario: HTML nativo (conectar a backend/Zapier en producción)

## Notas de desarrollo

- El archivo vive en `/Users/victorarias/Documents/Trueque/index.html`
- Optimizado para mobile-first
- Abrir directamente en browser (no requiere servidor)
