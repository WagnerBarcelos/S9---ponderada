# Contínuo Aprendizado em Sistemas Conversacionais

## Introdução

O paradigma de aprendizado contínuo é brutalmente relevante no campo de IA, especialmente em sistemas conversacionais. Este desafio surge da necessidade de manter o modelo atualizado com novos dados e informações, tendo o chamado "concept drift" como um problema central.

O "concept drift" refere-se à mudança nos padrões de dados subjacentes ao longo do tempo, fazendo com que o modelo se torne menos preciso em suas previsões. Isso é especialmente prejudicial em sistemas conversacionais que dependem de interações diárias com os usuários e estão continuamente expostos a novos padrões de linguagem e informações.

## Solução proposta 

<img width="547" alt="Hayashi" src="https://github.com/WagnerBarcelos/S9---ponderada/assets/99257595/a6d6d6dc-ba7c-4e53-96b9-80f4beda4b0d">

A solução proposta é composta pelos seguintes blocos:

1. **Coleta de dados:** Este bloco é responsável pela coleta de interações do usuário.
2. **Pré-processamento:** Aqui, os dados coletados são limpos e preparados.
3. **Detecção de Drift:** Este bloco é encarregado de monitorar o desempenho do modelo.
4. **Atualização do Modelo:** Aqui, novos modelos são treinados com base nos dados mais recentes.
5. **Implementação do Modelo:** Este bloco é responsável pela implementação do novo modelo.

## Conclusão

A importância do aprendizado contínuo em sistemas conversacionais justifica-se pela manutenção da acurácia do modelo, na medida em que ele enfrenta novos dados e novas informações regularmente, e evita o problema do "concept drift" que pode levar a resultados menos precisos ao longo do tempo. A solução em questão incorpora uma estrutura sistemática composta por cinco blocos principais: coleta de dados, pré-processamento, detecção de drift, atualização do modelo e implementação do modelo. Esses blocos trabalham juntos para garantir que o modelo esteja constantemente adaptando-se e aprendendo com a experiência, seguindo o paradigma do aprendizado contínuo. Esta solução representa um avanço significativo na maneira como os sistemas conversacionais são treinados e atualizados, levando a sistemas mais precisos e eficazes.

## Referências bibliográficas

1. GAMA, J.; ŽLIOBAITĖ, I.; BIFET, A.; PECHENIZKIY, M.; BOUCHACHIA, A. A survey on concept drift adaptation. ACM Computing Surveys (CSUR), v. 46, n. 4, p. 1-37, 2014.

2. HAREL, D.; MANN, G. Continuous Learning in Conversational Systems. In: Proceedings of the 2020 Conference on Empirical Methods in Natural Language Processing (EMNLP), 2020. Disponível em: https://www.aclweb.org/anthology/2020.emnlp-main.282/.
