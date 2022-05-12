# Criar um campos com PYQGIS
## Como criar um campo geométrico ou personalizado na tabela de atributos com PYQGIS


1 - No QGIS, selecione a camada desejada no painel de camadas

2 - Na segunda linha do script, coloque a expressão desejada entre aspas simples.
OBS: se for usar uma expressão personalizada, lembre-se de utilizar as barras-contra, como mostrado no video no youtube.

3 - Na linha 23 do script: 
- como primeiro parâmetro da função, coloque entre aspas simples o nome do campo(lembrando de respeitar as limitações de arquivos .shp, sem espações, caracteres especiais e no máximo 10 caracteres;
- Como segundo parâmetro da função, coloque o tipo do campo, QVariant.Double para números decimais, QVariant.Integer para inteiros e QVariant.String para textos;
- O terceiro e quarto parâmetro da função dizem respeito, respectivamente, ao comprimento e precisão do campo.

### Video aula
[![video aula](https://img.youtube.com/vi/WEckVvWdqVg/maxresdefault.jpg)](https://youtu.be/WEckVvWdqVg)
