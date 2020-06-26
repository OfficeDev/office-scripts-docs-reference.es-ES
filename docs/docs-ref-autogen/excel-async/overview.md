---
title: Referencia de API de scripts de Office
description: Información general sobre las API de JavaScript asincrónicas de scripts de Office.
ms.date: 06/17/2020
ms.openlocfilehash: b9fa59764b7cb54567adbe05b9671bae9b232972
ms.sourcegitcommit: 163b26a43411ad7f13a01237efe9b8d6de656b47
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 06/25/2020
ms.locfileid: "44887955"
---
# <a name="office-scripts-async-api-reference"></a>Referencia de API asincrónica de scripts de Office

La API asincrónica de scripts de Office admite scripts antiguos realizados durante la fase de vista previa de scripts de Office. Use esta documentación de referencia para obtener más información sobre las clases, los métodos y otros tipos usados por estos scripts antiguos. Todos los objetos a los que se puede tener acceso mediante scripts de Office se encuentran en la tabla de contenido a la izquierda de la página.

> [!IMPORTANT]
> Se recomienda encarecidamente crear scripts nuevos con las API de scripts estándar de Office. Si está realizando o modificando un nuevo script, cambie a la [versión no asincrónica](?view=office-scripts) de las API.

## <a name="common-classes"></a>Clases comunes

En la siguiente lista se desglosan los conceptos básicos del modelo de objetos de scripts de Office. Se muestran las clases comunes y el modo en que se relacionan entre sí.

- Un [libro](/javascript/api/office-scripts/excel/excelscript.workbook) contiene una o varias [hojas de cálculo](/javascript/api/office-scripts/excel/excelscript.worksheet) en un [WorksheetCollection](/javascript/api/office-scripts/excel/excelscript.worksheetcollection).
- Una [Hoja de cálculo](/javascript/api/office-scripts/excel/excelscript.worksheet) proporciona acceso a las celdas mediante objetos de [Rango](/javascript/api/office-scripts/excel/excelscript.range).
- Un [Rango](/javascript/api/office-scripts/excel/excelscript.range) representa un grupo de celdas adyacentes.
- Los [Rangos](/javascript/api/office-scripts/excel/excelscript.range) se usan para crear y colocar [Tablas](/javascript/api/office-scripts/excel/excelscript.table), [Gráficos](/javascript/api/office-scripts/excel/excelscript.chart), [Formas](/javascript/api/office-scripts/excel/excelscript.shape) y otros objetos de visualización u organización de datos.
- Una [hoja de cálculo](/javascript/api/office-scripts/excel/excelscript.worksheet) contiene colecciones de los objetos de datos (como un [ChartCollection](/javascript/api/office-scripts/excel/excelscript.chartcollection)) que están presentes en la hoja individual.
- Los [libros](/javascript/api/office-scripts/excel/excelscript.workbook) contienen colecciones de algunos de los objetos de datos (como un [TableCollection](/javascript/api/office-scripts/excel/excelscript.tablecollection)) para todo el [libro](/javascript/api/office-scripts/excel/excelscript.workbook).

Para obtener más información sobre el modelo de objetos de scripts de Office, visite [conceptos básicos de scripting para scripts de Office en Excel en la web](/office/dev/scripts/develop/scripting-fundamentals)

## <a name="see-also"></a>Vea también

- [Uso de las API asincrónicas de scripts de Office para admitir scripts heredados](/office/dev/scripts/develop/excel-async-model)
- [Acerca de los scripts de Office](/office/dev/scripts/overview/excel)
- [Grabar, editar y crear scripts de Office en Excel en la Web](/office/dev/scripts/tutorials/excel-tutorial)
- [Conceptos básicos de los scripts de Office en Excel en la Web](/office/dev/scripts/develop/scripting-fundamentals)
