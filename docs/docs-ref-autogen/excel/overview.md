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
# <a name="office-scripts-api-reference"></a><span data-ttu-id="3c3d3-103">Referencia de API de scripts de Office</span><span class="sxs-lookup"><span data-stu-id="3c3d3-103">Office Scripts API reference</span></span>

<span data-ttu-id="3c3d3-104">La API de scripts de Office permite automatizar tareas comunes en Excel en la Web.</span><span class="sxs-lookup"><span data-stu-id="3c3d3-104">The Office Scripts API lets you automate common tasks in Excel on the web.</span></span> <span data-ttu-id="3c3d3-105">Use esta documentación de referencia para obtener más información sobre las clases, métodos y otros tipos disponibles para los scripts.</span><span class="sxs-lookup"><span data-stu-id="3c3d3-105">Use this reference documentation to learn more about the classes, methods, and other types available for your scripts.</span></span> <span data-ttu-id="3c3d3-106">Todos los objetos a los que se puede tener acceso mediante scripts de Office se encuentran en la tabla de contenido a la izquierda de la página.</span><span class="sxs-lookup"><span data-stu-id="3c3d3-106">All the objects accessible through Office Scripts can be found in the table of contents on the left of the page.</span></span>

> [!NOTE]
> <span data-ttu-id="3c3d3-107">Si está buscando las API de JavaScript para desarrollar complementos de Office, visite la referencia de la API de JavaScript de los [Complementos de Office](/javascript/api/overview?view=excel-js-preview).</span><span class="sxs-lookup"><span data-stu-id="3c3d3-107">If you're looking for the JavaScript APIs for developing Office Add-ins, visit the [Office Add-ins JavaScript API reference](/javascript/api/overview?view=excel-js-preview).</span></span>

## <a name="common-classes"></a><span data-ttu-id="3c3d3-108">Clases comunes</span><span class="sxs-lookup"><span data-stu-id="3c3d3-108">Common classes</span></span>

<span data-ttu-id="3c3d3-109">En la siguiente lista se desglosan los conceptos básicos del modelo de objetos de scripts de Office.</span><span class="sxs-lookup"><span data-stu-id="3c3d3-109">The following list breaks down the basics of the Office Scripts object model.</span></span> <span data-ttu-id="3c3d3-110">Se muestran las clases comunes y el modo en que se relacionan entre sí.</span><span class="sxs-lookup"><span data-stu-id="3c3d3-110">This shows the common classes and how they relate to one another.</span></span>

- <span data-ttu-id="3c3d3-111">Un [Libro](/javascript/api/office-scripts/excel/excelscript.workbook) contiene una o varias [Hojas de cálculo](/javascript/api/office-scripts/excel/excelscript.worksheet).</span><span class="sxs-lookup"><span data-stu-id="3c3d3-111">A [Workbook](/javascript/api/office-scripts/excel/excelscript.workbook) contains one or more [Worksheets](/javascript/api/office-scripts/excel/excelscript.worksheet).</span></span>
- <span data-ttu-id="3c3d3-112">Una [Hoja de cálculo](/javascript/api/office-scripts/excel/excelscript.worksheet) proporciona acceso a las celdas mediante objetos de [Rango](/javascript/api/office-scripts/excel/excelscript.range).</span><span class="sxs-lookup"><span data-stu-id="3c3d3-112">A [Worksheet](/javascript/api/office-scripts/excel/excelscript.worksheet) gives access to cells through [Range](/javascript/api/office-scripts/excel/excelscript.range) objects.</span></span>
- <span data-ttu-id="3c3d3-113">Un [Rango](/javascript/api/office-scripts/excel/excelscript.range) representa un grupo de celdas adyacentes.</span><span class="sxs-lookup"><span data-stu-id="3c3d3-113">A [Range](/javascript/api/office-scripts/excel/excelscript.range) represents a group of contiguous cells.</span></span>
- <span data-ttu-id="3c3d3-114">Los [Rangos](/javascript/api/office-scripts/excel/excelscript.range) se usan para crear y colocar [Tablas](/javascript/api/office-scripts/excel/excelscript.table), [Gráficos](/javascript/api/office-scripts/excel/excelscript.chart), [Formas](/javascript/api/office-scripts/excel/excelscript.shape) y otros objetos de visualización u organización de datos.</span><span class="sxs-lookup"><span data-stu-id="3c3d3-114">[Ranges](/javascript/api/office-scripts/excel/excelscript.range) are used to create and place [Tables](/javascript/api/office-scripts/excel/excelscript.table), [Charts](/javascript/api/office-scripts/excel/excelscript.chart), [Shapes](/javascript/api/office-scripts/excel/excelscript.shape), and other data visualization or organization objects.</span></span>
- <span data-ttu-id="3c3d3-115">Una [hoja de cálculo](/javascript/api/office-scripts/excel/excelscript.worksheet) contiene matrices rellenas con los objetos que están presentes en la hoja individual.</span><span class="sxs-lookup"><span data-stu-id="3c3d3-115">A [Worksheet](/javascript/api/office-scripts/excel/excelscript.worksheet) contains arrays filled with those objects that are present in the individual sheet.</span></span>
- <span data-ttu-id="3c3d3-116">Un [libro](/javascript/api/office-scripts/excel/excelscript.workbook) contiene matrices de algunos de esos objetos de datos para todo el libro.</span><span class="sxs-lookup"><span data-stu-id="3c3d3-116">A [Workbook](/javascript/api/office-scripts/excel/excelscript.workbook) contains arrays of some of those data objects for the entire Workbook.</span></span>

<span data-ttu-id="3c3d3-117">Para obtener más información sobre el modelo de objetos de scripts de Office, visite [conceptos básicos de scripting para scripts de Office en Excel en la web](/office/dev/scripts/develop/scripting-fundamentals)</span><span class="sxs-lookup"><span data-stu-id="3c3d3-117">For more information about the Office Scripts object model, visit [Scripting fundamentals for Office Scripts in Excel on the web](/office/dev/scripts/develop/scripting-fundamentals)</span></span>

## <a name="see-also"></a><span data-ttu-id="3c3d3-118">Vea también</span><span class="sxs-lookup"><span data-stu-id="3c3d3-118">See also</span></span>

- [<span data-ttu-id="3c3d3-119">Acerca de los scripts de Office</span><span class="sxs-lookup"><span data-stu-id="3c3d3-119">About Office Scripts</span></span>](/office/dev/scripts/overview/excel)
- [<span data-ttu-id="3c3d3-120">Grabar, editar y crear scripts de Office en Excel en la Web</span><span class="sxs-lookup"><span data-stu-id="3c3d3-120">Record, edit, and create Office Scripts in Excel on the web</span></span>](/office/dev/scripts/tutorials/excel-tutorial)
- [<span data-ttu-id="3c3d3-121">Conceptos básicos de los scripts de Office en Excel en la Web</span><span class="sxs-lookup"><span data-stu-id="3c3d3-121">Scripting fundamentals for Office Scripts in Excel on the web</span></span>](/office/dev/scripts/develop/scripting-fundamentals)
