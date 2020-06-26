---
title: Referencia de API de scripts de Office
description: Información general sobre las API de JavaScript de scripts de Office.
ms.date: 06/17/2020
ms.openlocfilehash: 5634d0e5f68464655054ad1c09eb7931e0da62d4
ms.sourcegitcommit: 163b26a43411ad7f13a01237efe9b8d6de656b47
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 06/25/2020
ms.locfileid: "44884835"
---
# <a name="office-scripts-api-reference"></a>Referencia de API de scripts de Office

La API de scripts de Office permite automatizar tareas comunes en Excel en la Web. Use esta documentación de referencia para obtener más información sobre las clases, métodos y otros tipos disponibles para los scripts. Todos los objetos a los que se puede tener acceso mediante scripts de Office se encuentran en la tabla de contenido a la izquierda de la página.

> [!NOTE]
> Si está buscando las API de JavaScript para desarrollar complementos de Office, visite la referencia de la API de JavaScript de los [Complementos de Office](/javascript/api/overview?view=excel-js-preview).

## <a name="common-classes"></a>Clases comunes

En la siguiente lista se desglosan los conceptos básicos del modelo de objetos de scripts de Office. Se muestran las clases comunes y el modo en que se relacionan entre sí.

- Un [Libro](/javascript/api/office-scripts/excel/excelscript.workbook) contiene una o varias [Hojas de cálculo](/javascript/api/office-scripts/excel/excelscript.worksheet).
- Una [Hoja de cálculo](/javascript/api/office-scripts/excel/excelscript.worksheet) proporciona acceso a las celdas mediante objetos de [Rango](/javascript/api/office-scripts/excel/excelscript.range).
- Un [Rango](/javascript/api/office-scripts/excel/excelscript.range) representa un grupo de celdas adyacentes.
- Los [Rangos](/javascript/api/office-scripts/excel/excelscript.range) se usan para crear y colocar [Tablas](/javascript/api/office-scripts/excel/excelscript.table), [Gráficos](/javascript/api/office-scripts/excel/excelscript.chart), [Formas](/javascript/api/office-scripts/excel/excelscript.shape) y otros objetos de visualización u organización de datos.
- Una [hoja de cálculo](/javascript/api/office-scripts/excel/excelscript.worksheet) contiene matrices rellenas con los objetos que están presentes en la hoja individual.
- Un [libro](/javascript/api/office-scripts/excel/excelscript.workbook) contiene matrices de algunos de esos objetos de datos para todo el libro.

Para obtener más información sobre el modelo de objetos de scripts de Office, visite [conceptos básicos de scripting para scripts de Office en Excel en la web](/office/dev/scripts/develop/scripting-fundamentals)

## <a name="see-also"></a>Vea también

- [Acerca de los scripts de Office](/office/dev/scripts/overview/excel)
- [Grabar, editar y crear scripts de Office en Excel en la Web](/office/dev/scripts/tutorials/excel-tutorial)
- [Conceptos básicos de los scripts de Office en Excel en la Web](/office/dev/scripts/develop/scripting-fundamentals)
