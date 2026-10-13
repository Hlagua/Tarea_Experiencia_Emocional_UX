# Evaluación y rediseño de la experiencia emocional del usuario

**Universidad Técnica de Ambato** · Facultad de Ingeniería en Sistemas, Electrónica e Industrial · Carrera de Software  
**Asignatura:** Interacción Humano-Computador · Nivel 5 “A” · **Docente:** Ing. José Caiza, Mg.  
**Tema:** Emoción y experiencia de usuario (UX) · Tarea grupal (3 puntos)

Caso de estudio: prototipo original [`B-4-mapa`](https://github.com/juANO2202/HCI-2026-G1/blob/main/prototipos/original/B-4-mapa.png.jpeg) (paso 4 “Mapa” del proceso de compra de *SuperOfertas Ecuador*, repositorio del Grupo 1).

| Producto obligatorio | Ubicación / Enlace |
|---|---|
| Prototipo rediseñado en **Figma** | https://www.figma.com/design/aeBJgQV0pZDHto4NURDFpA |
| **Herramienta interactiva de prueba** (GitHub Pages) | https://hlagua.github.io/Tarea_Experiencia_Emocional_UX/herramienta_prueba/ |
| Portal web de navegación del proyecto | [`index.html`](index.html) |
| **Informe final (formato APE)** | [`informe/informe_final.pdf`](informe/informe_final.pdf) |
| Curva emocional | [`curva_emocional/curva_emocional.png`](curva_emocional/curva_emocional.png) |
| Matriz UX | [`matriz/matriz_ux.xlsx`](matriz/matriz_ux.xlsx) |
| Comparación antes/después | [`rediseño/antes_despues.png`](rediseño/antes_despues.png) |
| Evidencias y pruebas de usuarios | [`evidencias/pruebas_usuarios/`](evidencias/pruebas_usuarios/) |

## Integrantes y roles

| Integrante | GitHub | Rol | Responsabilidad |
|---|---|---|---|
| Alison Marcela Cobos Taco | [@Itsuna18](https://github.com/Itsuna18) | Desarrolladora Back-End | Análisis cuantitativo de emociones, trazabilidad de datos y consolidación de la matriz UX en Excel |
| Melany Saleth Cevallos Goyes | [@SalyC15](https://github.com/SalyC15) | Desarrolladora Front-End | Rediseño en Figma, prototipo interactivo y comparación visual antes/después |
| Henry Daniel Lagua Flores | [@Hlagua](https://github.com/Hlagua) | QA (Quality Assurance) | Estructura del repositorio, protocolo de prueba, inspección C1–C5 y control de calidad del informe APE |
| Carlos Giovanni Ramos Jácome | [@carlitosgiovanniramos](https://github.com/carlitosgiovanniramos) | Tester | Aplicación de las pruebas con usuarios (original y rediseño) y registro de evidencias en CSV |

El detalle de las contribuciones individuales está en [`CONTRIBUCIONES.md`](CONTRIBUCIONES.md) y en el historial de commits.

## Metodología

1. **Inspección del prototipo original:** Establecimiento de la tarea concreta, 5 momentos de interacción y capturas numeradas C1–C5 (hipótesis de diseño a verificar con usuarios). → [`evidencias/original/`](evidencias/original/)
2. **Prueba con usuarios ajenos al equipo:** Evaluación en la versión original con 3 participantes externos bajo escala de valencia de −3 a +3 por momento, emoción experimentada y evidencia observada. → [`evidencias/pruebas_usuarios/`](evidencias/pruebas_usuarios/)
3. **Curva emocional y matriz UX:** Representación de curvas individuales, promedio y matriz UX con fundamentación en heurísticas de Nielsen, principios de Norman y accesibilidad WCAG 2.1. → [`curva_emocional/`](curva_emocional/), [`matriz/`](matriz/)
4. **Rediseño en Figma:** 6 modificaciones prioritarias sobre la interfaz original y comparación visual antes/después. → [`rediseño/`](rediseño/)
5. **Validación:** Prueba del rediseño bajo las mismas condiciones y cálculo de mejoras ($\Delta$).

**Tarea evaluada:** *“Estás comprando un celular en SuperOfertas Ecuador. Ya ingresaste tus datos. En esta pantalla verifica que el pedido llegará a Calle Inventada 123 y confirma la dirección para continuar al pago.”*

| Momento | Fase | Descripción |
|---|---|---|
| M1 | Antes | Primera impresión de la pantalla |
| M2 | Durante | Orientación (en qué paso está y qué debe hacer) |
| M3 | Durante | Localizar el domicilio en el mapa |
| M4 | Durante | Guardar / confirmar la dirección |
| M5 | Después | Continuar al pago y confianza final |

## Hallazgos principales

### Evidencias de la inspección inicial:
- **C1 · M1** — Banner “¡OFERTA ÚNICA!”, contador 09:59 y fondo amarillo saturado: presión artificial.
- **C2 · M2** — Indicador de pasos sin estado completado, tipografías mezcladas, título poco claro.
- **C3 · M3** — El pin rojo no coincide con el marcador “123” de la dirección; el mapa no tiene leyenda.
- **C4 · M4** — “Guardar dirección” gris y sin retroalimentación; mensaje “¡¡No pierdas la Ofertta!!”.
- **C5 · M5** — La acción principal es “OMITIR »”, ambigua, y lleva a un pago con suscripción premium preseleccionada.

### Resultados y validación con usuarios:
- **Participantes evaluados:** 3 personas ajenas al equipo, anonimizadas bajo los códigos **P1**, **P2** y **P3**, cuya participación y autorización de registro para fines académicos se documenta en [`evidencias/pruebas_usuarios/sesion_evaluacion_usuarios.jpg`](evidencias/pruebas_usuarios/sesion_evaluacion_usuarios.jpg).
- **Momentos críticos identificados (Original):** **M4** (*Guardar / confirmar dirección*, promedio **-2,67**) y **M3** (*Localizar domicilio en el mapa*, promedio **-2,33**), provocados por la ausencia de retroalimentación ante el clic y la contradicción entre el pin rojo y la dirección "123".
- **Promedio general emocional:** Pasó de **-1,93** (experiencia negativa) a **+2,47** (experiencia altamente positiva), logrando un incremento global exacto de **+4,40 puntos**.
- **Mayor mejora observada:** En **M4** con un incremento exacto de **+5,33 puntos** (de -2,67 a +2,67) y en **M3** con **+4,67 puntos** (de -2,33 a +2,33), convirtiendo la frustración e incertidumbre en satisfacción gracias a la confirmación visual en verde y correspondencia del mapa.
- **Eficiencia objetiva (tiempo de interacción):** El tiempo total promedio de la tarea disminuyó de **86,8 s** a **37,5 s** (reducción neta de **-49,3 s**, equivalente a un **56,8% de mayor rapidez**).
- **Percepción de confianza para pagar (escala 1 a 5):** Aumentó significativamente de **1,67/5** a **4,67/5** sobre 5 puntos ($\Delta = \mathbf{+3,00}$), eliminando el rechazo al pago y la sospecha de patrones engañosos.
- **Entorno de prueba del rediseño:** Evaluado funcionalmente en [`rediseño/prototipo_rediseno.html`](rediseño/prototipo_rediseno.html) (construido con los componentes y flujo de Figma).
- **Limitación metodológica:** Se documenta el efecto de aprendizaje al realizar un diseño intrasujeto con descanso entre sesiones.

## Estructura del repositorio

```
Tarea_Experiencia_Emocional_UX/
├── README.md
├── CONTRIBUCIONES.md
├── index.html               # portal web de navegación del repositorio
├── herramienta_prueba/      # aplicación web interactiva utilizada para registrar las pruebas
├── evidencias/
│   ├── original/            # B-4-mapa, capturas anotadas C1–C5, pantallas de contexto
│   └── pruebas_usuarios/    # protocolo, resultados_pruebas.csv y sesion_evaluacion_usuarios.jpg
├── curva_emocional/
│   └── curva_emocional.png  # curva individual, promedio, comparativa y resultados.json
├── matriz/
│   └── matriz_ux.xlsx       # matriz completa en tabla con cuadrícula sin sombreado
├── rediseño/
│   ├── antes_despues.png    # comparación visual antes/después
│   └── enlace_figma.md      # enlace al archivo en Figma y justificación de heurísticas
└── informe/
    └── informe_final.pdf    # informe final en formato oficial APE de la UTA (tabla con cuadrícula)
```

> Participantes externos anonimizados: P1, P2 y P3. Los participantes autorizaron expresamente la toma y uso académico de su imagen y registros de evaluación bajo reserva estricta de sus datos personales.
