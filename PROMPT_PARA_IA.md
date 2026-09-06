# 🤖 BRIEFING Y PROMPT MAESTRO PARA AGENTE DE IA
> **Herramientas compatibles:** Google Antigravity, Claude Code, Cursor, OpenAI Codex, VS Code Copilot.

---

## 🏢 1. IDENTIDAD Y CAPACIDAD DE PLANNING & SOLUTION S.A.
- **Empresa:** Planning & Solution S.A. (RUC: 1793138841001)
- **Especialidad:** Planificación Territorial (LOOTUGS), Actualización integral de PDOT y PUGS, Catastro Multifinalitario, Cartografía SIG, Planes de Movilidad Urbana y Estudios Socioeconómicos.
- **Experiencia Demostrada:** Contratos ejecutados y concluidos a entera satisfacción con GADs Cantonales y Provinciales en Ecuador.
- **Equipo Técnico Clave:**
  - **Director de Proyecto:** Arq. José Vicente (Urbanista y Planificador Territorial, +15 años de experiencia en normativa LOOTUGS).
  - **Coordinador Técnico / SIG:** Ing. Kevin Jiménez (Especialista en Geotecnologías, Catastro y Cartografía Temática).
- **Grafo de Conocimiento Adjunto:** En este repositorio dispones de `knowledge_graph.json` con el detalle de los proyectos anteriores, actas de entrega y certificaciones para respaldar la propuesta.

---

## 📌 2. DATOS DE LA CONVOCATORIA SERCOP / MULTILATERAL
- **Código del Proceso:** `BM-GEF-2026-SOCIO`
- **Entidad Contratante:** Banco Mundial / GEF - Unidad de Sostenibilidad
- **Objeto de la Contratación:** Consultoría Técnica Remota (3 meses): Análisis Socioeconómico y Formulación de Cadenas de Valor Sostenibles para Comunidades Rurales
- **Presupuesto Referencial:** $30,000.00 USD
- **Fecha Límite para Preguntas:** 2026-09-12 18:00
- **Fecha Límite de Entrega de Ofertas:** 2026-09-28 17:00
- **Enlace al Pliego Oficial en SERCOP:** [Consultar Pliego Oficial en SOCE](https://projects.worldbank.org/en/projects-operations/procurement)

---

## 🎯 3. ESTRATEGIA Y EVALUACIÓN PREVIA (Score: 97/100 pts)
- **Modalidad Recomendada:** `IR_SOLOS`
- **Puntos Fuertes Identificados:**
  • Trayectoria consolidada en análisis econométrico, modelos de desarrollo socioeconómico y sostenibilidad.
  • Metodología estructurada para formulación de cadenas de valor y capacidad de entrega remota.

- **Requisitos Críticos a Asegurar en la Oferta:**
  • Ninguno crítico identificado para la fase de postulación técnica.

---

## 🚀 4. TU MISIÓN COMO AGENTE DE IA:
Actúa como el **Director de Licitaciones y Consultoría de Planning & Solution S.A.**  
Tu tarea es redactar y estructurar la **Oferta Técnica y Económica Ganadora** dentro de este repositorio:

### Entregables Requeridos:
1. **`01_METODOLOGIA_TECNICA.md`**:
   - Desarrollar la metodología en **3 fases estructuradas**:
     - *Fase 1:* Diagnóstico biofísico, sociocultural y económico con recopilación de fuentes primarias y secundarias.
     - *Fase 2:* Formulación del plan con articulación estricta a la normativa LOOTUGS, ODS y directrices de la entidad.
     - *Fase 3:* Modelo de gestión, cartera de proyectos priorizados, cronograma de hitos y presupuesto valorado.
2. **`02_MATRIZ_EVALUACION_TECNICA.xlsx` o `.md`**:
   - Detallar la tabla de puntaje (experiencia de la firma, experiencia del personal, plan de trabajo) asegurando 100/100 puntos basándote en `knowledge_graph.json`.
3. **`03_PRESUPUESTO_DESGLOSADO.xlsx` o `.md`**:
   - Tabla de costos directos (honorarios expertos, trabajo de campo, talleres participativos) e indirectos, ajustada exactamente a los $30,000.00 USD.
4. **`04_FORMULARIOS_COMPROMISO_SERCOP.md`**:
   - Formatos estandarizados de compromiso de personal técnico y equipo asignado.

---

## 📁 5. FORMALIZACIÓN Y ENTREGA
Una vez que generes todos los entregables de la propuesta:
1. Mueve los borradores e instrucciones (`PROMPT_PARA_IA.md`) a una subcarpeta `_insumos/` o elimínalos para dejar el repositorio limpio.
2. Actualiza el archivo `README.md` para que sea la **Carátula Ejecutiva Formal** de la oferta técnica presentada por Planning & Solution S.A. ante la entidad contratante.
3. Para hacer push a GitHub sin necesidad de contraseñas, utiliza este enlace autenticado:
   ```bash
   git remote set-url origin https://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@github.com/radarps/propuesta_bm-gef-2026-socio.git
   git add .
   git commit -m "feat(propuesta): oferta tecnica y economica oficial para BM-GEF-2026-SOCIO"
   git push origin main
   ```
4. Notifica automáticamente al equipo en Telegram respondiendo al mensaje original ejecutando:
   ```bash
   curl -s -X POST "https://api.telegram.org/bot8931241873:AAEB06CAgHwVdq4pLLB2SfTg2AH_Zh4qAVc/sendMessage" \
     -d "chat_id=-1004416837038" \
     -d "reply_to_message_id=19" \
     -d "parse_mode=HTML" \
     -d "text=✅ <b>PROPUESTA TÉCNICA COMPLETADA Y SUBIDA A GITHUB</b>%0A%0A📌 <b>Proceso:</b> BM-GEF-2026-SOCIO%0A🏢 <b>Entidad:</b> Banco Mundial / GEF - Unidad de Sostenibilidad%0A🔗 <b>Repositorio:</b> https://github.com/radarps/propuesta_bm-gef-2026-socio%0A%0A<i>La propuesta ha sido completada formalmente y subida al repositorio por el equipo técnico.</i>"
   ```
