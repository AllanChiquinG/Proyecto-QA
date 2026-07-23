# Evidencia del Quality Gate

## Resumen
Este documento consolida la evidencia de calidad del proyecto: matriz CTQ,
Definition of Done, tablero de seguimiento y resultado de la validación
automática (Quality Gate) ejecutada en GitHub Actions.

## Enlaces de evidencia
- Repositorio: https://github.com/AllanChiquinG/Proyecto-QA
- Matriz CTQ: [CTQ.md](CTQ.md)
- Definition of Done: [DoD.md](DoD.md)
- Tablero del proyecto (GitHub Project): https://github.com/users/AllanChiquinG/projects/1
- Pull Request de validación: https://github.com/AllanChiquinG/Proyecto-QA/pull/4
- Workflow de Quality Gate: [.github/workflows/quality-gate.yml](../../.github/workflows/quality-gate.yml)

## Resultado del Quality Gate
El workflow `quality-gate.yml` se ejecutó automáticamente en el Pull Request #4
hacia la rama `main`. Resultado: Éxito

Validaciones ejecutadas:
- Existencia de README.md, CTQ.md y DoD.md
- Estructura mínima de documentación Markdown
- Existencia de archivos base del sitio (index.html, styles.css, script.js)
- Linter HTML (HTMLHint) sobre src/index.html

## Estado de los CTQs (al momento de esta entrega)
| CTQ ID | Estado DoD | Prioridad |
|---|---|---|
| CTQ-001 | Pendiente | Must |
| CTQ-002 | Pendiente | Must |
| CTQ-003 | Pendiente | Should |

## Limitaciones documentadas
- No se configuró la regla de protección de rama (branch protection) para
  exigir el status check "quality-gate" antes del merge, dado que se trata
  de un repositorio personal de práctica académica. La validación del gate
  se evidenció manualmente en el Pull Request #4.