
# MANIFIESTO DE EVIDENCIAS — DENTITECH

## Proyecto
**Nombre:** DentiTech — Sistema de Gestión Integral para la Clínica Odontológica Medicus.

**Asignatura:** Ingeniería de Requerimientos (ISR-401).

**Universidad:** Universidad Técnica Estatal de Quevedo (UTEQ).

**Entrega:** E1 — Visión, Alcance, Partes Interesadas, Contexto y Plan de Elicitación.

**Repositorio:** https://github.com/kcontrerasc3-cloud/DentiTech

## 1. Objetivo

Registrar y mantener la trazabilidad de las evidencias que respalden las actividades de levantamiento de información, identificación de partes interesadas, elaboración de modelos y validación de requisitos del proyecto DentiTech.

Este manifiesto distingue los documentos elaborados por el equipo de las evidencias obtenidas directamente de la organización cliente.

## 2. Documentos de trabajo disponibles

| ID | Documento | Ubicación | Estado |
|---|---|---|---|
| DOC-01 | Guion de entrevista | `../instrumentos/01_guion_entrevista.pdf` | Disponible |
| DOC-02 | Cuestionario | `../instrumentos/02_cuestionario.pdf` | Disponible |
| DOC-03 | Guía de observación | `../instrumentos/03_guia_observacion.pdf` | Disponible |
| DOC-04 | Consentimiento informado | `../instrumentos/04_consentimiento_informado.pdf` | Disponible |
| MOD-01 | Diagrama de contexto | `../modelos/diagrama_contexto.drawio` | Disponible |
| MOD-02 | Matriz poder-interés | `../modelos/matriz_poder_interes.drawio` | Disponible |
| INF-01 | Informe DentiTech | `../DentiTech.pdf` | Disponible |

**Nota:** Los instrumentos y modelos son productos elaborados para el proyecto. Su existencia no demuestra que se hayan aplicado entrevistas, observaciones o validaciones con Medicus.

## 3. Registro de evidencias de campo

| ID | Evidencia | Fecha | Responsable | Estado | Archivo o referencia | SHA-256 |
|---|---|---|---|---|---|---|
| EVI-01 | Entrevista con representante de Medicus | Por registrar | Por registrar | Pendiente de documentar | — | — |
| EVI-02 | Observación de procesos de citas y atención | Por registrar | Por registrar | Pendiente de documentar | — | — |
| EVI-03 | Validación de actores, alcance y objetivos | Por registrar | Por registrar | Pendiente de documentar | — | — |

Los registros anteriores son espacios de control, no evidencias de actividades realizadas. Solo se marcarán como completados cuando exista documentación auténtica y verificable.

## 4. Protección de información

- No publicar nombres, teléfonos, cédulas ni historias clínicas de pacientes.
- Solicitar autorización antes de grabar entrevistas o compartir fotografías.
- Anonimizar documentos y capturas que contengan información personal.
- Conservar documentos sensibles en un almacenamiento privado y autorizado.
- Publicar únicamente evidencias cuya difusión haya sido autorizada.

## 5. Verificación de integridad

Cuando se incorpore una evidencia digital, calcular su código SHA-256 y registrarlo en la tabla correspondiente.

En Windows PowerShell se puede utilizar:

```powershell
Get-FileHash -Algorithm SHA256 "C:\ruta\archivo.pdf"
```

El valor obtenido debe corresponder exactamente al archivo registrado.

## 6. Pendientes de validación

- Confirmar con Medicus los datos operativos descritos en el informe.
- Validar las metas de negocio propuestas.
- Confirmar si Asistente dental y Responsable de contabilidad son funciones diferenciadas.
- Registrar fechas, participantes y resultados reales de las actividades de elicitación.
- Incorporar evidencias auténticas y sus hashes SHA-256, cuando estén disponibles.

## 7. Control de actualización

**Responsable de coordinación:** Equipo DentiTech.

**Estado:** Manifiesto inicial de control documental. Evidencias de campo pendientes de registrar y verificar.
