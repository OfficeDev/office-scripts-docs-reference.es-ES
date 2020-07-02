---
title: Referencia de API de scripts de Office
description: Información general sobre las API de JavaScript asincrónicas de scripts de Office.
ms.date: 06/29/2020
ms.openlocfilehash: 3d8d37b30d9535e8b6a56a08c44f9034cb599f31
ms.sourcegitcommit: 9c4c4c213a203e58c55eb3d84d7d92fa527f3eb8
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 07/01/2020
ms.locfileid: "45003957"
---
# <a name="office-scripts-async-api-reference"></a>Referencia de API asincrónica de scripts de Office

La API asincrónica de scripts de Office admite scripts antiguos realizados durante la fase de vista previa de scripts de Office. Use esta documentación de referencia para obtener más información sobre las clases, los métodos y otros tipos usados por estos scripts antiguos. Todos los objetos a los que se puede tener acceso mediante scripts de Office se encuentran en la tabla de contenido a la izquierda de la página.

> [!IMPORTANT]
> Se recomienda encarecidamente crear scripts nuevos con las API de scripts estándar de Office. Si está realizando o modificando un nuevo script, cambie a la [versión no asincrónica](?view=office-scripts) de las API.

## <a name="common-classes"></a>Clases comunes

En la siguiente lista se desglosan los conceptos básicos del modelo de objetos de scripts de Office. Se muestran las clases comunes y el modo en que se relacionan entre sí.

- Un [libro](/javascript/api/office-scripts/excelscript/excelscript.workbook) contiene una o varias [hojas de cálculo](/javascript/api/office-scripts/excelscript/excelscript.worksheet) en un [WorksheetCollection](/javascript/api/office-scripts/excelscript/excelscript.worksheetcollection).
- Una [Hoja de cálculo](/javascript/api/office-scripts/excelscript/excelscript.worksheet) proporciona acceso a las celdas mediante objetos de [Rango](/javascript/api/office-scripts/excelscript/excelscript.range).
- Un [Rango](/javascript/api/office-scripts/excelscript/excelscript.range) representa un grupo de celdas adyacentes.
- Los [Rangos](/javascript/api/office-scripts/excelscript/excelscript.range) se usan para crear y colocar [Tablas](/javascript/api/office-scripts/excelscript/excelscript.table), [Gráficos](/javascript/api/office-scripts/excelscript/excelscript.chart), [Formas](/javascript/api/office-scripts/excelscript/excelscript.shape) y otros objetos de visualización u organización de datos.
- Una [hoja de cálculo](/javascript/api/office-scripts/excelscript/excelscript.worksheet) contiene colecciones de los objetos de datos (como un [ChartCollection](/javascript/api/office-scripts/excelscript/excelscript.chartcollection)) que están presentes en la hoja individual.
- Los [libros](/javascript/api/office-scripts/excelscript/excelscript.workbook) contienen colecciones de algunos de los objetos de datos (como un [TableCollection](/javascript/api/office-scripts/excelscript/excelscript.tablecollection)) para todo el [libro](/javascript/api/office-scripts/excelscript/excelscript.workbook).

Para obtener más información sobre el modelo de objetos de scripts de Office, visite [conceptos básicos de scripting para scripts de Office en Excel en la web](/office/dev/scripts/develop/scripting-fundamentals)

## <a name="see-also"></a>Ver también

- [Uso de las API asincrónicas de scripts de Office para admitir scripts heredados](/office/dev/scripts/develop/excel-async-model)
- [Acerca de los scripts de Office](/office/dev/scripts/overview/excel)
- [Grabar, editar y crear scripts de Office en Excel en la Web](/office/dev/scripts/tutorials/excel-tutorial)
- [Conceptos básicos de los scripts de Office en Excel en la Web](/office/dev/scripts/develop/scripting-fundamentals)
