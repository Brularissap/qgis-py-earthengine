<h1> QGIS | PYTHON | GEE</h1>

<p>
<img src="http://img.shields.io/static/v1?label=STATUS&message=EM%20DESENVOLVIMENTO&color=GREEN&style=for-the-badge"/>
</p>

<h2>Introdução</h2>
Este repositório trata de exemplos de aplicações em python no QGIS com consulta ao Google Earth Engine.

<h2>QGIS </h2>

É necessário <a href="https://www.qgis.org/pt_BR/site/forusers/download.html">instalar</a> o software <a href="https://www.qgis.org/pt_BR/site/forusers/download.html">QGIS</a> em sua máquina.

```
https://www.qgis.org/pt_BR/site/forusers/download.html
```
<p align="center">
<img src="https://github.com/Brularissap/qgis-py-earthengine/blob/main/download-qgis.gif?raw=true"/>
</p>


<h2>PYTHON</h2>
A linguagem Python será implementada no <b>Terminal Python</b>, dentro do QGIS, que pode ser acessado com as seguintes teclas de atalho:

```
Ctrl + Alt + P
```

<p align="center">
<img src="https://github.com/Brularissap/qgis-py-earthengine/blob/main/Terminal-Python.gif?raw=true"/>
</p>

<b>OBS:</B> Você precisa ter conhecimento prévio da linguagem Python. 

Experimente <b>GRATUITAMENTE</b> o curso <a href="https://pt.coursera.org/learn/ciencia-computacao-python-conceitos?">Introdução à Ciência da Computação com Python Parte 1</a> que está disponível em:

```
https://pt.coursera.org/learn/ciencia-computacao-python-conceitos?
```

![coursera curso](https://github.com/Brularissap/qgis-py-earthengine/blob/main/coursera_usp_python.jpg?raw=true)


<h2> GEE</h2>

Para que um script, presente neste repositório, rode em sua máquina, por favor registre-se em:

```
https://code.earthengine.google.com/register
```

<p align="center">
<img src="https://github.com/Brularissap/qgis-py-earthengine/blob/main/registre-se-gee.gif?raw=true"/>
</p>

Dentro do QGIS é necessário instalar o Plugin Google Earth Engine e você pode fazer isso na aba Complementos/Gerenciar e Instalar Complementos.

<p align="center">
<img src="https://github.com/Brularissap/qgis-py-earthengine/blob/main/Plugin%20-%20GEE.gif?raw=true"/>
</p>

<h2>Exemplo: Consultar imagens Sentine-2 no QGIS</h2>

O arquivo <a href="https://github.com/Brularissap/qgis-py-earthengine/blob/main/add_Sentinel_2.py.py">add_Sentinel_2.py.py</a> diz respeito a busca por imagens
Sentinel 2 da coleção ee.ImageCollection("COPERNICUS/S2_SR"), presente no GEE.
Essa busca ocorre dentro do QGIS, através do terminal python e utilizando o plugin Google Earth Engine.

<b>O que acontece?</b>

Os códigos deste arquivo irão consultar o Earth Engine em busca das imagens de acordo com o que está sendo filtrado
da coleção. 
Se encontrar alguma imagem ela será adicionada como uma camada no QGIS e poderá ser visualizada. 
Um dos filtros aplicados para esta ImageCollection refere-se ao percentual de nuvem menor que 10%, com isto, após rodar o arquivo, é posível visualizar no console a data da imagem encontrada e o seu percentual de nuvem. <b>Centralize, em um basemap, a sua área de interesse antes de rodar o arquivo no terminal.</b>

![Giff_add_Sentinel_2 py](https://raw.githubusercontent.com/Brularissap/qgis-py-earthengine/main/Giff_add_Sentinel_2.py.gif) 

<h2>Pratique na sua máquina</h2>
Agora que concluiu as estapas acima, você já pode copiar ou baixar os códigos deste repositório e aplicar dentro do terminal python do seu QGIS.




