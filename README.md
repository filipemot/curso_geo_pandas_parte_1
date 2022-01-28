
# GeoPandas Parte 1: Trabalhando com dados Geoespaciais - Alura - 2021  
  
Link do Curso: [https://cursos.alura.com.br/course/geopandas-dados-geoespaciais](https://cursos.alura.com.br/course/geopandas-dados-geoespaciais)
  
**Instalação:**  

- pip install wheel
- pip install pipwin

- pipwin install numpy
- pipwin install pandas
- pipwin install shapely
- pipwin install gdal
- pipwin install fiona
- pipwin install pyproj
- pipwin install six
- pipwin install rtree
- pipwin install geopandas

**Instalação Anaconda:**  

- conda config --add channels conda-forge
- conda config --add channels defaults
- conda create -n test_python python=3.9 geopandas
- conda activate test_python
- conda install -c anaconda ipykernel
- python -m ipykernel install --user --name=test_python

**Execução**
Jupyter.bat
  
**Aulas:**  
  
- [X] 01 - Introdução ao GeoPandas  
  
- [X] 02 - Do DataFrame ao GeoDataFrame  
  
- [X] 03 - Sistemas de coordenadas  
  
- [X] 04 - Filtrando imóveis por região  
  
- [X] 05 - Calculando distâncias  
  
- [ ] 06 - Agregando outras localizações

**Conteúdos Aprendidos:**  

- Uma introdução ao GeoPandas
  - Como instalá-lo
  - O seu funcionamento
- Como iniciar o Jupyter em uma pasta diferente da pasta do Anaconda
- Como plotar um mapa
- Os shapes Polygon, Point, LineString e MultiPolygon
- Shapefiles
	- Como lê-los, modificá-los e salvá-los
- Coordenadas de latitude e longitude
- Como transformar um DataFrame em GeoDataFrame
- O sistema de referência de coordenadas
	- Projeções
	- Elipses
	- Datum
	- Universal Transverse Mercator (UTM)
- Como modificar o sistema de coordenadas
- Como identificar os outliers
- Como selecionar pontos (dados) dentro de uma região
- Como importar os dados das estações para um DataFrame
- Como agrupar os dados das estações de metrô aos dados do município do Rio de Janeiro e dos imóveis
- Como calcular a distância de cada imóvel até a estação de metrô mais próxima