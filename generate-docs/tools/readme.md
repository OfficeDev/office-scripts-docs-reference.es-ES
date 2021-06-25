# <a name="office-scripts-api-documentation-tools"></a>Office Herramientas de documentación de api de scripts

Estas herramientas ayudan a admitir la Office de SCripts y el equipo detrás de ella. Siga estas instrucciones para ejecutar las herramientas de esta carpeta.

## <a name="coverage-tester"></a>coverage-tester

Esta herramienta proporciona información general sobre la cobertura de documentación de cada API. Cada API se evalúa para la calidad de la documentación y la presencia de código de ejemplo. Las métricas de calidad aún están en desarrollo.

El resultado de esta herramienta es un `.csv` archivo.

### <a name="coverage-tester-instructions"></a>Instrucciones del evaluador de cobertura

1. Clone o bifurca el repositorio.
1. En una ventana de comandos, vaya a `/office-scripts-docs-reference/generate-docs/tools`
1. Ejecutar `npm install`
1. Ejecutar `npm run build`
1. Ejecutar `node coverage-tester`
1. Abra "Api Coverage Report.csv"
