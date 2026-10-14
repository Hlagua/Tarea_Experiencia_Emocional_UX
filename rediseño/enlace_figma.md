# Rediseño en Figma

**Archivo:** https://www.figma.com/design/aeBJgQV0pZDHto4NURDFpA

Marcos del archivo:

| Marco | Contenido |
|---|---|
| ANTES – Original B-4-mapa | Captura original del repositorio del Grupo 1 |
| DESPUÉS – Rediseño (estado inicial) | Paso 4 de 5 con marcador coherente y acción principal clara |
| DESPUÉS – Rediseño (dirección confirmada) | Retroalimentación: aviso verde, pin verde, paso 4 ✓, “Continuar al pago →” |
| Cambios y justificación | Las 6 modificaciones con su principio de IHC |

Prototipo navegable equivalente (usado en las pruebas): [`prototipo_rediseno.html`](prototipo_rediseno.html)
Estados: `?estado=pendiente`, `?estado=confirmado`, `?estado=pago`.

## Modificaciones

| N.º | Modificación | Antes → Después | Principio |
|---|---|---|---|
| 1 | Se elimina la presión artificial | Banner “¡OFERTA ÚNICA!”, contador 09:59 → barra de confianza | Diseño emocional; evitar patrones engañosos; Nielsen #8 |
| 2 | Orientación en el proceso | Pasos sin estado → stepper con ✓ y “Paso 4 de 5” | Nielsen #1 |
| 3 | Mapa coherente | Pin lejos del “123” → un solo marcador sobre la casa, leyenda, zoom 44 px | Nielsen #2; WCAG 2.5.5 |
| 4 | Acción principal + retroalimentación | “OMITIR »” / “Guardar dirección” gris → “Confirmar dirección” + aviso | Nielsen #1, #5 |
| 5 | Control del usuario | — → “Editar dirección”, referencia, “Volver” | Nielsen #3 |
| 6 | Legibilidad y accesibilidad | Tipografías mezcladas, faltas ortográficas → una tipografía, contraste ≥ 4,5:1 | WCAG 1.4.3; Nielsen #8 |

## Verificación de usabilidad y resultados de diseño

Las 6 modificaciones fueron puestas a prueba en el prototipo interactivo con 3 usuarios anonimizados (P1, P2 y P3) ajenos al equipo:
- **Reducción de carga cognitiva y ansiedad:** La eliminación del contador y elementos estridentes aumentó la valoración en M1 de -1,67 a +2,33 ($\Delta = \mathbf{+4,00}$).
- **Visibilidad del estado del sistema:** La retroalimentación verde inmediata en M4 ("Dirección confirmada") y la actualización coherente de la leyenda y pin ("Marcador verde") generaron el mayor salto cualitativo de la experiencia, alcanzando un incremento exacto de $\Delta = \mathbf{+5,33}$ (de -2,67 a +2,67).
- **Consistencia de modelo mental:** Al unificar el marcador sobre el domicilio 123 y dotar de controles táctiles con target > 44px, las dudas y confusiones en el mapa (M3) se erradicaron, pasando de -2,33 a +2,33 con un incremento exacto de $\Delta = \mathbf{+4,67}$.
- **Eficiencia en la interacción:** El tiempo promedio de ejecución de la tarea se redujo de 86,8 s a 37,5 s (-49,3 s, equivalente al 56,8% de ahorro en tiempo).

