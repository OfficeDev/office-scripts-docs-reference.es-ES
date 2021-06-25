# <a name="office-scripts-api-documentation-tools"></a><span data-ttu-id="011b9-101">Office Herramientas de documentación de api de scripts</span><span class="sxs-lookup"><span data-stu-id="011b9-101">Office Scripts API Documentation Tools</span></span>

<span data-ttu-id="011b9-102">Estas herramientas ayudan a admitir la Office de SCripts y el equipo detrás de ella.</span><span class="sxs-lookup"><span data-stu-id="011b9-102">These tools help support the Office SCripts documentation and the team behind it.</span></span> <span data-ttu-id="011b9-103">Siga estas instrucciones para ejecutar las herramientas de esta carpeta.</span><span class="sxs-lookup"><span data-stu-id="011b9-103">Follow these instructions to run the tools in this folder.</span></span>

## <a name="coverage-tester"></a><span data-ttu-id="011b9-104">coverage-tester</span><span class="sxs-lookup"><span data-stu-id="011b9-104">coverage-tester</span></span>

<span data-ttu-id="011b9-105">Esta herramienta proporciona información general sobre la cobertura de documentación de cada API.</span><span class="sxs-lookup"><span data-stu-id="011b9-105">This tool gives an overview of the documentation coverage for each API.</span></span> <span data-ttu-id="011b9-106">Cada API se evalúa para la calidad de la documentación y la presencia de código de ejemplo.</span><span class="sxs-lookup"><span data-stu-id="011b9-106">Each API is assessed for documentation quality and the presence of sample code.</span></span> <span data-ttu-id="011b9-107">Las métricas de calidad aún están en desarrollo.</span><span class="sxs-lookup"><span data-stu-id="011b9-107">The quality metrics are still in development.</span></span>

<span data-ttu-id="011b9-108">El resultado de esta herramienta es un `.csv` archivo.</span><span class="sxs-lookup"><span data-stu-id="011b9-108">The output of this tool is a `.csv` file.</span></span>

### <a name="coverage-tester-instructions"></a><span data-ttu-id="011b9-109">Instrucciones del evaluador de cobertura</span><span class="sxs-lookup"><span data-stu-id="011b9-109">coverage-tester Instructions</span></span>

1. <span data-ttu-id="011b9-110">Clone o bifurca el repositorio.</span><span class="sxs-lookup"><span data-stu-id="011b9-110">Clone or fork the repo.</span></span>
1. <span data-ttu-id="011b9-111">En una ventana de comandos, vaya a `/office-scripts-docs-reference/generate-docs/tools`</span><span class="sxs-lookup"><span data-stu-id="011b9-111">In a command window, go to `/office-scripts-docs-reference/generate-docs/tools`</span></span>
1. <span data-ttu-id="011b9-112">Ejecutar `npm install`</span><span class="sxs-lookup"><span data-stu-id="011b9-112">Run `npm install`</span></span>
1. <span data-ttu-id="011b9-113">Ejecutar `npm run build`</span><span class="sxs-lookup"><span data-stu-id="011b9-113">Run `npm run build`</span></span>
1. <span data-ttu-id="011b9-114">Ejecutar `node coverage-tester`</span><span class="sxs-lookup"><span data-stu-id="011b9-114">Run `node coverage-tester`</span></span>
1. <span data-ttu-id="011b9-115">Abra "Api Coverage Report.csv"</span><span class="sxs-lookup"><span data-stu-id="011b9-115">Open “API Coverage Report.csv”</span></span>
