# Eduardo Navarro

**Agentic QA Engineer** · Automatización de pruebas · Full Stack Developer — Cartagena, Colombia

Construyo agentes de IA que hacen el trabajo de QA: verifican que el código cumpla lo que se pidió, ejecutan las pruebas y reportan los bugs en Jira.

*English: QA engineer who builds AI agents that do the QA work: they check that the code meets what was requested, run the tests and file the bugs in Jira.*

[Portafolio](https://portfolio.edudev.biz) · [Clon digital (conversa con mi avatar)](https://cv.edudev.biz) · [LinkedIn](https://www.linkedin.com/in/eduardonavarroecheverria) · [Correo](mailto:edudevcol@gmail.com)

---

## 🎯 Qué hago

Desde 2020 estoy en la Sociedad Portuaria Regional de Cartagena automatizando pruebas de aplicaciones web críticas con **Selenium, Playwright y TestComplete**, con pruebas funcionales y de APIs REST en metodología ágil (SCRUM). Hoy me enfoco en el **Agentic QA**: agentes de IA que cubren el ciclo de pruebas. Como también desarrollo (React, Node.js, TypeScript), construyo mis propias herramientas.

## 🤖 Agentes que he construido

- **Cazador de Bugs**: cruza el código entregado por el desarrollador contra los criterios de aceptación y verifica si lo desarrollado incluye lo que se pidió.
- **Agente ejecutor**: ejecuta las pruebas de forma autónoma.
- **Agente reportador**: reporta en Jira, de forma autónoma, los casos de prueba y los bugs con sus correcciones.
- **Playwright Workflow Builder**: las pruebas se arman arrastrando nodos, al estilo n8n, y se encadenan en un solo flujo.
- **Plataforma de casos de prueba y criterios de aceptación**: genera los casos y los documenta en Jira y Confluence.
- **Clon digital**: un avatar 3D conversacional por voz, conectado a servidores MCP y a Google Workspace. Las acciones sensibles piden confirmación hablada. Pruébalo en [cv.edudev.biz](https://cv.edudev.biz).

## ⚙️ Cómo trabajan

- Cada caso de prueba queda enlazado a su criterio de aceptación: criterio, caso y bug quedan trazables.
- Los agentes cruzan Jira, la documentación funcional y el código, y validan contra la base de datos, no solo contra la pantalla.
- Un filtro de "abogado del diablo" baja los falsos positivos: solo pasa lo que resiste ser refutado.
- Cada hallazgo sale con receta y traza reproducibles.
- Los Jira de corrección se crean enlazados al criterio, con la evidencia adjunta y siempre con visto bueno humano.

## 📊 Impacto (estimaciones mías, no mediciones)

Cifras que calculé bajo supuestos que detallo en mi [perfil](https://portfolio.edudev.biz/perfil.json); no son resultados medidos en un ciclo real.

| Indicador | Estimación |
|---|---|
| Tiempo para generar criterios y casos de un documento funcional | −93 % |
| Tiempo de regresión frente a pruebas manuales | −80 % |
| Esfuerzo humano de la regresión | −95 % |
| Tiempo de reporte de un hallazgo con evidencia | −93 % |
| Bugs detectados por ciclo frente a pruebas manuales | +30-40 % |

## 🔌 Mi perfil como servidor MCP

Mi perfil profesional está publicado como un **servidor MCP de solo lectura**, sin cuenta ni autenticación, para que tu asistente de IA lo consulte directamente:

```
https://api.edudev.biz/mcp
```

Abre los **conectores** de tu agente (por ejemplo, en Claude: *Ajustes › Conectores › Agregar conector personalizado*), pega esa dirección y pregúntale por mí. Herramientas: `get_profile`, `get_experience`, `get_skills`, `list_projects`, `get_education`, `evaluate_job_fit` (pásale una oferta y calcula el encaje), `get_contact` y `ask_the_clone`.

*English: my profile is a read-only MCP server (no authentication) at the address above. Add it as a custom connector in your AI agent and ask about me.*

## 🧰 Stack

**Agentic AI:** agentes de IA autónomos · MCP (Model Context Protocol) · agentes de voz en tiempo real (Gemini Live API, WebSocket) · flujos de pruebas por nodos · LLMs (Claude, Gemini, GPT, OpenAI)

**Testing:** Playwright · Cypress · TestComplete · Selenium WebDriver · Postman · pruebas funcionales y de APIs REST

**Desarrollo:** TypeScript / JavaScript · React · Node.js · Express · Java · SQL · MongoDB · Python

**Herramientas:** Jira · Confluence · Git · Docker · SCRUM

![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=fff)
![React](https://img.shields.io/badge/-React-61DAFB?style=flat-square&logo=react&logoColor=000)
![Node.js](https://img.shields.io/badge/-Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![Playwright](https://img.shields.io/badge/-Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white)
![Selenium](https://img.shields.io/badge/-Selenium-43B02A?style=flat-square&logo=selenium&logoColor=white)
![Jira](https://img.shields.io/badge/-Jira-0052CC?style=flat-square&logo=jira&logoColor=white)
![MCP](https://img.shields.io/badge/-MCP-6A5ACD?style=flat-square)

## 🚀 Proyectos con demo pública

- [AI Test Case Generator](https://ai-test-cases-generator-bay.vercel.app): casos de prueba generados con IA y exportación a Jira · [código](https://github.com/edudevcol/ai-test-cases-generator)
- [AI Script Generator Playwright](https://playwright-ai-wlz9.vercel.app): scripts de Playwright a partir de lenguaje natural · [código](https://github.com/edudevcol/playwright-ai)
- [AI Test Data Generator](https://tdm-generator-ai.vercel.app): datos de prueba sintéticos con LLMs · [código](https://github.com/edudevcol/tdm-generator-ai)

Los agentes de la Sociedad Portuaria (Cazador de Bugs, ejecutor, reportador y Workflow Builder) los construí para la empresa y no tienen demo pública.
