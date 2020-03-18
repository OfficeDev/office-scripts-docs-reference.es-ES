---
title: Referencia de la API de scripts de Office
description: Información general sobre las API de JavaScript de scripts de Office
ms.date: 12/12/2019
ms.openlocfilehash: b3e75cbecac13f41c83f019c681b0682571ead41
ms.sourcegitcommit: 2834ee43a14a4b0953d5fb22749c115a42960e20
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 03/10/2020
ms.locfileid: "42705946"
---
# <a name="office-scripts-api-reference"></a>Referencia de la API de scripts de Office

La API de scripts de Office permite automatizar tareas comunes en Excel en la Web. Use esta documentación de referencia para obtener más información sobre las clases, métodos y otros tipos disponibles para los scripts. Todos los objetos a los que se puede tener acceso mediante scripts de Office se encuentran en la tabla de contenido a la izquierda de la página.

## <a name="common-classes"></a>Clases comunes

En la siguiente lista se desglosan los conceptos básicos del modelo de objetos de scripts de Office. Se muestran las clases comunes y el modo en que se relacionan entre sí.

- Un [libro](/javascript/api/office-scripts/excel/excel.workbook) contiene una o varias [hojas de cálculo](/javascript/api/office-scripts/excel/excel.worksheet) en un [WorksheetCollection](/javascript/api/office-scripts/excel/excel.worksheetcollection).
- Una [hoja de cálculo](/javascript/api/office-scripts/excel/excel.worksheet) da acceso a celdas a través de objetos [Range](/javascript/api/office-scripts/excel/excel.range) .
- Un [rango](/javascript/api/office-scripts/excel/excel.range) representa un grupo de celdas contiguas.
- Los [rangos](/javascript/api/office-scripts/excel/excel.range) se usan para crear y colocar [tablas](/javascript/api/office-scripts/excel/excel.table), [gráficos](/javascript/api/office-scripts/excel/excel.chart), [formas](/javascript/api/office-scripts/excel/excel.shape)y otros objetos de visualización o de organización de datos.
- Una [hoja de cálculo](/javascript/api/office-scripts/excel/excel.worksheet) contiene colecciones de los objetos de datos (como un [ChartCollection](/javascript/api/office-scripts/excel/excel.chartcollection)) que están presentes en la hoja individual.
- [Libros](/javascript/api/office-scripts/excel/excel.workbook). contienen colecciones de algunos de esos objetos de datos (como un [TableCollection](/javascript/api/office-scripts/excel/excel.tablecollection)) para todo el [libro](/javascript/api/office-scripts/excel/excel.workbook).

Para obtener más información sobre el modelo de objetos de scripts de Office, visite [conceptos básicos de scripting para scripts de Office en Excel en la web](/office/dev/scripts/develop/scripting-fundamentals)

## <a name="see-also"></a>Vea también

- [Acerca de los scripts de Office](/office/dev/scripts/overview/excel)
- [Grabar, editar y crear scripts de Office en Excel en la web](/office/dev/scripts/tutorials/excel-tutorial)
- [Conceptos básicos sobre el scripting de los scripts de Office en Excel en la web](/office/dev/scripts/develop/scripting-fundamentals)
