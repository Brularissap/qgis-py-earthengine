<h1> QGIS | PYTHON | GEE</h1>

<p>
<img src="http://img.shields.io/static/v1?label=STATUS&message=EM%20DESENVOLVIMENTO&color=GREEN&style=for-the-badge"/>
</p>

<h2>Introdução</h2>

Este arquivo python diz respeito a busca por imagens
Sentinel 2 da coleção ee.ImageCollection("COPERNICUS/S2_SR"), presente no GEE.
Essa busca ocorre dentro do QGIS, através do terminal python e utilizando o plugin Google Earth Engine.

O que acontece?

Os códigos deste arquivo irão consultar o Earth Engine em busca das imagens de acordo com o que esta sendo filtrado
da coleção. Se encontrar alguma imagem ela será adicionada como uma camada no QGIS e poderá ser visualizada.
Algumas condições foram impostas, uma delas é que se não houver imagem para a data solicitada e com percentual de
cobertura de nuvem menor que 10% logo aparecerá no terminal a seguinte mensagem:
NÃO TEM IMAGEM.
Deste modo, basta voce alterar as datas ou o percentual de nuvem.
Centralize, em um basemap, a sua área de interesse antes de rodar o arquivo no terminal.

<h2>QGIS </h2>

É necessário <a href="https://www.qgis.org/pt_BR/site/forusers/download.html">instalar</a> o software <a href="https://www.qgis.org/pt_BR/site/forusers/download.html">QGIS</a> em sua máquina.

```
https://www.qgis.org/pt_BR/site/forusers/download.html
```


<h2>PYTHON</h2>
A linguagem Python será implementada no Terminal Python, dentro do QGIS, que pode ser acessado com as seguintes teclas de atalho:

```
Ctrl + Alt + P
```

Você precisa ter conhecimento prévio da linguagem Python. 

Experimente GRATUITAMENTE o curso Introdução à Ciência da Computação com Python Parte 1 que está disponível em:

```
https://pt.coursera.org/learn/ciencia-computacao-python-conceitos?
```

<h2> GEE</h2>

Para que um script, presente neste repositório, rode em sua máquina, por favor registre-se em:

```
https://code.earthengine.google.com/register
```

Dentro do QGIS é necessário instalar o Plugin Google Earth Engine e você pode fazer isso na aba complementos.

<p align="center">
<img src="https://user-images.githubusercontent.com/120928832/222942858-d34d0b82-9156-4306-80a1-1ff3333d632b.jpg"/>
</p>


<h2>Pratique</h2>
Agora que concluiu as estapas acima, você já pode copiar ou baixar os códigos deste repositório e aplicar dentro do terminal ppython do QGIS.







