BDGD Coordinate Extractor

Script em Python para extrair coordenadas geográficas (latitude e longitude) de elementos da BDGD (Base de Dados Geográfica da Distribuidora) a partir de arquivos no formato shapefile.
O código utiliza a biblioteca GeoPandas para ler a camada e recuperar as coordenadas correspondentes ao atributo COD_ID.

Este utilitário é útil para operações de análise espacial, estudos de perdas técnicas, inspeção de transformadores, validação de bases e integração com ferramentas como OpenDSS, ArcGIS, QGIS e painéis de geoprocessamento.

Instale as dependências:

pip install geopandas
pip install shapely
