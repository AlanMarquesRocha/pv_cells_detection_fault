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
  
# Rede Neural Convolucional Híbrida Otimizada por Algoritmos Genéticos para Classificação em Imagens Eletroluminescentes de Células Fotovoltaicas

## Resumo

Este trabalho propõe um método para classificação de células fotovoltaicas (FV) de silício monocristalino (Si-m) e policristalino (Si-p) em categorias funcionais e não-funcionais. Para isso, utiliza-se uma Hybrid Convolutional Neural Network (HCNN) baseada nas arquiteturas ResNet50 e VGG16, pré-treinadas com o conjunto de dados ImageNet para extração de características das imagens. Os melhores hiperparâmetros para cada rede foram obtidos por meio de Algoritmos Genéticos Evolutivos (AGE). O processo de classificação da HCNN foi realizado utilizando uma Support Vector Machine (SVM).

Foram conduzidos quatro experimentos de classificação. Inicialmente, algoritmos elementares como SVM, Naïve Bayes (NB), k-Nearest Neighbors (k-NN) e Random Forest (RF) foram testados. Subsequentemente, experimentos foram realizados com as arquiteturas ResNet50, VGG16 e InceptionV3. Os modelos HCNN ResNet50+SVM e VGG16+SVM foram testados com a base de dados original contendo 2.624 amostras e com uma base de dados aumentada, contendo 13.120 imagens.

O ajuste fino utilizando AGE sem aumento de dados resultou na topologia VGG16+SVM alcançando uma acurácia de 95,21% e um índice Kappa de 78,23%. Como resultado principal deste trabalho, a mesma topologia de HCNN superou seu desempenho anterior, alcançando uma acurácia de 99,67% e um índice Kappa de 80,17% com aumento de dados. O modelo ResNet50+SVM também mostrou resultados robustos com aumento de dados, atingindo uma acurácia de 98,17% e um índice Kappa de 85,26%. Esses resultados evidenciam a eficácia das técnicas propostas, posicionando a HCNN otimizada por AGE e aumento de dados como uma solução promissora para a detecção automática de defeitos em células FVs de Si-m e Si-p.

## Palavras-chave

Detecção automática de defeitos; Rede neural convolucional híbrida; Célula fotovoltaica; Ajuste fino de hiperparâmetros; Algoritmos genéticos evolutivos.

## Metodologia

A metodologia empregada neste trabalho envolveu as seguintes etapas:

1.  **Base de Imagens:** Utilização de um conjunto de dados de imagens eletroluminescentes de células fotovoltaicas de silício monocristalino (Si-m) e policristalino (Si-p).
2.  **Aumento de Dados:** Aplicação de técnicas de aumento de dados para expandir o conjunto de treinamento e melhorar a robustez dos modelos.
3.  **Pré-processamento com CLAHE:** Uso da técnica Contrast Limited Adaptive Histogram Equalization (CLAHE) para realçar características importantes nas imagens.
4.  **Ajuste Fino Genético:** Otimização dos hiperparâmetros das redes neurais convolucionais (ResNet50 e VGG16) utilizando Algoritmos Genéticos Evolutivos (AGE).
5.  **Extração de Características:** As redes pré-treinadas (ResNet50 e VGG16) foram utilizadas como extratores de características.
6.  **Classificação com SVM:** As características extraídas foram então alimentadas em uma Support Vector Machine (SVM) para a classificação final das células em funcionais e não-funcionais.

## Resultados e Discussões

Os experimentos foram divididos em diferentes fases para avaliar a performance dos modelos:

*   **Algoritmos Elementares:** Testes iniciais com SVM, Naïve Bayes (NB), k-Nearest Neighbors (k-NN) e Random Forest (RF).
*   **Modelos CNN:** Avaliação das arquiteturas ResNet50, VGG16 e InceptionV3.
*   **Ajuste Fino Genético (sem aumento de dados):** A topologia VGG16+SVM alcançou 95,21% de acurácia e 78,23% de índice Kappa.
*   **Ajuste Fino Genético (com aumento de dados):** A topologia VGG16+SVM atingiu 99,67% de acurácia e 80,17% de índice Kappa. O modelo ResNet50+SVM obteve 98,17% de acurácia e 85,26% de índice Kappa.

