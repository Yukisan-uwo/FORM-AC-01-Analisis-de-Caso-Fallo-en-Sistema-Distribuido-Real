# FORM-AC-01 · Análisis de un fallo en un sistema distribuido

Actividad formativa de la semana 3 de Aplicaciones Distribuidas.
El informe analiza la caída de Cloudflare del 21 de junio de 2022.

## Integrantes del equipo CGMZ

- Luis Mario Zambrano Parraga (P1)
- Allison Michelle Mera Jumbo (P2)
- Joseph Alexander Calderón Saltos (P3)
- Roger Steven García Sangoquiza (P4)

## Archivos

- [Informe compilado](Documento%20latex%20y%20PDF%20compilado/main.pdf)
- [Código fuente LaTeX](Documento%20latex%20y%20PDF%20compilado/main.tex)
- [Diagrama editable en draw.io](diagramas/causas.drawio.xml)

## Cómo compilar

Desde la raíz del repositorio, con XeLaTeX y Biber instalados, ejecuta:

```sh
cd "Documento latex y PDF compilado"
xelatex main.tex
biber main
xelatex main.tex
xelatex main.tex
```

El archivo `main.pdf` se genera en esa misma carpeta.