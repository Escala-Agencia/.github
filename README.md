# .github de Escala-Agencia

Valores por defecto de GitHub para los repos de la organización. Es público porque GitHub lo exige.

| Ruta | Para qué |
|---|---|
| `profile/README.md` | Portada de la organización |
| `.github/ISSUE_TEMPLATE/` | 4 formularios con su tipo de issue (Épica, Tarea, Bug, Mejora); entran en «Agencia — Operación» |
| `.github/pull_request_template.md` · `CONTRIBUTING.md` · `SECURITY.md` | Plantilla de PR y normas, heredadas por cada repo sin las suyas |
| `workflow-templates/` | `ci`, `pr-titulo` y `release-please` en Actions → New workflow; llaman a los reutilizables de [`mariomina/.github`](https://github.com/mariomina/.github) |

Los repos de cliente nacen de `Escala-Agencia/plantilla-cliente`; su proyecto, de copiar «Cliente — plantilla».
