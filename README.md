# DigitalTwins
Este repositorio contiene información sobre como iniciar en Azure Digital Twins 

# Requisitos
- Tener una cuenta de Azure <link>https://portal.azure.com</link>

# Paso a seguir

## Paso 1: Crear el Servicio de Azure Digital Twins en Azure 
- Crear el servicio de Azure Digital Twins <link>https://docs.microsoft.com/es-es/azure/digital-twins/quickstart-azure-digital-twins-explorer</link>
## Paso 2: Descargar Azure Digital Twins Explorer  Repo 
- Descargar Repositorio de ejemplo: <link>https://github.com/azure-samples/digital-twins-explorer/tree/main/</link> o puedes usar el que se encuentre en este repositorio en la carpeta digital-twins-explorer (descargado el 21/05/2022)
## Paso 3: Iniciar o instalar Azure Digital Twins Explorer
### Opción 1: Iniciar Digital Explorer desde Azure 
![Alt text](/images/referencia_azure_digital_twins_explorer.png?raw=true)
### Opción 2: Instalar Azure Digital Twins Explorer
- Instalar Azure CLI y Activar cuenta de Azure <link>https://docs.microsoft.com/en-us/cli/azure/install-azure-cli-windows?tabs=azure-cli</link>
- Instalar Node JS  <link>https://nodejs.org/en/download/?WT.mc_id=other-azuredevtipsvideo-azureappsdev</link>
- Abrir un comando con la ruta digital-twins-explorer\client\src y ejecutar el comando *npm install* 
![Alt text](/images/npm_install.png)
- Ejecutar el comando *npm run start*
## Paso 4: Iniciar Digital Twins
- Copiar Host name de Azure Digital Twins
![Alt text](/images/ADT_Hostname_Azure.png)
- Pegar en Azure Digital Twins Explorer
![Alt text](/images/ADT_Hostname.png)

## Paso 5: Cargar Modelos
- En Azure Digital Twins Explorer ir a la pestaña *Models* y presionar en *Upload a Model* 
![Alt text](/images/load_models.png)
- Para importar los modelos seleccionar <span style="color:green">Floor.json</span> y <span style="color:green">Room.json</span>  de la carpeta digital-twins-explorer/client/examples
 texto azul 
![Alt text](/images/models_dir.png)

Vista de modelos cargados ![Alt text](/images/show_models.png)

- En Azure Digital Twins Explorer en la parte media presionar en *Import Graph* 
![Alt text](/images/import_graph.png)

- Para importar grafos seleccionar <span style="color:green">buildingScenario.xlsx </span> de la carpeta digital-twins-explorer/client/examples
![Alt text](/images/select_file_graph.png)

- Una vez cargada tendra una vista previa para validar si los datos son correctos de manera gráfica
![Alt text](/images/save_graph_imported.png)

- Al cargar para visualizar ejecutar el query por defecto <span style="color:blue"> SELECT * FROM digitaltwins <span>
![Alt text](/images/run_query_1.png)

- Para mostrar información presiona en uno de los circulos y mostrará los datos a la derecha
![Alt text](/images/show_info.png)

- Haciendo doble click sobre algunos de los datos podrá modificarlo 
![Alt text](/images/change_humidity_value.png)
- Luego presionar en el símbolo de guardar 
![Alt text](/images/save_changes.png)

# Recursos
- Precio <link>https://azure.microsoft.com/en-us/pricing/details/digital-twins/</link>

# Referencias
- Azure Digital Twins Explorer <link>https://docs.microsoft.com/es-mx/samples/azure-samples/digital-twins-explorer/digital-twins-explorer/?WT.mc_id=docs-azuredevtipsvideo-azureappsdev</link>
- Introducción a Azure Digital Twins <link>https://docs.microsoft.com/es-es/azure/digital-twins/quickstart-azure-digital-twins-explorer</link>
- Video para crear Azure Digital Twins <link>https://www.youtube.com/watch?v=F_6oUknixeY </link>