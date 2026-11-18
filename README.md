# .github de Escala-Agencia

Valores por defecto de GitHub para los repos de la organización. Es público porque GitHub lo exige.

| Ruta | Para qué |
|---|---|
| `profile/README.md` | Portada de la organización |
| `.github/ISSUE_TEMPLATE/` | 4 formularios con su tipo de issue (Épica, Tarea, Bug, Mejora). Cada proyecto recoge los issues de sus repos con su auto-add («Agencia — Operación»: `home-agencia` y `web`; «Cliente — `<slug>`»: `cliente-<slug>`) |
| `CONTRIBUTING.md` · `SECURITY.md` | Normas, heredadas por cada repo sin las suyas. Sin plantilla de PR: el cuerpo lo define pstack |
| `workflow-templates/` | `pr` (checks de PR en un solo job) y `release-please` (diario) en Actions → New workflow; usan la acción y el reutilizable de [`mariomina/.github`](https://github.com/mariomina/.github) con `@v1` (mariomina/mario-home#134) |
| `.github/workflows/pr.yml` | CI de este repo, en un solo job: título convencional y sin marcas de conflicto |

Los repos de cliente nacen de `Escala-Agencia/agencia-plantilla-cliente`; su proyecto, de copiar «Cliente — plantilla».
