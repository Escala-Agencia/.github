# .github de Escala-Agencia

tipo-repo: producto
autonomia: 0

Valores por defecto de GitHub para los repos de la organización (formularios, CONTRIBUTING, SECURITY, portada y plantillas de workflow). Las reglas de trabajo son las de `mario-home/AGENTS.md` y `agencia-home/AGENTS.md`; aquí solo lo propio de este repo. Sin plantilla de PR: el cuerpo lo define pstack.

## Reglas propias

- El repo es público porque GitHub lo exige: nunca entran secretos, IDs de clientes ni datos internos.
- Las plantillas de `workflow-templates/` llaman a la acción y al reutilizable de `mariomina/.github` con `@v1`: un cambio de su interfaz se hace allí, no aquí.
