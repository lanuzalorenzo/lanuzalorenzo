# Guía para agentes: perfil público (lanuzalorenzo)

README de perfil de GitHub: una tarjeta de presentación, no la biografía ni el archivo de proyectos.

## Contenido

- La fuente única de trayectoria, stack, formación y certificaciones es la web personal: <https://lanuzalorenzo.github.io>. Aquí solo posicionamiento, proyectos y enlaces; no dupliques el contenido largo.
- Mantén la tabla de proyectos y estados alineada con el portfolio; no presentes un diseño o un runbook preparado como validación.
- Enlaces clave: [guía de lectura](https://github.com/lanuzalorenzo/portfolio-ciberseguridad-lorenzo/blob/main/docs/guia-de-lectura.md) y [CV ATS](https://lanuzalorenzo.github.io/assets/cv/lanuza-lorenzo-cv.pdf). Si cambian sus rutas, actualízalos.
- `main` exige PR, los dos checks de CI y rama actualizada; solo el propietario fusiona, salvo las PRs de Dependabot de parche y minor, que fusiona el flujo automático si pasan los checks.

## Estilo

- El estándar editorial completo —español claro, apertura llana, jerga y claridad que no cambia lo que se afirma— está en el [contrato del portfolio](https://github.com/lanuzalorenzo/portfolio-ciberseguridad-lorenzo/blob/main/AGENTS.md). En este README: estados explícitos (Validado · Parcial · Runbook preparado · Diseño · Pendiente), sin secretos, datos personales sensibles ni enlaces a repositorios privados.

## Verificación

```bash
python3 scripts/check_links.py
gitleaks detect --source . --redact --verbose --exit-code 2
```

Son los dos checks de `.github/workflows/ci.yml`: enlaces relativos y secretos sobre el historial completo.

## Commits

Formato: `type(scope): imperative summary in English`. Scopes: `profile`, `repo`. Tipos: `feat`, `fix`, `docs`, `refactor`, `chore`. Asunto imperativo, conciso y en inglés.
