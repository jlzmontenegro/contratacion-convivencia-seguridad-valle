# Contratación · Secretaría de Convivencia y Seguridad Ciudadana · Valle del Cauca

Tablero interactivo de la contratación de la Secretaría de Convivencia y Seguridad Ciudadana de la Gobernación del Valle del Cauca, desde el 1 de enero de 2024.

**Ver el tablero:** https://jlzmontenegro.github.io/contratacion-convivencia-seguridad-valle/

## Qué incluye

- Resumen, indicadores y gráficos que se leen por valor contratado, por número de contratos o en porcentaje: categorías de gasto, proyecto de inversión, top 15 de contratistas, año, estado, modalidad, tipo de contrato y origen de los recursos.
- Filtros que se combinan (varios valores por filtro) y gráficos que filtran al hacer clic.
- Tabla con columnas a elección, orden por cualquier columna, enlace a cada proceso en SECOP II y exportación a CSV y PDF.

## Datos

- **Fuente:** SECOP II · Contratos Electrónicos (`jbjy-vk9h`) en datos.gov.co, filtrado por el nombre exacto de la entidad (`GOBERNACION DEL VALLE - SECRETARIA DE CONVIVENCIA Y SEGURIDAD CIUDADANA`), no por el NIT, que comparten todas las dependencias de la Gobernación.
- Se excluyen los contratos en Borrador o Cancelado y se deja una sola fila por contrato. Los contratos enviados al contratista y aún sin firmar se listan aparte y no suman.
- Cobertura verificada contra SECOP Integrado (`rpmr-utcd`) y los procesos de SECOP II (`p6dx-8zbt`).
- La página consulta la API al abrirse y se actualiza sola; si no hay conexión usa `datos.js`.
