<h3 align="center">Conecte-se comigo em:</h3>
<p align="center">
<a href="https://linkedin.com/in/alanmarquesrocha" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="alanmarquesrocha" height="30" width="40" /></a>
<a href="https://stackoverflow.com/users/19201352/m4rkn4l4" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/stack-overflow.svg" alt="alanmarquesrocha" height="30" width="40" /></a>
<a href="https://instagram.com/alanmarquesrocha" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/instagram.svg" alt="alanmarquesrocha" height="30" width="40" /></a>
</p>

---

<h3 align="center"> 
	 🚀 Em construção 🚀 
</h3>

---

<h3 align="center">Modelo computacional para discriminação de células fotovoltaicas defeituosas em imagens eletroluminescentes.<br>

---
  
### Informações básicas do projeto (Sujeito à alterações):

O projeto em questão tem como objetivo realizar a implementação de uma topologia de CNN (Convolutional Neural Network) de baixo custo computacional para realizar a extração de atributos das imagens de células Fotovoltaicas (FVs) de um conjunto de dados amplamente utilizado na literatura, visando usar esses atributos para formar um vetor de características robusto que alimentará um classificador.

O projeto em questão está dividido nas seguintes etapas (Sujeito à alterações):

- Pré-processamento das imagens;
- Aplicação do método ``Local Binary Pattern`` (LBP) para realizar a melhoria dos atributos que serão utilizados na alimentação da CNN;
- Ajuste dos hiperparâmetros da CNN, visando obter uma topologia robusta e de baixo custo computacional;
- Implementação da CNN para realizar o processo de extração de características das imagens;
- Implementação de uma ``Support Vector Machine`` (SVM) que servirá como classificador do modelo proposto.



A base de dados contém **2.624 imagens de células FVs de 300 x 300 pixels em níveis de cinza (8 bits)**, sendo 1.074 imagens de células de silício monocristalino e 1.550 imagens de células de silício policristalino, extraídas de 44 módulos FVs diferentes.

Cada imagem foi rotulada com um número de ponto flutuante que caracteriza a probabilidade de defeito da mesma, podendo variar entre 0 e 1, onde:

0 - célula FV sem probabilidade de defeito
1 - célula FV com alto grau de probabilidade de defeito.

As células são divididas em ``mono`` e ``poly``, representando as células de silício monocristalino e policristalino respectivamente.

Pode-se verificar qual tipo de célula estamos trabalhando através do arquivo ``labels.csv``. Neste arquivo, constam as seguintes informações:

- nome da imagem (Ex: cell236.png)
- grau de defeito (0.0, 1.0, 0.333, 0.666)
- tipo de célula (mono ou poly)

### Autores que disponibilizaram a base (Citação):

> Buerhop-Lutz, C.; Deitsch, S.; Maier, A.; Gallwitz, F.; Berger, S.; Doll, B.; Hauch, J.; Camus, C. & Brabec, C. J. A Benchmark for Visual Identification of Defective Solar Cells in Electroluminescence Imagery. European PV Solar Energy Conference and Exhibition (EU PVSEC), 2018. DOI: [10.4229/35thEUPVSEC20182018-5CV.3.15](http://dx.doi.org/10.4229/35thEUPVSEC20182018-5CV.3.15)

> Deitsch, S., Buerhop-Lutz, C., Sovetkin, E., Steland, A., Maier, A., Gallwitz, F., & Riess, C. (2021). Segmentation of photovoltaic module cells in uncalibrated electroluminescence images. Machine Vision and Applications, 32(4). DOI: [10.1007/s00138-021-01191-9](https://doi.org/10.1007/s00138-021-01191-9)

> Deitsch, S.; Christlein, V.; Berger, S.; Buerhop-Lutz, C.; Maier, A.; Gallwitz, F. & Riess, C. Automatic classification of defective photovoltaic module cells in electroluminescence images. Solar Energy, Elsevier BV, 2019, 185, 455-468. DOI: [10.1016/j.solener.2019.02.067](http://dx.doi.org/10.1016/j.solener.2019.02.067)

BibTeX details:

<details>

```bibtex

@InProceedings{Buerhop2018,
  author    = {Buerhop-Lutz, Claudia and Deitsch, Sergiu and Maier, Andreas and Gallwitz, Florian and Berger, Stephan and Doll, Bernd and Hauch, Jens and Camus, Christian and Brabec, Christoph J.},
  title     = {A Benchmark for Visual Identification of Defective Solar Cells in Electroluminescence Imagery},
  booktitle = {European PV Solar Energy Conference and Exhibition (EU PVSEC)},
  year      = {2018},
  eventdate = {2018-09-24/2018-09-28},
  venue     = {Brussels, Belgium},
  doi       = {10.4229/35thEUPVSEC20182018-5CV.3.15},
}

@Article{Deitsch2021,
  author       = {Deitsch, Sergiu and Buerhop-Lutz, Claudia and Sovetkin, Evgenii and Steland, Ansgar and Maier, Andreas and Gallwitz, Florian and Riess, Christian},
  date         = {2021},
  journaltitle = {Machine Vision and Applications},
  title        = {Segmentation of photovoltaic module cells in uncalibrated electroluminescence images},
  doi          = {10.1007/s00138-021-01191-9},
  issn         = {1432-1769},
  number       = {4},
  volume       = {32},
}

@Article{Deitsch2019,
  author    = {Sergiu Deitsch and Vincent Christlein and Stephan Berger and Claudia Buerhop-Lutz and Andreas Maier and Florian Gallwitz and Christian Riess},
  title     = {Automatic classification of defective photovoltaic module cells in electroluminescence images},
  journal   = {Solar Energy},
  year      = {2019},
  volume    = {185},
  pages     = {455--468},
  month     = jun,
  issn      = {0038-092X},
  doi       = {10.1016/j.solener.2019.02.067},
  publisher = {Elsevier {BV}},
}
```
