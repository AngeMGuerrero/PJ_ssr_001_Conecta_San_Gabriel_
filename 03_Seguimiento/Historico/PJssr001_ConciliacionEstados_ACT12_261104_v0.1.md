# Conciliación de estados | ACT-12 · revisión v0.1

**Proyecto:** PJ-SSR-001 · Conecta San Gabriel  
**Fecha de referencia:** 04/11/2026  
**Estado:** nota de control en revisión; no sustituye el Registro Descriptivo ACT-12 v1.0.

## Hallazgo
El Registro Descriptivo de Seguimiento Semanal ACT-12 v1.0 presenta el balance **3 Done, 9 In Progress y 2 Todo**, mientras que la exportación CSV identificada como corte del 04/11/2026 contiene **12 Done, 2 In Progress y 0 Todo** sobre las 14 actividades. Ambas distribuciones suman 14, pero no corresponden al mismo estado del tablero. Se requiere aclarar si representan momentos de captura distintos.

## Conciliación con el CSV publicado
| Estado | Registro descriptivo v1.0 (observación por verificar en PDF) | CSV 04/11/2026 (verificado) |
| --- | ---: | ---: |
| Done | 3 | 12 |
| In Progress | 9 | 2 |
| Todo | 2 | 0 |
| **Total** | **14** | **14** |

En el CSV, **ACT-12 y ACT-13** permanecen `In Progress`; ACT-01 a ACT-11 y ACT-14 están `Done`.

## Tratamiento propuesto
1. Mantener el PDF ACT-12 v1.0 como evidencia del estado documentado originalmente hasta aprobar una revisión controlada.
2. Preparar **ACT-12 v1.1** que indique explícitamente el corte de referencia, el balance **12/2/0**, y la diferencia respecto de **3/9/2** como antecedente, sin atribuir fechas de captura que no estén acreditadas.
3. Cotejar las cifras y los 17 hipervínculos del PDF v1.0, conservando contenido técnico, identidad institucional y enlaces válidos en la revisión.
4. Actualizar los enlaces al PDF vigente solo después de publicar y verificar v1.1. No modificar estados del tablero ni cerrar el Issue #12 por esta conciliación.

## Fuentes
- [Exportación Seguimiento semanal · CSV 04/11/2026](PJssr001_Exportacion_SeguimientoSemanal_20261104.csv)
- [Registro descriptivo ACT-12 v1.0 · PDF](../02_Evidencias/ACT-12/PJssr001_ACT-12_RegistroSeguimiento_261104_v1.0.pdf)
- [Vista Seguimiento semanal](https://github.com/users/AngeMGuerrero/projects/1/views/2)
- [Issue #12](https://github.com/AngeMGuerrero/PJ_ssr_001_Conecta_San_Gabriel_/issues/12)
