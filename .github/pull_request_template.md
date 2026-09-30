## Resumen

<!-- Qué cambia y por qué, en 2 o 3 líneas. -->

Cierra #

## Tipo de cambio

- [ ] Feature
- [ ] Bug
- [ ] Deuda técnica
- [ ] Documentación
- [ ] Agente, skill o política (repositorio de plataforma)

## Autoría

- [ ] Humano
- [ ] Agente: `nombre-del-agente` (nivel N2) — persona responsable: @
- [ ] Pareja humano + agente

## Handoff del agente

<!-- Obligatorio si el PR lo abrió un agente (skill agent-handoff-contract). Borra esta sección si no aplica. -->

| Campo | Contenido |
|---|---|
| **Objetivo** | |
| **Entradas** | |
| **Salida** | |
| **Evidencia** | |
| **Supuestos y riesgos** | |
| **Siguiente responsable** | |

## Evidencia

<!-- Pruebas en verde, capturas antes/después, reportes. Sin datos personales reales. -->

## Definition of Done (mínima del piloto, README 13.3)

- [ ] Criterios de aceptación cumplidos, con evidencia (arriba)
- [ ] Pruebas en verde en CI (TDD cuando hay código)
- [ ] Checks obligatorios en verde
- [ ] Sin hallazgos de seguridad críticos o altos abiertos
- [ ] Documentación actualizada en este PR con frontmatter válido, o declaración de que no hay impacto: ⟨motivo⟩
- [ ] Si aplica: accesibilidad (UI), pruebas E2E o de API, migraciones reversibles

## Revisión humana

<!-- La marca quien revisa, no quien abre el PR. Después envía la revisión desde Files changed → Review changes → Comment (un comentario en la conversación no cuenta). Indicador de R15: docs/runbooks/indicador-r15.md -->

- [ ] Leí el diff completo, no solo el resumen
- [ ] Verifiqué la evidencia contra los criterios de aceptación de la historia
- [ ] Revisé seguridad: secretos, permisos, datos personales y entradas no confiables
- [ ] El tamaño y el propósito son los de una sola historia
- [ ] Dejé al menos una observación concreta en la revisión

<!-- La fusión la hace una persona. QA en staging, verificación post-deploy y aceptación del PO se registran en la historia (skill definition-of-done). -->
