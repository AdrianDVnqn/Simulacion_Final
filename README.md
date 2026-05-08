# Simulación Final

Repositorio del trabajo práctico integral de Simulación.

## Flujo de trabajo recomendado

- `main` queda como rama estable y no se edita directo.
- Cada parte del TP se trabaja en una rama dedicada a esa sección.
- Antes de empezar una tarea, crear la rama desde `main` actualizado.
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

1. Actualizar `main` con `git pull` antes de arrancar.
2. Crear la rama de la sección que toca: `git checkout -b sec-1-rng-montecarlo`.
3. Trabajar solo en los archivos de `secciones/` de esa parte.
4. Hacer commits chicos y descriptivos.
5. Subir la rama con `git push -u origin nombre-de-rama`.
6. Abrir Pull Request hacia `main`.
7. No mezclar dos secciones distintas en la misma rama salvo que sea integración final.

## Recomendación para Quarto

- Mantener `TP_Simulacion.qmd` como archivo principal que arma el documento final.
- Separar el contenido por partes en archivos más chicos dentro de `secciones/`.
- Evitar subir PDFs durante el desarrollo.
- Compilar el PDF solo al final, cuando el texto esté cerrado.

## Archivos generados

Los archivos PDF quedan ignorados por Git para evitar conflictos con binarios generados localmente.
