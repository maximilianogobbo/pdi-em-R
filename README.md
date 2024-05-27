# pdi-em-R

O repositório refere-se ao livro de Processamento Digital de Imagens (PDI), foi construído para servir de apoio para sua publicação.

# Processamento Digital de Imagens em R

## Descrição

Este repositório está interligado ao livro **Processamento Digital de Imagens (PDI)**, o qual foi desenvolvido durante a disciplina de PDI, realizada na Universidade Federal de Uberlândia (UFU) para o curso de Geografia (Instituto de Geografia). No livro são apresentadas diferentes ferramentas para a análise, tratamento e manipulação de imagens orbitais. A base teórica para sua construção foi o livro de Meneses et al. (2012): **Introdução ao Processamento de Imagens de Sensoriamento Remoto**. Vale destacar que nosso foco foi transpor procedimentos executados em softwares de PDI para o universo da programação, mais propriamente ao **Software R**. Por tal, ao início de cada capítulo do nosso livro fazemos menção ao(s) capítulo(s) do livro de Meneses et al. (2012), de modo que nosso leitor possa complementar a compreensão dos procedimentos com esta formidável base teórica. Esperamos que o livro **Processamento Digital de Imagens em R** possa ilustrar alguns dos inúmeros procedimentos associados ao Processamento Digital de Imagem. Além disso, pretendemos demonstrar o poder analítico do **Software R**, trazendo de forma didática e dinâmica como a programação pode ser um recurso diferencial no geoprocessamento e em seus desdobramentos.

*Referência completa: MENESES, P. R.; ALMEIDA, T. D.; ROSA, A. N. D. C. S.; SANO, E. E. et al. Introdução ao Processamento de Imagens de Sensoriamento Remoto. Brasília: UnB-CNPq, 276 p., 2012.

Os dados vetoriais e raster, as imagens orbitais originais e recortadas e outros documentos utilizados neste livro foram captados de bases e plataformas globais, como o Instituto Nacional de Pesquisas Espaciais (INPE-Brasil), o Instituto Brasileiro de Geografia e Estatística (IBGE-Brasil) e o Copernicus. 
The data used in this research were produced by the Brazilian Institute of Geography and Statistics (IBGE), to which we are immensely grateful for making this wide range of information available.

## Requisitos

Para executar os scripts deste repositório, você precisará ter o seguinte software instalado:

- [R](https://cran.r-project.org/)
- [RStudio](https://www.rstudio.com/)

Além disso, você precisará instalar alguns pacotes R. Os principais pacotes utilizados são:

library(sf)      
library(terra)   
library(dplyr)   
library(spData)
library(raster)
library(ows4R)
library(osmdata)
library(geodata)
library(tigris)
library(tidycensus)
library(GSODR)
library(tidyverse)
library(ggplot2,gapminder, magrittr)
library(pander)
library(rgdal)
library(leaflet)
library(rmapshaper)
library(mapview)
library(tmap)
library(osmdata)
library(ggmap)
library(grid)
library(gridExtra)
library(png)
library(readxl)

## Como usar 

Este repositório contém 10 arquivos R Markdown principais (`.Rmd`), cada um deles referentes a um dos capítulos do livro. Portanto, eles podem ser executados individualmente, necessitando obrigatoriamente dos dados de referência para sua execução (disponíveis na pasta em núvem do livro). Aqui está uma breve descrição de cada um e como usá-los:

0.	Índice: “index.Rmd” – publicado no RPubs, disponível em: https://rpubs.com/maximilianogobbo/1187740 
1.	Capítulo 01 - Introdução ao R, RStudio e RMarkdown: “cap01.Rmd” – publicado no RPubs, disponível em: http://rpubs.com/maximilianogobbo/1187664
2.	Capítulo 02 - Classificação de Imagens Orbitais: “cap02.Rmd” – publicado no RPubs, disponível em: http://rpubs.com/maximilianogobbo/1187672 
3.	Capítulo 03 - Histogramas - Quantização e Amostragem: “cap03.Rmd” – publicado no RPubs, disponível em: https://rpubs.com/maximilianogobbo/1187738 
4.	Capítulo 04 - Filtragem: passa-baixa e passa-alta: “cap04.Rmd” – publicado no RPubs, disponível em: http://rpubs.com/maximilianogobbo/1187733 
5.	Capítulo 05 - Morfologia Matemática: “cap05.Rmd” – publicado no RPubs, disponível em: https://rpubs.com/maximilianogobbo/1187729 
6.	Capítulo 06 - Transformação no Espaço Imagem: “cap06.Rmd” – publicado no RPubs, disponível em: http://rpubs.com/maximilianogobbo/1187735 
7.	Capítulo 07 - Aritmética de Bandas: soma, subtração, multiplicação e divisão: “cap07.Rmd” – publicado no RPubs, disponível em: http://rpubs.com/maximilianogobbo/1187690 
8.	Capítulo 08 - Correção Geométrica e Registro de Imagens: “cap08.Rmd” – publicado no RPubs, disponível em: http://rpubs.com/maximilianogobbo/1187685 
9.	Capítulo 09 - Fusão de Imagens: “cap09.Rmd” – publicado no RPubs, disponível em: https://rpubs.com/maximilianogobbo/1187680  

Todos os arquivos associados ao livro e aqueles necessários para execução dos códigos “.Rmd” encontram-se indexados em uma pasta compartilhada em núvem, acessível através do link:

- PDI em R: https://1drv.ms/f/s!AtQOHKy-igqQj7AuSjgYJiSDqTu7EQ?e=gFTVuF 

## Contribuições 

Todos os leitores e todas as leitoras são convidadas a contribuir com o desenvolvimento do livro **Processamento Digital de Imagens em R**. Solicitamos, caso queira contribuir, que: 

- Problemas abertos relatando bugs ou sugerindo novos recursos.
- Envie solicitações pull com correções de bugs ou melhorias.
- Fornecer feedback sobre como podemos tornar este projeto ainda melhor.

Se você quiser contribuir com código, siga estas diretrizes:
- Crie um branch separado para suas alterações.
- Descreva claramente suas alterações na solicitação pull.
- Certifique-se de que seu código seja testado adequadamente.

## License

Este projeto está licenciado sob a [Licença MIT](https://opensource.org/licenses/MIT) - consulte o arquivo [LICENSE](LICENSE) para obter mais detalhes.
