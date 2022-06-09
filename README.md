# Filtro eBird para IBAs
Este código simple permite filtrar la base de datos de eBird y resumir la información regustrada en el área geográfica de un Important Bird Area (IBA) de interés.

Para correr este código se requieren de tres archivos.
1) El [eBird Basic Dasaset](https://ebird.org/science/use-ebird-data/download-ebird-data-products) (EBD) que se puede solicitar en el siguiente [link](https://ebird.org/data/download). La base de datos es gratuita, solo es necesario rellenar un formulario detallando el motivo para el cual uno lo quiere usar. 
2) El polígono de la Important Bird Area. Este código acepta archivos en formato .shp o .kml
3) Un archivo adicional con las categorias de conservacion de las especies posibles en el área (opcional)

Este ejemplo lo desarrollé de parte de la Red de Observadores de Aves y Vida Silvestre de Chile [(ROC)](http://www.redobservadores.cl) como una herrmienta para el partner de Birdlife en Chile.


**Items aún por desarrollar:**
- Columna que indica en cuantos de los ultimos 5 años hubo por lo menos un registro
- Columna con tasa de encuentro relativa
