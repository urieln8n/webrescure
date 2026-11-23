# WEB RESCUE LAB v0.2
Visor de resultados JSON, no escáner. La web pública no tiene autenticación: solo usar datos ficticios o anonimizados. Descargar offline.html y abrir desde disco sin conexión para datos confidenciales. No se usan fetch, almacenamiento del navegador ni servicios externos. Los registros se toman como declaraciones del archivo; no se verifica su veracidad. La compatibilidad con el findings.json real aún requiere prueba. Admite arrays y las claves findings/hallazgos/results, ejes/axes/dimensions y algunas claves de nota. La demo es ficticia. Para PDF usar imprimir. Los filtros afectan la lista impresa. No incluir informes privados en el repositorio.

## Pruebas de normalización ejecutadas durante la creación
- PASS: demo
- PASS: classification unknown
- PASS: no invented risk
- PASS: array
- PASS: nested
- PASS: a eo only
- PASS: reject unknown
- PASS: reject invalid array
- PASS: preserve hostile text
- PASS: false positive

Pendiente: prueba de navegador, despliegue y archivo real.

## V0.2
Admite informes individuales y el contenedor GATE-4B con regraded, full.repositorio, full.propuesta y simulated. Distingue clasificación de resultado técnico. Muestra cobertura ponderada, recuentos y limitaciones sin inferir datos ausentes. Los escenarios se identifican como offline o simulación. Las pruebas de helpers con registros sintéticos de la estructura real: 12/12. Pendiente validación en Chromium con el archivo original y comprobación de cabeceras/despliegue. Para PDF, desmarcar encabezados y pies de página en el diálogo del navegador. No publicar informes de clientes.
