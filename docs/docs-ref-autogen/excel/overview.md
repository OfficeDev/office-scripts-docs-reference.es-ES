---
title: Referencia de API de scripts de Office
description: Una introducción a las API de JavaScript Office scripts.
ms.date: 06/29/2020
ms.openlocfilehash: b9ac5b191dbbb72301fc1f4fe11c81bd2b45ae17
ms.sourcegitcommit: dfc12de9e6eb5de71199b36f92ce93039509ad37
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 03/23/2022
ms.locfileid: "63755994"
---
# <a name="office-scripts-api-reference"></a>Referencia de API de scripts de Office

La API Office scripts le permite automatizar tareas comunes en Excel en la Web. Use esta documentación de referencia para obtener más información sobre las clases, métodos y otros tipos disponibles para los scripts. Todos los objetos accesibles a Office scripts se pueden encontrar en la tabla de contenido de la izquierda de la página.

> [!NOTE]
> Si está buscando las API de JavaScript para desarrollar complementos Office, visite la referencia de la [API de JavaScript](/javascript/api/overview?view=excel-js-preview&preserve-view=true) de Office complementos.

## <a name="common-classes"></a>Clases comunes

En la siguiente lista se desglosan los conceptos básicos del Office de objetos scripts. Esto muestra las clases comunes y cómo se relacionan entre sí.

- Un [Libro](/javascript/api/office-scripts/excelscript/excelscript.workbook) contiene una o varias [Hojas de cálculo](/javascript/api/office-scripts/excelscript/excelscript.worksheet).
- Una [Hoja de cálculo](/javascript/api/office-scripts/excelscript/excelscript.worksheet) proporciona acceso a las celdas mediante objetos de [Rango](/javascript/api/office-scripts/excelscript/excelscript.range).
- Un [Rango](/javascript/api/office-scripts/excelscript/excelscript.range) representa un grupo de celdas adyacentes.
- Los [Rangos](/javascript/api/office-scripts/excelscript/excelscript.range) se usan para crear y colocar [Tablas](/javascript/api/office-scripts/excelscript/excelscript.table), [Gráficos](/javascript/api/office-scripts/excelscript/excelscript.chart), [Formas](/javascript/api/office-scripts/excelscript/excelscript.shape) y otros objetos de visualización u organización de datos.
- Una [hoja](/javascript/api/office-scripts/excelscript/excelscript.worksheet) de cálculo contiene matrices rellenas con los objetos que están presentes en la hoja individual.
- Un [libro](/javascript/api/office-scripts/excelscript/excelscript.workbook) contiene matrices de algunos de esos objetos de datos para todo el libro.

Para obtener más información acerca del Office de objetos scripts, visite [Scripting fundamentals for Office Scripts in Excel en la Web](/office/dev/scripts/develop/scripting-fundamentals)

## <a name="see-also"></a>Vea también

- [Acerca Office scripts](/office/dev/scripts/overview/excel)
- [Grabar, editar y crear Scripts de Office en Excel para la Web](/office/dev/scripts/tutorials/excel-tutorial)
- [Conceptos básicos de los Scripts de Office en Excel en la web](/office/dev/scripts/develop/scripting-fundamentals)
