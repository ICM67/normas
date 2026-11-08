# normas
# Normativa tributaria – proyecto "LGT temas transversales"

Repositorio de contexto normativo. Cada norma se guarda en `normas/` como Markdown con el texto consolidado del BOE.

**Regla de uso:** citar siempre artículo y apartado literalmente desde estos archivos. La fecha de consolidación de cada archivo consta en su cabecera; si la consulta depende de la redacción vigente en una fecha concreta, comprobar en el BOE el histórico de versiones.

## Índice

| Archivo | Norma | ID BOE | URL BOE |
|---|---|---|---|
| `normas/LGT-Ley-58-2003.md` | Ley 58/2003, de 17 de diciembre, General Tributaria (LGT) | BOE-A-2003-23186 | https://www.boe.es/buscar/act.php?id=BOE-A-2003-23186 |
| `normas/RGR-RD-939-2005.md` | Real Decreto 939/2005, Reglamento General de Recaudación (RGR) | BOE-A-2005-14803 | https://www.boe.es/buscar/act.php?id=BOE-A-2005-14803 |
| `normas/RGAT-RD-1065-2007.md` | Real Decreto 1065/2007, Reglamento General de las actuaciones y los procedimientos de gestión e inspección tributaria (reglamento de gestión e inspección) | BOE-A-2007-15984 | https://www.boe.es/buscar/act.php?id=BOE-A-2007-15984 |
| `normas/RGRVA-RD-520-2005.md` | Real Decreto 520/2005, Reglamento general de desarrollo de la LGT en materia de revisión en vía administrativa (RGRVA) | BOE-A-2005-8662 | https://www.boe.es/buscar/act.php?id=BOE-A-2005-8662 |
| `normas/TRLRHL-RDLeg-2-2004.md` | Real Decreto Legislativo 2/2004, texto refundido de la Ley Reguladora de las Haciendas Locales (TRLRHL) | BOE-A-2004-4214 | https://www.boe.es/buscar/act.php?id=BOE-A-2004-4214 |
| `normas/LPAC-Ley-39-2015.md` | Ley 39/2015, del Procedimiento Administrativo Común de las Administraciones Públicas (LPAC) | BOE-A-2015-10565 | https://www.boe.es/buscar/act.php?id=BOE-A-2015-10565 |

## Formato de cada archivo

Cabecera YAML al inicio:

```yaml
---
norma: Ley 58/2003, de 17 de diciembre, General Tributaria
siglas: LGT
boe_id: BOE-A-2003-23186
url: https://www.boe.es/buscar/act.php?id=BOE-A-2003-23186
consolidado_a: AAAA-MM-DD   # fecha de la última actualización consolidada en el momento de la descarga
descargado: AAAA-MM-DD
---
```

Después, el texto íntegro, con un encabezado `##` por título/capítulo y `###` por artículo (`### Artículo 66. Plazos de prescripción.`), para poder buscar por artículo.

## Cómo obtener el texto

- PDF consolidado: `https://www.boe.es/buscar/pdf/AAAA/BOE-A-AAAA-NNNNN-consolidado.pdf`
- El BOE ofrece también el volumen "Ley General Tributaria y sus reglamentos" en su Biblioteca jurídica (Códigos electrónicos), en PDF y EPUB.

## Actualización

Revisar las normas al menos trimestralmente y tras cada reforma relevante, y anotar la nueva fecha en `consolidado_a`.
