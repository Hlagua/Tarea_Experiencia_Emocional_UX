# Contribuciones y plan de trabajo

La guía evalúa el **trabajo colaborativo verificable** (0,50 pts): commits, archivos modificados y participación documentada. Cada integrante debe hacer **sus propios commits desde su cuenta**. No hagan commits por otra persona.

## Preparación (una sola vez)

1. Aceptar la invitación de colaborador que llega al correo de GitHub.
2. Clonar el repositorio:
   ```bash
   git clone https://github.com/Hlagua/Tarea_Experiencia_Emocional_UX.git
   cd Tarea_Experiencia_Emocional_UX
   ```
3. Antes de empezar cada tarea: `git pull`. Al terminar: `git add …`, `git commit -m "…"`, `git push`.

## Tareas por integrante

### Henry Lagua (@Hlagua) · QA
- [x] Estructura del repositorio, README y guía de contribuciones.
- [x] Inspección del original y capturas numeradas C1–C5 (`evidencias/original/`).
- [x] Protocolo de prueba (`evidencias/pruebas_usuarios/protocolo_prueba.md`).
- [x] Coordinación del rediseño inicial, estructura de entregables y control de calidad.
- [x] Revisión final del informe APE (ortografía, tablas con cuadrícula, referencias IEEE) y compilación del PDF para entrega.

### Carlos Ramos (@carlitosgiovanniramos) · Tester
- [x] Aplicar la prueba de la **versión original** a 3 personas ajenas al equipo (P1, P2, P3).
- [x] Aplicar la prueba del **rediseño** a los mismos 3 usuarios bajo la misma tarea y escala de -3 a +3.
- [x] Consolidar el registro de datos en `evidencias/pruebas_usuarios/resultados_pruebas.csv`.
- [x] Registro de observaciones cualitativas y comentarios en voz alta por momento.

### Alison Cobos (@Itsuna18) · Back-End
- [x] Análisis cuantitativo de datos emocionales y cálculo de promedios, desviaciones y deltas ($\Delta$).
- [x] Elaboración de las curvas emocionales individuales, promedio y comparativa antes/después en `curva_emocional/`.
- [x] Elaboración y estructuración de la matriz UX completa en `matriz/matriz_ux.xlsx` (formato sin relleno con cuadrícula).
- [x] Verificación de la consistencia métrica entre la curva emocional y los hallazgos cualitativos.

### Melany Cevallos (@SalyC15) · Front-End
- [x] Rediseño en Figma del flujo y componentes visuales (`https://www.figma.com/design/aeBJgQV0pZDHto4NURDFpA`).
- [x] Prototipado de la propuesta de solución (`rediseño/prototipo_rediseno.html`).
- [x] Comparaciones visuales antes/después (`rediseño/antes_despues.png`, `rediseño/antes_despues_vertical.png`).
- [x] Documentación de heurísticas de usabilidad y verificación de diseño en `rediseño/enlace_figma.md`.

## Registro de contribuciones

| Fecha | Integrante | Rol | Contribución | Tarea |
|---|---|---|---|---|
| 2026-10-13 | Henry Lagua (@Hlagua) | QA / Coordinador | Estructura del repositorio, README y guía de contribuciones | `chore(repo)` |
| 2026-10-13 | Henry Lagua (@Hlagua) | QA / Arquitecto | Inspección del prototipo original B-4-mapa y capturas numeradas C1–C5 | `docs(inspeccion)` |
| 2026-10-13 | Carlos Ramos (@carlitosgiovanniramos) | Tester | Protocolo de prueba y despliegue de herramienta web interactiva | `test(protocolo)` |
| 2026-10-13 | Carlos Ramos (@carlitosgiovanniramos) | Tester | Pruebas con usuarios anonimizados (P1, P2, P3), CSV y registro fotográfico | `test(ux)` |
| 2026-10-14 | Melany Cevallos (@SalyC15) | Front-End | Rediseño en Figma, prototipo HTML y comparación antes/después | `feat(ui)` |
| 2026-10-14 | Alison Cobos (@Itsuna18) | Back-End | Curvas emocionales individuales, comparativa y matriz UX con formato de cuadrícula | `feat(metrics)` |
| 2026-10-14 | Henry Lagua (@Hlagua) | QA / Coordinador | Compilación de informe final APE en PDF/DOCX con tablas con cuadrícula y control de calidad | `docs(report)` |
