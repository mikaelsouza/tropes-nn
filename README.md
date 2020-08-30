# Utilizando Tropes para Prever Sucesso de Filmes:

### Informações Importantes:

Este trabalho foi financiado pelo [Conselho Nacional de Desenvolvimento Científico e Tecnológico - CNPq](http://www.cnpq.br/) e obteve menção honrosa como melhor trabalho da área de Ciências Naturais e da Terra no XXVII CONIC 2017/2018 pela [Universidade Federal do Amazonas](https://ufam.edu.br/).

### Sobre:
[Tropes](https://en.wikipedia.org/wiki/Trope_(literature)), no contexto de mídia audiovisual, são estruturas de roteiro e tipos de personagens recorrentes que podem ser identificados. Por conta desta característica, tropes podem ser explorados como representações categóricas para modelos de aprendizagem de máquina com diversos objetivos.

O website [TVTropes](https://tvtropes.org/) fornece um vasto catálogo de Tropes descritos no formato de wiki e editado por colaboradores. Isto apresenta uma oportunidade de utilizar estas informações catalogadas como uma representação do roteiro e dos personagens envolvidos nas tramas.

Por conta do alto custo para a produção de grande parte de mídias áudiovisuais, medir o sucesso das mesmas antes de produzi-las é uma capacidade desejada para medir risco de investimento, por conta disso este trabalho explorou-se o uso de Tropes como atributo para prever o desempenho de destas mídias em notas do IMDB e arrecadação de bilheteria.

### Banner & Resultados:

![Banner CONIC](imgs/0001.jpg)

### Limitações:

- Boa parte do problema deste trabalho está no problema da alta dimensionalidade por conta da vasta quantidade de tropes existentes. Utilizou-se abordagens de redução de dimensionalidade como [PCA](https://en.wikipedia.org/wiki/Principal_component_analysis), [t-SNE](https://en.wikipedia.org/wiki/T-distributed_stochastic_neighbor_embedding) e [Autoencoders](https://en.wikipedia.org/wiki/Autoencoder) para tentar resolver este problema.
- Deviso a minha inexperiencia no momento deste trabalho, os resultados podem estar alterados devido ao pre-processamento indevido dos dados.

### TODOs:

- [ ] Adicionar códigos neste repositório.
- [ ] Realizar um novo crawling dos dados de filmes e tropes.
- [ ] Reexecutar abordagem testada por este trabalho para testar validade dos resultados originais.