# PBA Líbano — Municipal & Project Data Room
## Sala de Datos del Activo Municipal y Proceso de Concesión APP
### Expediente de Debida Diligencia del Activo Público · Ley 1508 de 2012
**Ecobank Development Colombia S.A.S. — Originador**  
*Edición Oficial del Activo · Septiembre 2026*

---

## Propósito de esta Sala de Datos

Este espacio compila la totalidad de los antecedentes jurídicos, títulos prediales, certificaciones municipales, expedientes técnicos, matriz de riesgos CONPES 3714, estudios de demanda regional y minutas del contrato de concesión relacionados con el **activo físico y el proceso municipal** de la **Planta de Beneficio Animal (PBA) del Municipio de Líbano, Tolima**.

> [!NOTE]
> **Delimitación de Alcance — Sala de Datos Municipal vs. Sala de Datos de Inversión:**  
> Esta sala de datos (`ruapp/data-room/`) es de carácter **institucional, técnico y municipal**, centrada exclusivamente en la infraestructura pública, la titularidad del predio, los actos administrativos de la Alcaldía de Líbano, los permisos ambientales (CORTOLIMA), el estudio de mercado pecuario y el marco de concesión APP bajo la Ley 1508 de 2012.  
> 
> La **Sala de Datos de Inversión (Investor Data Room)** —que estructurará la tesis de retorno de capital, vehículos corporativos internacionales (SPV Florida LLC), tabla de capitalización, tokenomics, pacto de accionistas y contratos de suscripción— se desarrollará de forma independiente (en la órbita de `capital/`) y se apoyará en esta sala de datos municipal como capa probatoria del activo subyacente.

---

## Estructura Modular del Data Room

```text
ruapp/data-room/
├── README.md                                      <-- Este documento guía
│
├── 00_resumen_ejecutivo/                          <-- Visión general, tesis de inversión y arquitectura APP
│   ├── pba-libano-investment-teaser-v1.md         <-- Teaser ejecutivo de inversión y fundamentos
│   └── estructura-institucional-app-v1.md         <-- Marco normativo: Ley 1508/2012, 30 años, 5% contraprestación
│
├── 01_titulos_y_seguridad_juridica/               <-- Cadena de títulos, predio y certificaciones oficiales
│   ├── informe-titulos-matricula-364-917-v1.md    <-- Estudio de títulos: Matrícula 364-917 y Esc. 1860/1988
│   ├── certificacion-oficial-contratacion-v1.md   <-- Certificado FO-GDC-A03-13 (Cero contratos vigentes/terceros)
│   ├── oficio-respuesta-alcaldia-predio-v1.md     <-- Oficio AL-RS-2026-00005653 (Tradición, catastro y servicios)
│   ├── oficio-planeacion-uso-suelo-y-no-rechazo-v1.md <-- Oficio AL-RS-2026-00005383 (PBOT Industrial y Cero Rechazo)
│   ├── plan-reconciliacion-cabida-operativa-v1.md <-- Reconciliación de área (1.035 m² titulados vs ~3.000 m² huella)
│   │   [Soportes Documentales Oficiales en PDF]:
│   ├── 2026-08-29-al-rs-2026-00005383-planeacion-uso-suelo-y-ausencia-iniciativas.pdf <-- PBOT Industrial & Cero Rechazo
│   ├── 2026-09-10-al-rs-2026-00005653-respuesta-solicitud-contratos-y-predio.pdf       <-- Servicios, Catastro & Tradición
│   ├── 2026-09-10-fo-gdc-a03-13-certificacion-contratacion-mantenimiento-acceso.pdf    <-- Certificado Negativo de Pasivos
│   └── 1988-11-09-escritura-1860-notaria-unica-libano-adjudicacion-municipio.pdf       <-- Escritura de Adjudicación al Municipio
│
├── 02_expediente_app_concesion/                   <-- Estructuración oficial ante la Administración Municipal
│   ├── prefactibilidad-pba-libano-v1.md           <-- Documento maestro de Prefactibilidad (Decreto 1082/2015)
│   ├── factibilidad-alcance-y-estudios-v1.md      <-- Alcance de estudios de Factibilidad (Fases F1 a F7)
│   ├── borrador-minuta-concesion-app-v1.md        <-- Minuta contractual formal de concesión a 30 años
│   │   [Soporte Corporativo en PDF]:
│   └── 2026-08-20-acta-06-junta-directiva-ecobank-autorizacion-ruapp.pdf <-- Acta No. 6 Firma y Radicación RUAPP
│
├── 03_anexos_tecnicos_y_ambientales/              <-- Soporte técnico, ambiental, operativo y de riesgos
│   ├── matriz-riesgos-conpes-3714-v1.md           <-- Matriz de 39 riesgos del proyecto y asignación contractual
│   ├── estandares-niveles-servicio-pba-v1.md      <-- Indicadores de servicio y estándares sanitarios INVIMA
│   ├── plan-gestion-social-comunitaria-v1.md      <-- Programa de gestión comunitaria y valor compartido Día 1
│   └── estado-permiso-ambiental-cortolima-v1.md   <-- Resolución CORTOLIMA 1910/2022 y estrategia PTAR
│
└── 04_mercado_y_respaldo_institucional/           <-- Demanda comercial, hato regional y legitimidad política
    ├── estudio-demanda-catchment-12-municipios-v1.md <-- Cuantificación de hato ganadero regional (165.488 cabezas)
    └── presentacion-institucional-concejo-v1.md   <-- Presentación ejecutiva oficial ante el Concejo Municipal
```

---

## Principios de la Información Presentada

1. **Autonomía y Validez:** Toda la información aquí contenida refleja el estado actual ("moment-in-time") de la estructuración del proyecto y está respaldada por actos administrativos, estudios primarios y certificaciones oficiales.
2. **Confidencialidad:** La información de este Data Room se comparte bajo acuerdos de estricta reserva con aliados e inversionistas de proyecto calificados.
3. **Verificabilidad:** Los actos administrativos y certificaciones incorporan sus respectivos códigos de verificación electrónica (CVS) y radicados oficiales ante el Municipio del Líbano.
