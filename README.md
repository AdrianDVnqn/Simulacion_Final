# Simulación Final

Repositorio del trabajo práctico integral de Simulación.

## Flujo de trabajo recomendado

- `main` queda como rama estable y no se edita directo.
- Cada parte del TP se trabaja en una rama dedicada a esa sección.
- Antes de empezar una tarea, primero asegurarse de estar parado en `main` actualizado.
- Cuando la tarea está lista, subir la rama y abrir un Pull Request hacia `main`.
- Si hace falta tocar `TP_Simulacion.qmd`, hacerlo solo para integrar inclusiones o ajustes finales.

## Ramas sugeridas por sección

- `sec-1-rng-montecarlo` para la Parte 1.
- `sec-2-mh-bayes` para la Parte 2.
- `sec-3-mm1` para la Parte 3.
- `sec-4-gbm` para la Parte 4.
- `sec-5-gillespie` para la Parte 5.
- `sec-6-integradora` para la Parte Integradora opcional.
- `integracion-final` para unificar detalles, revisar estilo y preparar la entrega final.

## Cómo trabajar en equipo

1. Abrir una terminal dentro de la carpeta del proyecto.
2. Pararse en `main` y actualizarla con `git pull`.
3. Cambiarse a la rama que corresponde con `git switch sec-1-rng-montecarlo`.
4. Si Git dice que la rama no existe todavía en tu compu, usar primero `git fetch origin` y después `git switch sec-1-rng-montecarlo`.
5. Trabajar solo en los archivos de `secciones/` de esa parte.
6. Guardar los cambios con commits chicos y claros.
7. Subir la rama con `git push -u origin nombre-de-rama`.
8. Abrir Pull Request hacia `main`.
9. No mezclar dos secciones distintas en la misma rama salvo que sea la rama 'integración-final'.

## Comandos básicos para no perderse

- Ver en qué rama estás: `git branch`
- Ir a la rama estable: `git switch main`
- Ir a la rama de una sección: `git switch sec-3-mm1`
- Actualizar lo último del repo: `git pull`
- Subir cambios: `git push`
- Subir una rama nueva y dejarla vinculada: `git push -u origin nombre-de-rama`

## Recomendación para Quarto

- Mantener `TP_Simulacion.qmd` como archivo principal que arma el documento final.
- Separar el contenido por partes en archivos más chicos dentro de `secciones/`.
- Evitar subir PDFs durante el desarrollo.
- Compilar el PDF solo al final, cuando el texto esté cerrado.

## Archivos generados

Los archivos PDF quedan ignorados por Git para evitar conflictos con binarios generados localmente.
