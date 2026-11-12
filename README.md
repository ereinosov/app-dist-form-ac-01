# FORM-AC-01 — Análisis de caso: fallo real en un sistema distribuido

Aplicaciones Distribuidas (ISR-701) · UTEQ · Ingeniería de Software · 7.º nivel, paralelo A · SPA 2026–2027

## Caso asignado

Amazon S3, región US-EAST-1 (28 de febrero de 2017).
Fuente principal: informe oficial de AWS, https://aws.amazon.com/message/41926/

## Integrantes (equipo GLMR)

| Integrante | Usuario de GitHub |
|---|---|
| García Bazurto Kevin Leonel | yaser-uwu |
| Lombeida Escaleras Bryan Humberto | BryanLomb |
| Manotoa Alava Carlos Alexander | CarlosManotoa007 |
| Reinoso Vélez Eduardo David | ereinosov |

## Estructura

- `FORM-AC-01/main.tex`: análisis (archivo principal)
- `FORM-AC-01/referencias.bib`: referencias en IEEE
- `FORM-AC-01/main.pdf`: PDF compilado de la versión final
- `FORM-AC-01/diagramas/`: diagrama de causas (`causas.drawio` editable y `causas.pdf` exportado)

## Compilación

Requisitos: MiKTeX o TeX Live con `pdflatex` y `biber`.

Desde la carpeta `FORM-AC-01/`:

```
pdflatex main.tex
biber main
pdflatex main.tex
pdflatex main.tex
```

Resultado: `FORM-AC-01/main.pdf`.

Paquetes LaTeX: inputenc, fontenc, babel (spanish, es-tabla), csquotes, geometry, graphicx, booktabs, tabularx, biblatex (backend biber, estilo ieee), hyperref.

## Versiones

- `v1-preliminar`: versión previa a la exposición
- `v2-final`: versión final