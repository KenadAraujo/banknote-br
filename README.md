# Open Dataset for Recognition of Brazilian Counterfeit Banknotes (BankNote-Br)

Este conjunto de dados é composto de imagens de cédulas brasileiras da [Segunda Família do Real](https://www.bcb.gov.br/cedulasemoedas/segundafamilia), verdadeiras e falsas, compostas das denominações: 2 reais, 5 reais, 10 reais, 20 reais, 50 reais e 100 reais. As cédulas de 200 reais não foram adicionadas devido a dificuldade em [obtê-las](https://g1.globo.com/economia/noticia/2022/09/02/ja-viu-alguma-nota-de-r-200-completa-dois-anos-mas-circulacao-no-pais-ainda-e-baixa.ghtml), além do mais, o governo brasileiro tem a intenção de [retirá-lás de circulação](https://www.terra.com.br/economia/nota-de-r-200-pode-acabar-veja-o-que-aconteceu-com-a-cedula-lancada-na-pandemia,7b5d388688a32be3368d60578d7fcad13tt3wi6n.html), por essa razão elas não foram adicionadas a esse conjunto de dados.

## Organização do conjunto de dados

O conjunto de dados é composto de 368 imagens (92 de treinamento e 276 de test), originadas de 23 cédulas genuínas, frente e verso ( 4 cédulas de 2 reais, 3 cédulas de 5 reais, 5 cédulas de 10 reais, 5 cédulas de 20 reais, 3 cédulas de 50 reais e 3 cédulas de 100 reais). Cada cédula genuína produziu duas imagens de treinamento padronizadas e 6 imagens de treinamento não padronizadas(simulando a captura por um deficiente visual). Além disso, suas contrapartes falsas também foram produzidas.

Este conjunto de dados é organizado em dois diretórios principais: 'FALSE' e 'TRUE'. Em cada uma desses diretórios possui dois subdiretórios: 'TEST' e 'TRAIN'. Os diretórios 'FALSE' e 'TRUE' possuem as imagens de cédulas falsas e cédulas verdadeiras, com a organização sugerida para teste ('TEST') e treinamento ('TRAIN'). A seguir a diagramação do diretório.

```
Banknote-Br
│   README.md
│   EULA.md    
└───FALSE
│   │   TEST
│   │   TRAIN
└───TRUE
    │   TEST
    │   TRAIN
```

> Este conjunto de dados segue as diretrizes da licença CC BY-NC 4.0 DEED

## Citação dos autores

Ao utilizar esse conjunto de dados, por favor, utilize o bibtex abaixo para citar os autores

``` bibtex
@data{silva_et_al_2024,
    url = {https://github.com/KenadAraujo/banknote-br},
    author = {Silva, Kenad W.A. and Aires, Kelson R.T. and Brito Neto, Laurindo de S.},
    publisher = {AVC Lab, UFPI - Universidade Federal do Piauí},
    title = {Open Dataset for Recognition of Brazilian Counterfeit Banknotes(BankNote-Br)},
    year = {2024} 
}
```

## Exemplos das imagens

As imagens foram capturadas de duas formas: em espaço controlado e em simulação do mundo real. Para o espaço controlado, foram capturadas fotografias em espaço iluminado, em uma distância de 30 a 40 centímetros, de ambos os lados das cédulas, sem dobras e sem oclusões (isto é, detalhes encobertos por outros objetos ou sobreposições). Para as simulações do mundo real, foram capturadas fotografias também a uma distância de 30 a 40 centímetros, sendo seguradas por mãos humanas, parcialmente encobertas ou não, com variação de iluminação e plano de fundo.

### Imagens de treinamento

<table>
  <tr>
    <td>Cédula Genuína de 2 reais - Frontal</td>
    <td>Cédula Genuína de 2 reais - Verso</td>
  </tr>
  <tr>
    <td><img src="./TRUE/TRAIN/02-C01F01P-V.jpg" width=640 height=300></td>
    <td><img src="./TRUE/TRAIN/02-C01V01P-V.jpg" width=640 height=300></td>
  </tr>
 </table>

<table>
  <tr>
    <td>Cédula Falsa de 2 reais - Frontal</td>
    <td>Cédula Falsa de 2 reais - Verso</td>
  </tr>
  <tr>
    <td><img src="./FALSE/TRAIN/02-C01F01P-F.jpg" width=640 height=300></td>
    <td><img src="./FALSE/TRAIN/02-C01V01P-F.jpg" width=640 height=300></td>
  </tr>
 </table>

### Imagens de teste

<table>
  <tr>
    <td>Cédula Genuína de 2 reais - Frontal</td>
    <td>Cédula Genuína de 2 reais - Verso</td>
  </tr>
  <tr>
    <td><img src="./TRUE/TEST/02-C01F01Z-V.jpg" width=640 height=300></td>
    <td><img src="./TRUE/TEST/02-C01V01Z-V.jpg" width=640 height=300></td>
  </tr>
 </table>

<table>
  <tr>
    <td>Cédula Genuína de 2 reais - Frontal</td>
    <td>Cédula Genuína de 2 reais - Verso</td>
  </tr>
  <tr>
    <td><img src="./TRUE/TEST/02-C01F02Z-V.jpg" width=640 height=300></td>
    <td><img src="./TRUE/TEST/02-C01V02Z-V.jpg" width=640 height=300></td>
  </tr>
 </table>

 <table>
  <tr>
    <td>Cédula Genuína de 2 reais - Frontal</td>
    <td>Cédula Genuína de 2 reais - Verso</td>
  </tr>
  <tr>
    <td><img src="./TRUE/TEST/02-C01F03Z-V.jpg" width=640 height=300></td>
    <td><img src="./TRUE/TEST/02-C01V03Z-V.jpg" width=640 height=300></td>
  </tr>
 </table>

 <table>
  <tr>
    <td>Cédula Falsa de 2 reais - Frontal</td>
    <td>Cédula Falsa de 2 reais - Verso</td>
  </tr>
  <tr>
    <td><img src="./FALSE/TEST/02-C01F01Z-F.jpg" width=640 height=300></td>
    <td><img src="./FALSE/TEST/02-C01V01Z-F.jpg" width=640 height=300></td>
  </tr>
 </table>

<table>
  <tr>
    <td>Cédula Falsa de 2 reais - Frontal</td>
    <td>Cédula Falsa de 2 reais - Verso</td>
  </tr>
  <tr>
    <td><img src="./FALSE/TEST/02-C01F02Z-F.jpg" width=640 height=300></td>
    <td><img src="./FALSE/TEST/02-C01V02Z-F.jpg" width=640 height=300></td>  </tr>
 </table>

 <table>
  <tr>
    <td>Cédula Falsa de 2 reais - Frontal</td>
    <td>Cédula Falsa de 2 reais - Verso</td>
  </tr>
  <tr>
    <td><img src="./FALSE/TEST/02-C01F03Z-F.jpg" width=640 height=300></td>
    <td><img src="./FALSE/TEST/02-C01V03Z-F.jpg" width=640 height=300></td>
  </tr>
 </table>