Esses resultados demonstram a superioridade da abordagem HCNN otimizada por AGE e com aumento de dados para a detecção de defeitos em células fotovoltaicas.

## Estrutura do Repositório

```
.
├── README.md
├── dissertacao.pdf
├── imagens/
│   ├── lib/
│   │   ├── capitulo_04_celula_fotovoltaica/
│   │   ├── capitulo_05_eletroluminescencia/
│   │   ├── capitulo_06_pre_processamento/
│   │   ├── capitulo_07_aprendizado_profundo/
│   │   ├── capitulo_07_resultados/
│   │   └── capitulo_08_metodologia/
│   └── ... (outros arquivos e diretórios da dissertação)
└── ... (outros arquivos do projeto)
```

## Como Citar

Se você utilizar este trabalho em sua pesquisa, por favor, cite a dissertação original:

Rocha, A. M. (2024). *Rede Neural Convolucional Híbrida Otimizada por Algoritmos Genéticos para Classificação em Imagens Eletroluminescentes de Células Fotovoltaicas*. Dissertação de Mestrado, Universidade Federal do Ceará, Sobral.

## Contato

Para mais informações, entre em contato com o autor: Alan Marques da Rocha.

## Licença

Este projeto está licenciado sob a Licença MIT. Veja o arquivo `LICENSE` para mais detalhes. (Assumindo licença MIT, caso contrário, especificar a licença correta).



## Imagens Relevantes

Aqui estão algumas imagens importantes que ilustram a metodologia e os resultados deste trabalho:

### Modelo de Rede Neural Convolucional Híbrida (HCNN)

