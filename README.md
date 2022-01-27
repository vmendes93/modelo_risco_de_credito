# Modelo de Risco de Crédito

## Descrição
Este projeto usa métodos de predição para prever a chance de inadimplência de diversos clientes cadastrados em um banco de dados.

Esse tipo de análise é essencial para instituições que dependem de crédito analisarem os riscos associados a cada potencial credor, dado as condições.

Para isso, foram utilizados dois datasets - um de treino e outro de teste - para treinar o modelo e testá-lo respectivamente.

Foram feito dois modelos baseados em:
    - Regressão logística
    - *XG Boost*
No notebook é discutido qual modelo era o mais adequado.

Outras bibliotecas usadas:
    - Pandas
    - Numpy
    - Matplotlib
    - Seaborn
    - Sci Kit learn (vários módulos)

O maior desafio para manipulação destes dados foi decidir como preencher o número de valores nulos e NaN's sem que isso afetasse a efetividade do modelo - isso também é discutido em mais detalhe no *notebook* do projeto.

Futuramente, seria interessante comparar outros métodos com os usados assim como também separar diversos casos de uso e em como os modelos vão variar dependendo da influência dos dados.

## Baixar e Rodar o Projeto

Recomenda-se baixar todos os conteúdos deste repositório e que o usuários tenha um amebiente Python3 com as seguintes bibliotecas instaladas:
 - Pandas
 - Numpy
 - Matplotlib
 - Seaborn
 - Sci kit learn
 - XG Boost
 - Imbalanced Learn

 ## Como e onde posso usar este projeto?

 Este projeto é apenas um teste baseado em dados compartilhados comigo - que foram alterados e anonimizados para preservar a origem. Portanto, esse projeto é mais para praticar, estudar, e testar machine learning - ideal para quem está estudando ou aprendendo.

 Alguns insights podem ser retirados para quem está começando na carreira e se depara com uma situação semelhante.

 ## Créditos

 Gostaria de agradecer ao meu amigo [João Ralha(https://www.linkedin.com/in/jo%C3%A3o-ralha-5b768646/)] que me auxiliou de começo ao fim no projeto e me deu várias dicas e insights de como organizar e tratar os dados.