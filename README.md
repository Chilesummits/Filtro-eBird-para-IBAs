# Filtro eBird para IBAs
Este código simple permite filtrar la base de datos de eBird y resumir la información regustrada en el área geográfica de un Important Bird Area (IBA) de interés.

Para correr este código se requieren de tres archivos.
1) El [eBird Basic Dasaset](https://ebird.org/science/use-ebird-data/download-ebird-data-products) (EBD) que se puede solicitar en el siguiente [link](https://ebird.org/data/download). La base de datos es gratuita, solo es necesario rellenar un formulario detallando el motivo para el cual uno lo quiere usar. 
2) El [polígono](https://github.com/Chilesummits/Filtro-eBird-para-IBAs/blob/main/Bahia%20Coquimbo.kml) de la Important Bird Area. Este código acepta archivos en formato .shp o .kml
3) Un [archivo](https://github.com/Chilesummits/Filtro-eBird-para-IBAs/blob/main/Lista%20aves%20de%20chile.csv) adicional con las categorias de conservacion de las especies posibles en el área (opcional)

Este ejemplo lo desarrollé de parte de la Red de Observadores de Aves y Vida Silvestre de Chile [(ROC)](http://www.redobservadores.cl) como una herrmienta para el partner de Birdlife en Chile.


**Funcionalidades aún por desarrollar:**
- Columna que indica en cuantos de los ultimos 5 años hubo por lo menos un registro de la especie
- Columna de tasa relativa de encuentro
- Función para especificar un buffer que agranda el perimetro del polígono, para incluir listas adjacentes al área de interés
