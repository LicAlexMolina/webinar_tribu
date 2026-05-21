# Contexto: Integración de botón de registro Luma

## Objetivo
Incrustar un botón de registro de Luma en una landing page de webinar para Tribu Emprendedores.

---

## Código a incrustar (copiar tal cual en el HTML)

```html
<a
  href="https://luma.com/event/evt-lQDmoszq107WLSY"
  class="luma-checkout--button"
  data-luma-action="checkout"
  data-luma-event-id="evt-lQDmoszq107WLSY"
>
  Inscribirse al evento
</a>

<script id="luma-checkout" src="https://embed.lu.ma/checkout-button.js"></script>
```

---

## Notas importantes

- El script `luma-checkout` solo debe incluirse UNA vez por página, aunque el botón aparezca varias veces.
- Si se quiere usar estilo propio para el botón, eliminar la clase `luma-checkout--button` del `<a>`.
- Para etiquetar inscripciones por fuente, agregar: `data-luma-utm-source="fuente"` al `<a>`.

---

## Datos del evento

- ID del evento: evt-lQDmoszq107WLSY
- URL pública del evento: https://luma.com/event/evt-lQDmoszq107WLSY
- Plataforma: Luma

---

## Contexto del proyecto

- Marca: Tribu Emprendedores
- Tema del webinar: "De conversar con IA a operar con IA"
- Formato: Videollamada en vivo por Google Meet
- Ponente: Director fundador de Tribu Emprendedores
- La landing del webinar debe ser más pequeña/compacta que la landing de referencia.