![Modelo HCNN](https://private-us-east-1.manuscdn.com/sessionFile/YNPFHXLad9UOfvbIwAd145/sandbox/ZiZynWABKb72id4er0HxdR-images_1753140548319_na1fn_L2hvbWUvdWJ1bnR1L3JlcG9faW1hZ2VzL0hDTk4.png?Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9wcml2YXRlLXVzLWVhc3QtMS5tYW51c2Nkbi5jb20vc2Vzc2lvbkZpbGUvWU5QRkhYTGFkOVVPZnZiSXdBZDE0NS9zYW5kYm94L1ppWnluV0FCS2I3MmlkNGVyMEh4ZFItaW1hZ2VzXzE3NTMxNDA1NDgzMTlfbmExZm5fTDJodmJXVXZkV0oxYm5SMUwzSmxjRzlmYVcxaFoyVnpMMGhEVGs0LnBuZyIsIkNvbmRpdGlvbiI6eyJEYXRlTGVzc1RoYW4iOnsiQVdTOkVwb2NoVGltZSI6MTc5ODc2MTYwMH19fV19&Key-Pair-Id=K2HSFNDJXOU9YS&Signature=vyhBRu8vWQxFrPZEq~EbmpRsDpvXyf-PYapeCTVUPXIgoaSuUfKvgcaOT9qPAS8Ti4CvjxlbV64q5eE0bSxTskU79GShFIE9GiJTNFSC17Jk3SPsq-lN8FOcx6CkcRWbBlwpjh-K9iV6B-tQTAA7-XMUZnpreSsfncKH1VoWerlVi3c6k0V7NjnOmL4uy~wUoyM9UK7yj41tAgDohGMXjecE5sRhrdsLbyoc~O4nMsCNM1DA0YMmvvwV5XYq6iRKMXePkF7NieP406nmXrFk5m5gZtNA5c557eZtpr4~MU7CNFpfzhCfGtHinN2In7BBAN1FqPVZHrHJ30833Z2ZVw__)

### Matriz de Confusão do Modelo VGG16+SVM

![Matriz de Confusão VGG16+SVM](https://private-us-east-1.manuscdn.com/sessionFile/YNPFHXLad9UOfvbIwAd145/sandbox/ZiZynWABKb72id4er0HxdR-images_1753140548320_na1fn_L2hvbWUvdWJ1bnR1L3JlcG9faW1hZ2VzL21jX3ZnZzE2X3N2bQ.png?Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9wcml2YXRlLXVzLWVhc3QtMS5tYW51c2Nkbi5jb20vc2Vzc2lvbkZpbGUvWU5QRkhYTGFkOVVPZnZiSXdBZDE0NS9zYW5kYm94L1ppWnluV0FCS2I3MmlkNGVyMEh4ZFItaW1hZ2VzXzE3NTMxNDA1NDgzMjBfbmExZm5fTDJodmJXVXZkV0oxYm5SMUwzSmxjRzlmYVcxaFoyVnpMMjFqWDNablp6RTJYM04yYlEucG5nIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxNzk4NzYxNjAwfX19XX0_&Key-Pair-Id=K2HSFNDJXOU9YS&Signature=Eal05IsYvk6KtmChw1OhRsmv4DwqAQauSFzX4QIouNM56FG-aUw80vudqUHc5J80i~2V8e5vZy9-wtsRJXJANy4YKpPjtv7fFBqsC8EdWx-Q3t3A5IWuzHCtMwQ-k6A~ow94PTFoFtCrbWQUvuiRxf7uFaGPlgqU-hq1u43wMAnOeIjus29utwdK-JPHmn2KFXnh94xgJ7x1YztWRwk7trUrZ35tRSbOjjh2G7l~osSVoqTr0AUHci-G-snqCLc2PuTLFkkKrcWAJ7R7CSHf~oC90rUapoANU8x5wNPqzVBFqRcNLZc9gnhVGIci1KNDFjc8H11zG7Kwp9izIFpKdQ__)

### Matriz de Confusão do Modelo ResNet50+SVM

![Matriz de Confusão ResNet50+SVM](https://private-us-east-1.manuscdn.com/sessionFile/YNPFHXLad9UOfvbIwAd145/sandbox/ZiZynWABKb72id4er0HxdR-images_1753140548321_na1fn_L2hvbWUvdWJ1bnR1L3JlcG9faW1hZ2VzL21jX3Jlc25ldDUwX3N2bQ.png?Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9wcml2YXRlLXVzLWVhc3QtMS5tYW51c2Nkbi5jb20vc2Vzc2lvbkZpbGUvWU5QRkhYTGFkOVVPZnZiSXdBZDE0NS9zYW5kYm94L1ppWnluV0FCS2I3MmlkNGVyMEh4ZFItaW1hZ2VzXzE3NTMxNDA1NDgzMjFfbmExZm5fTDJodmJXVXZkV0oxYm5SMUwzSmxjRzlmYVcxaFoyVnpMMjFqWDNKbGMyNWxkRFV3WDNOMmJRLnBuZyIsIkNvbmRpdGlvbiI6eyJEYXRlTGVzc1RoYW4iOnsiQVdTOkVwb2NoVGltZSI6MTc5ODc2MTYwMH19fV19&Key-Pair-Id=K2HSFNDJXOU9YS&Signature=Ugu3cjsnE1OFeRWOTv94X54B9i-T1iWWwYWiPfTYCJ9z~rEPr-xemygs4c0HBKPcFc3b2FX3LKHR1vDlnhzf~Loc-u8S9K3LgfiiwfDqybDlCuODuoFdxrCEophzxESPrcMmSwdSQrvY~0Jzf5oct2of0AfqUwc4hDC7KEEnMO5mtwxJb1Jy35HSaXj9OP1OQgLo~p0ZtHTO9mKeWwCtgeJve7leZbbxXYdSb-oQSnqibOnEciodZ8sA4GmzdKofAu9DtZmy8yyPelF9T8h8xKfjbqrg~dHmScgKXE4-EARDNCpreR-uqg0mRsGUvfBHUdbNkz3BaWI8b7UhRZkTjQ__)

### Célula Fotovoltaica Monocristalina Funcional

![Célula Monocristalina Funcional](https://private-us-east-1.manuscdn.com/sessionFile/YNPFHXLad9UOfvbIwAd145/sandbox/ZiZynWABKb72id4er0HxdR-images_1753140548322_na1fn_L2hvbWUvdWJ1bnR1L3JlcG9faW1hZ2VzL2ZpZ184XzFfYV9tb25vX2Z1bmM.png?Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9wcml2YXRlLXVzLWVhc3QtMS5tYW51c2Nkbi5jb20vc2Vzc2lvbkZpbGUvWU5QRkhYTGFkOVVPZnZiSXdBZDE0NS9zYW5kYm94L1ppWnluV0FCS2I3MmlkNGVyMEh4ZFItaW1hZ2VzXzE3NTMxNDA1NDgzMjJfbmExZm5fTDJodmJXVXZkV0oxYm5SMUwzSmxjRzlmYVcxaFoyVnpMMlpwWjE4NFh6RmZZVjl0YjI1dlgyWjFibU0ucG5nIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxNzk4NzYxNjAwfX19XX0_&Key-Pair-Id=K2HSFNDJXOU9YS&Signature=VQRu7uljLQEWHmXYpyHnqmdD0DC6SAxIS5Ie0CPd0EVr6n3ScsR0aS1UD58weS8kF9GWV2aYUK2kdM2bydLHSO1GIMl~V3gWXYB2jdBiKcZ-Qb4Ulon2cExKtrHi8s-AnTZrkzIKjkHxeu9faGH8i50T~S4OJbdWfX58JlgsWDmvc9BGjwYCeu~ckozjok-ElH6HkpIUalJzWs1nGyIDe3H-XS~AaHs5OPpojCXcmPAwaEQ8DcsP-9V-Uf4g~dFr7CMiv1czxjnXiKLKhNBy6-jpqjeZK-8MA2Hk1R2EVo2vc~AFmCCeuiBX-mkhCBEYR5~AHeQFgSDiwAnzg8ku4Q__)

### Célula Fotovoltaica Monocristalina com Defeito

![Célula Monocristalina com Defeito](https://private-us-east-1.manuscdn.com/sessionFile/YNPFHXLad9UOfvbIwAd145/sandbox/ZiZynWABKb72id4er0HxdR-images_1753140548322_na1fn_L2hvbWUvdWJ1bnR1L3JlcG9faW1hZ2VzL2ZpZ184XzFfYl9tb25vX2RlZg.png?Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9wcml2YXRlLXVzLWVhc3QtMS5tYW51c2Nkbi5jb20vc2Vzc2lvbkZpbGUvWU5QRkhYTGFkOVVPZnZiSXdBZDE0NS9zYW5kYm94L1ppWnluV0FCS2I3MmlkNGVyMEh4ZFItaW1hZ2VzXzE3NTMxNDA1NDgzMjJfbmExZm5fTDJodmJXVXZkV0oxYm5SMUwzSmxjRzlmYVcxaFoyVnpMMlpwWjE4NFh6RmZZbDl0YjI1dlgyUmxaZy5wbmciLCJDb25kaXRpb24iOnsiRGF0ZUxlc3NUaGFuIjp7IkFXUzpFcG9jaFRpbWUiOjE3OTg3NjE2MDB9fX1dfQ__&Key-Pair-Id=K2HSFNDJXOU9YS&Signature=iTgPhKyq9Q9xSBTotSfnaA82Mt2slRHCb5Kb~yr1zXz-pFB6KBZG3vdidXZZ-zlDQXrKGgZj6V99h3HtFhJGiUOyBB42Zk0W0C0HQXMkVJweVhGl~ugZwJ9kjyLmumcpAT-bWuwllc3B34D1oVidKe1l9vs6iFEHO8eL62a1byPIpV3RYGdpxABLo-QEOonRDFzmWARRDyLCjMh3A3E~mXTjbCt2L~ONbguknoPk~nTUrZCgKfuioBlajQnigkc8ujbW4GEQVWGNEoVpPzbLco6xa4yNRgB2Q4E46b4EgMifX64rAbTyCjoFRAd3bwLtgjyPVRnDhZwEEPU0nlZFTA__)



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
