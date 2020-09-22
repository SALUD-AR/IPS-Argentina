# Resumen Electrónico de Historia Clínica

En el contexto de la [Estrategia Nacional de Salud Digital](https://www.argentina.gob.ar/noticias/se-aprobo-la-estrategia-nacional-de-salud-digital-2018-2024) que lleva cabo el Ministerio de Salud de la Nación en Argentina, se implementa la Red Nacional de Interoperabilidad que va a permitir la comunicación de información sanitaria entre instituciones de salud, en forma segura y privada.

El grupo de trabajo para la implementación del resumen de historia clínica electrónica esta diseñando y piloteando la transferencia de información basada en el estándar internacional [IPS (Internacional Patient Summary)](http://wiki.hl7.org/index.php?title=International_Patient_Summary_(IPS)) y [HL7 FHIR](https://www.hl7.org/fhir/).

Este repositorio es un area de trabajo de este grupo y contiene versiones de prueba del estándar propuesto.

## Demo

Este es un visor de resúmenes de paciente IPS compatibles.

https://salud-ar.github.io/IPS-Argentina/demo.html

## Piloto

Durante la etapa piloto de la implementación del resumen de Historia Clínica Electrónica se han priorizado la siguiente lista de componentes:

1. Alergias
2. Lista de problemas o diagnósticos activos
3. Inmunizaciones
4. Medicación

Todos los elementos clínicos, alergias, diagnósticos, vacunas y medicamentos se codifican con códigos de la [edición argentina de SNOMED CT](https://www.argentina.gob.ar/salud/snomed).

## Más información

Las definiciones formales de los estándares de interoperabilidad se publicarán en el sitio de documentación del proyecto de salud digital:

https://simplifier.net/SaludDigital.ar

