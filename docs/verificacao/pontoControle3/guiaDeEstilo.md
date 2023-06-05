# Verificação do Guia de Estilo

## Introdução

O presente documento apresentará a verificação do artefato Guia de Estilo, desenvolvidos pela equipe 3 do [Banco Central do Brasil](https://interacao-humano-computador.github.io/2023.1-BancoCentral/). A versão avaliada da página Guia de Estilo é a 1.0 da data 15/05. A técnica de inspeção será aplicada para verificar esses artefatos, de acordo com o [planejamento](../planejamento.md) estabelecido.

## Metodologia

Para a verificação, será adotada a técnica de inspeção, a qual será realizada por meio de uma checklist. Essa checklist consiste em uma série de perguntas que têm como objetivo avaliar se o artefato foi desenvolvido de acordo com as exigências da disciplina.

A checklist será preenchida com base em diferentes classificações, que incluem:

- 🟢: Completamente Satisfatório;
- 🟡: Incompleto;
- 🔴: Não realizado ou Errado;
- N/A: Não se aplica.

## Inspeção

Na tabela 1 a seguir, estão as questões padrões utilizadas em todos os artefatos.

| ID |                                 Questão                                 | Inspeção |
| :-: | :-----------------------------------------------------------------------: | :--------: |
| 1 |                 As legendas estão no padrão do projeto?                 |     🟢     |
| 2 |                  Possui links para os outros artefatos?                  |     🟡     |
| 3 |                   Existe uma introdução no artefato?                   |     🟢     |
| 4 |          Existe tabela de versionamento padronizado e completo?          |     🟡     |
| 5 |      Há referências bibliográficas e/ou bibliografia no artefato?      |     🟢     |
| 6 | As tabelas e imagens possuem legenda, fonte e são introduzidas no texto? |     🟡     |

<div style="text-align: center">
    <p> Tabela 1: Verificação padrao (Fonte: Gabriel Ferreira e Samuel. 2023).</p>
</div>

Na tabela 2 a seguir, estão as questões padrões utilizadas em todos os artefatos.

| ID |                                                                      Questão                                                                      | Inspeção |
| :-: | :-------------------------------------------------------------------------------------------------------------------------------------------------: | :--------: |
| 1 |                                             O documento explica com clareza as ferramentas utilizadas?                                             |     🟢     |
| 2 |                                          O documento apresenta as finalidades das ferramentas utilizadas ?                                          |     🟢     |
| 3 |                                O Guia de Estilo do projeto possui na introdução com Objetivo do Guia de Estilo ?                                |     🟢     |
| 4 |                      O Guia de Estilo do projeto possui na introdução com a Organização e Conteúdo do Guia de Estilo ?                      |     🟢     |
| 5 |                                    O Guia de Estilo do projeto possui na introdução o público-alvo do guia ?                                    |     🟢     |
| 6 |                                     O Guia de Estilo do projeto possui na introdução como utilizar o guia ?                                     |     🟢     |
| 7 |                                     O Guia de Estilo do projeto possui na introdução como manter o guia ?                                     |     🟢     |
| 8 |                                  O Guia de Estilo apresenta um tópico ou seção para Resultados de análise ?                                  |     🟢     |
| 9 |                      O Guia de Estilo apresenta um tópico ou seção para Descrição do ambiente de trabalho do usuário ?                      |     🟢     |
| 10 |                                  O Guia de Estilo apresenta  um tópico ou seção para Elementos de interface ?                                  |     🟢     |
| 11 |                               O Guia de Estilo apresenta um tópico ou seção para a disposição espacial e grid ?                               |     🟢     |
| 12 |                                          O Guia de Estilo apresenta um tópico ou seção para janelas ?                                          |     🔴     |
| 13 |                                     O Guia de Estilo apresenta um tópico ou seção para tipografia e cores ?                                     |     🟢     |
| 14 | O Guia de Estilo apresenta  um tópico ou seção para Elementos de interação, Estilos de interação, Seleção de um estilo e Aceleradores ? |     🟡     |
| 15 |           O Guia de Estilo apresenta um tópico ou seção para Elementos de ação, Preenchimento de campos, Seleção e Ativação ?           |     🟡     |
| 16 |    O Guia de Estilo apresenta um tópico ou seção para Vocabulário e padrões,  Terminologia, Tipos de tela e Sequências de diálogos ?    |     🟢     |
| 17 |     O Guia de Estilo apresenta um tópico, seção ou explicação para como os Princípios Gerais do Projeto serão adicionados ao projeto ?     |     🔴     |

<div style="text-align: center">
    <p> Tabela 2: Verificação de Padrões do Guia de Estilo (Fonte: Gabriel Ferreira e Samuel. 2023).</p>
</div>

## Comentários

Referentes a Tabela 1, os comentário que podem ser feitos, que estão contidos Tabela 3

| Número do ID da Tabela 1 | Comentário                                                                                                                                                                                                                     |
| ------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 2                         | O link do IFRAME, ou FIGMA 1 não existe na chamada de texto, gerando a seguinte condição "[Figma 1](link do figma)", impossibilitando acesso ao link do figma que era esperado. Recomenda-se colocar o link para corrigi-lo. |
| 4                         | O histórico de versão apresenta tanto datas e versão incodizentes com o escrito, sendo a revisão descrita como se tivesse feita antes da criação do figma.                                                                |
| 6                         | Como o link está quebrado em "FIGMA 1", por esse motivo está incompleto, sendo o referente ao "questionário" correto, recomenda-se seguir esse exemplo                                                                       |

<div style="text-align: center">
    <p> Tabela 3: Comentários sobre incosistências da Tabela 1 (Fonte: Gabriel Ferreira e Samuel Gomes. 2023).</p>
</div>

Comentários referentes a questões mais especificas da Tabela 2, estão localizados na Tabela 4

| Número do ID da Tabela 2 | Comentário                                                                                                                                                                                                                                                                                                                                          |
| ------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 12                        | As janelas não aparecem somente os grid e onde supostamente deveriam ficar o conteúdo, reocmenda-se criar uma alternativa, ou caso, não se possa retirar prints da tela deixa claro na documentação a motivação.                                                                                                                              |
| 14                        | Apesar das cores de cada estilo estarem bem definidas, sem as janelas, existe uma grande dificuldade em tentar se compreender como se ocorrerá a interação em alguma dessas páginas, como por exemplo a home, sendo definida, somente a grid das páginas, sem algum tipo de interface mais complexa para entender como tal elemento funcionaria |
| 15                        | Não foi encontrado elementos referentes a preenchimento, seleção e ativação na home e outras páginas, decorrentes da falta de janelas, o que prejudica o entedimento de onde iria se realizar essa ações em algumas dessas telas.                                                                                                            |
| 17                        | Sobre essa questão não foi possível identificar onde os Principios Gerais do Projeto serão adicionado a esse projeto, de maneira que ajude o guia de estilo e o projeto em si a tomar uma direção sem perder seus rumos.                                                                                                                       |

<div style="text-align: center">
    <p> Tabela 4:Comentários sobre incosistências da Tabela 2 (Fonte: Gabriel Ferreira e Samuel Gomes. 2023).</p>
</div>

## Resultados

Através dos checklists realizados no Cronograma podemos observar que:

- 16/23 exigências estão satisfatórias;
- 5/23 exigências estão incompletas;
- 2/23 exigências estão erradas ou não realizadas.

## Referências Bibliográficas

Banco Central. Disponível em: [https://interacao-humano-computador.github.io/2023.1-BancoCentral/#/](https://interacao-humano-computador.github.io/2023.1-BancoCentral/#/). Acesso em: 5 jun. 2023.‌
‌

## Histórico de versão

|    Data    | Versão |      Descrição      |    Autor(es)    |
| :--------: | :-----: | :--------------------: | :--------------: |
| 05/06/2023 |   1.0   | Criação do documento | Gabriel Ferreira e Samuel |
