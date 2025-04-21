# Limpieza de historial con git rebase -i

## Objetivo:
Mejorar la claridad del historial de commits y unificar commits que por sí solos no significan nada

## Commits originales:
- "Arreglos"
- "Cambios"
- "Actualización de cosas"

## Qué hice:
1. Usé `git rebase -i HEAD~3` para poder modificar mis commits y ponerlos más claros
2. Cambié los mensajes con `reword` (el primero y el tercero)
3. Fusioné dos commits con `squash` (el segundo con el primero)
4. Usé `git push --force` para subir los cambios

## Resultado:
- Historial más claro y más organizado
