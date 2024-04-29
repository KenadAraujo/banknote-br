# Open Dataset for Recognition of Brazilian Counterfeit Banknotes (BankNote-Br)

This dataset consists of images of Brazilian banknotes from the [Second Family of Real](https://www.bcb.gov.br/cedulasemoedas/segundafamilia) for people with visual impairment, both genuine and counterfeit, comprising the denominations: 2 reais, 5 reais, 10 reais, 20 reais, 50 reais, and 100 reais. The 200 reais banknotes were not included due to the difficulty in [obtaining](https://g1.globo.com/economia/noticia/2022/09/02/ja-viu-alguma-nota-de-r-200-completa-dois-anos-mas-circulacao-no-pais-ainda-e-baixa.ghtml) them (source), furthermore, the Brazilian government intends to [withdraw them from circulation](https://www.terra.com.br/economia/nota-de-r-200-pode-acabar-veja-o-que-aconteceu-com-a-cedula-lancada-na-pandemia,7b5d388688a32be3368d60578d7fcad13tt3wi6n.html), hence they were not added to this dataset.

``` 
At the end of producing the images, all fake banknotes were destroyed in order to prevent malicious use.
```

## Dataset Organization

The dataset comprises 368 images (92 for training and 276 for testing), originating from 23 genuine banknotes, both front and back (4 notes of 2 reais, 3 notes of 5 reais, 5 notes of 10 reais, 5 notes of 20 reais, 3 notes of 50 reais, and 3 notes of 100 reais). Each genuine banknote produced two standardized training images and 6 non-standardized training images (simulating capture by a visually impaired person). Additionally, their counterfeit counterparts were also produced.

This dataset is organized into two main directories: 'FALSE' and 'TRUE'. Each of these directories contains two subdirectories: 'TEST' and 'TRAIN'. The 'FALSE' and 'TRUE' directories contain images of counterfeit and genuine banknotes, respectively, with the suggested organization for testing ('TEST') and training ('TRAIN'). Below is the directory structure.

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

> This dataset follows the guidelines of the CC BY-NC 4.0 DEED license.

## Author Citation

When using this dataset, please use the following BibTeX entry to cite the authors:

``` bibtex
@data{silva_et_al_2024,
    url = {https://github.com/KenadAraujo/banknote-br},
    author = {Silva, Kenad W.A. and Aires, Kelson R.T. and Brito Neto, Laurindo de S.},
    publisher = {Applied Visual Computing Laboratory (AVC Lab), Federal University of Piauí (UFPI)},
    title = {Open Dataset for Recognition of Brazilian Counterfeit Banknotes(BankNote-Br)},
    year = {2024} 
}
```

## Examples of Images

The images were captured in two ways: controlled environment and real-world simulation. For the controlled environment, photographs were taken in a well-lit space, at a distance of 30 to 40 centimeters, from both sides of the banknotes, without folds and without occlusions (i.e., details covered by other objects or overlays). For real-world simulations, photographs were also taken at a distance of 30 to 40 centimeters, being held by human hands, partially covered or not, with variations in lighting and background.

### Training Images

<table>
  <tr>
    <td>Genuine 2 reais Banknote - Front</td>
    <td>Genuine 2 reais Banknote - Back</td>
  </tr>
  <tr>
    <td><img src="./TRUE/TRAIN/02-C01F01P-V.jpg" width=640 height=300></td>
    <td><img src="./TRUE/TRAIN/02-C01V01P-V.jpg" width=640 height=300></td>
  </tr>
 </table>

<table>
  <tr>
    <td>Counterfeit 2 reais Banknote - Front</td>
    <td>Counterfeit 2 reais Banknote - Back</td>
  </tr>
  <tr>
    <td><img src="./FALSE/TRAIN/02-C01F01P-F.jpg" width=640 height=300></td>
    <td><img src="./FALSE/TRAIN/02-C01V01P-F.jpg" width=640 height=300></td>
  </tr>
 </table>

### Test Images

<table>
  <tr>
    <td>Genuine 2 reais Banknote - Front</td>
    <td>Genuine 2 reais Banknote - Back</td>
  </tr>
  <tr>
    <td><img src="./TRUE/TEST/02-C01F01Z-V.jpg" width=640 height=300></td>
    <td><img src="./TRUE/TEST/02-C01V01Z-V.jpg" width=640 height=300></td>
  </tr>
 </table>
<table>
  <tr>
    <td>Genuine 2 reais Banknote - Front</td>
    <td>Genuine 2 reais Banknote - Back</td>
  </tr>
  <tr>
    <td><img src="./TRUE/TEST/02-C01F02Z-V.jpg" width=640 height=300></td>
    <td><img src="./TRUE/TEST/02-C01V02Z-V.jpg" width=640 height=300></td>
  </tr>
 </table>
 <table>
  <tr>
    <td>Genuine 2 reais Banknote - Front</td>
    <td>Genuine 2 reais Banknote - Back</td>
  </tr>
  <tr>
    <td><img src="./TRUE/TEST/02-C01F03Z-V.jpg" width=640 height=300></td>
    <td><img src="./TRUE/TEST/02-C01V03Z-V.jpg" width=640 height=300></td>
  </tr>
 </table>
 <table>
  <tr>
    <td>Counterfeit 2 reais Banknote - Front</td>
    <td>Counterfeit 2 reais Banknote - Back</td>
  </tr>
  <tr>
    <td><img src="./FALSE/TEST/02-C01F01Z-F.jpg" width=640 height=300></td>
    <td><img src="./FALSE/TEST/02-C01V01Z-F.jpg" width=640 height=300></td>
  </tr>
 </table>
<table>
  <tr>
    <td>Counterfeit 2 reais Banknote - Front</td>
    <td>Counterfeit 2 reais Banknote - Back</td>
  </tr>
  <tr>
    <td><img src="./FALSE/TEST/02-C01F02Z-F.jpg" width=640 height=300></td>
    <td><img src="./FALSE/TEST/02-C01V02Z-F.jpg" width=640 height=300></td>  </tr>
 </table>
 <table>
  <tr>
    <td>Counterfeit 2 reais Banknote - Front</td>
    <td>Counterfeit 2 reais Banknote - Back</td>
  </tr>
  <tr>
    <td><img src="./FALSE/TEST/02-C01F03Z-F.jpg" width=640 height=300></td>
    <td><img src="./FALSE/TEST/02-C01V03Z-F.jpg" width=640 height=300></td>
  </tr>
 </table>
