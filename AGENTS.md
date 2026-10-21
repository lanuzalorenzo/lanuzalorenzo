# Guía para agentes: Perfil personal (lanuzalorenzo)

Este repositorio genera la portada pública del perfil de GitHub (README de perfil). Cualquier asistente de IA (GitHub Copilot, Google Antigravity, Claude, etc.) debe seguir estas directrices:

## Criterio editorial y posicionamiento
- Este README es una **tarjeta de presentación**, no la biografía completa: la fuente única de trayectoria, stack y formación es la web personal (`lanuzalorenzo.github.io`). No dupliques aquí el contenido largo.
- Mantener el posicionamiento técnico sénior: Software Architect (.NET & Azure) especializado en Cloud Security y DevSecOps.
- Enlazar al portfolio público de ciberseguridad sin revelar datos o enlaces a repositorios privados del curso.
- Mantener la tabla de proyectos y estados alineada con el portfolio; no presentar un diseño o un runbook preparado como validación.
- Mantener el enlace a la guía de lectura del portfolio (`docs/guia-de-lectura.md`) alineado con la tabla de proyectos; si cambia su URL, actualizarlo.
- Mantener el enlace al CV ATS (`https://lanuzalorenzo.github.io/assets/cv/lanuza-lorenzo-cv.pdf`) si cambia su ruta.

## Convenciones de Commits
Todos los commits de este repositorio deben seguir estrictamente el estándar **Conventional Commits**:
- Formato: `type(scope): imperative summary in English`.
- **Ámbitos (`scope`) permitidos:** `profile`, `repo`.
- **Tipos permitidos:** `feat`, `fix`, `docs`, `refactor`, `chore`.
- El asunto debe ser imperativo, conciso y redactado en inglés.
- Ejemplos:
  - `docs(profile): update software architect summary and devsecops focus`
  - `docs(profile): format contact information and badges`
