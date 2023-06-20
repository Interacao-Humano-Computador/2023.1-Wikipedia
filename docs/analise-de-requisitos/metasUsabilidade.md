## Introdução

Bem-vindo à página de Metas de Usabilidade, nessa presente página serão definidas as metas para definir fatores de qualidade de uso que deverão ser priorizados no projeto atual, como serão avaliados ao longo do processo de design, definindo também indicadores para definir valores que serão aceitos ou não, e ideais a serem seguidos. No caso desse projeto relacionado ao processo de design, o ciclo de vida da Engenharia da Usabilidade de Mayhew[1] foi o definido anteriormente.

## Metas de Usabilidade

As metas de usabilidade são objetivos a serem alcançados sobre a usabilidade, no caso de usabilidade, como definido por Nielsen "Usabilidade é um atributo de qualidade que avalia a facilidade de uso das interfaces do usuário. A palavra 'usabilidade' também se refere a métodos para melhorar a facilidade de uso durante o processo de design."(adaptado, Nielsen,2012)[2]. De acordo com ele também, a usabilidade é definida por 5 componentes de qualidade como descrito na Tabela 1.

| Componente     | Descrição                                                                                                                   |
| -------------- | ----------------------------------------------------------------------------------------------------------------------------- |
| Aprendizagem   | O quão fácil é para os usuários realizarem tarefas básicas na primeira vez que encontram o design?                       |
| Eficiência    | Uma vez que os usuários tenham aprendido o design, com que rapidez eles podem executar tarefas?                              |
| Memorabilidade | Quando os usuários retornam ao design após um período sem usá-lo, com facilidade eles podem restabelecer a proficiência? |
| Erros          | Quantos erros os usuários cometem, o quão grave são esses erros, e com que facilidade eles podem se recuperar dos erros?   |
| Satisfação   | O quão agradável é usar o design?                                                                                          |

<div style="text-align: center">
    <p> Tabela 1: Componentes da Usabilidade (Fonte: Adaptado de Nielsen. 2012).</p>
</div>

Nielsen, escreve que também existem diversos outros atributos de qualidade importantes, sendo um principal, a **utilidade**, significando se a funcionalidade do design ***"faz o que o usuário necessita?"***[2], sendo essas qualidades, assim como a usabilidade, importantes para a sobrevivência de sistemas principalmente na web onde se qualquer dessas qualidades não for atendida as pessoas podem abandonar o sistema ou o site, principalmente por insatisfação com o mesmo, por não poder encontrar algo ou pelo motivo deste ser lento.

Para Preece, Rogers e Sharp[3] refere-se a garantir que a interatividade do produto seja fácil de aprender, com uso efetivo e divertido do ponto de vista do usuário, envolvendo melhorar a interatividade entre o usuário e produto para que o mesmo consiga realizar suas atividade no trabalho, na escola, na sua vida diária. Para isso as metas da Tabela 2 foram criadas para atender esses objetivos.

| Componente     |         Descrição         |
| -------------- | :-------------------------: |
| Eficiência    |     Eficiente para usar     |
| Eficácia      |      Eficaz para usar      |
| Segurança     |     Seguro para se usar     |
| Utilidade      |      Ter boa utilidade      |
| Aprendizagem   |     Fácil de Aprender     |
| Memorabilidade | Fácil de lembrar como usar |

<div style="text-align: center">
    <p> Tabela 2: Metas de Usabilidade de Preece, Rogers e Sharp  (Fonte: Adaptado de  Preece, Rogers e Sharp. 2015).</p>
</div>

As metas de usabilidade são geralmente guiadas por perguntas, sendo as respostas sobre essas questões que provêm ao designer alerta sobre problemas que possam existir bem cedo durante o processo de design. Dessa maneira, com o uso desses dois pode-se definir quais atributos de qualidade ou componentes da Tabela 1, ou Tabela 2, serão utilizados para definir as metas de usabilidade e o que será seguido em cada uma dessas.

## Metas de Usabilidade no Projeto

As metas de usabilidade foram definidas levando-se em consideração e baseando-se no [perfil de usuário](../analise-de-requisitos/perfilDeUsuario.md), considerando as características e [princípios gerais do projeto](../analise-de-requisitos/principiosGerais.md) dessa maneira utilizando as usabilidades definidas por Preece, Rogers e Sharp[3] e 1 componente definido no artigo de Nielsen[2], as metas de usabilidade da Tabela 3 foram as definidas para esse presente projeto.

| ID  | Componente     | Questão                                                                                                                        | Usabilidade Atual                                                                                                                                                                                                                                                                                                                                                                                                | Usabilidade Meta                                                                                                                                                                                                                                                                                                                                                                            |
| --- | -------------- | ------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| M01 | Eficiência    | O usuário consegue realizar suas atividades de maneira eficiente?                                                              | O sistema deve permitir a leitura de artigos a partir da escolha do usuário localizado na primeira página do Wikipédia, ou localização a partir de um filtro, ou categoria escolhida para realizar leitura com 1 a 4 cliques, excetuando as categorias que podem levar mais tempo por serem dividas em páginas, assim como poder criar, editar e denunciar artigos de maneira fácil                       | O sistema deve permitir a leitura de artigos a partir da escolha do usuário localizado na primeira página do Wikipédia, ou localização a partir de um filtro ou categoria escolhida para realizar leitura com 1 a 4 cliques, excetuando as categorias que podem levar mais tempo por serem dividas em páginas, assim como poder criar, editar e denunciar artigos de maneira fácil |
| M02 | Eficácia      | O usuário consegue realizar tarefas e acessar informações de maneira eficaz?                                                 | No sistema atual o usuário consegue acessar a principais funcionalidades do site na primeira página de maneira eficaz, podendo realizar o que o mesmo quer.                                                                                                                                                                                                                                                    | O sistema deve mostrar as principais funcionalidades que os usuários irão usar na página principal.                                                                                                                                                                                                                                                                                    |
| M03 | Segurança     | O sistema é seguro, ele protege as informações dos usuários ou possui falhas de segurança que podem comprometer o sistema? | O sistema atualmente impede de criar hiperlinks duvidosos por verificação manual por parte de algum administrador de páginas da Wikipédia e a denúncia de artigos ou usuários para proteção tanto de páginas quanto de usuários que acessem a mesma, sendo essa última funcionalidade escondida em uma página em que é feito um pedido para retirar ou verificar usuários que danifiquem páginas. | O sistema deve impedir os usuários de criarem hiperlinks que levem a material prejudicial a outros usuários, criando também um botão para denúncias de artigos, para entidades responsáveis na Wikipédia possam verificar se o mesmo é prejudicial ou não.                                                                                                                         |
| M04 | Utilidade      | O sistema fornece ao usuário funcionalidades que o mesmo necessita?                                                           | O sistema fornece ao usuário funcionalidades de filtros para localizar artigos de maneira rápida, cadastro e login para acessar a funcionalidade de criar ou editar um artigo, envio de formulário, entretanto, são todas essas funcionalidades cumprem em seu básico as atividades propostas pelos mesmos.                                                                                                | O sistema deve ser útil ao usuário para que o usuário acessa as principais funcionalidades de maneira fácil.                                                                                                                                                                                                                                                                            |
| M05 | Aprendizagem   | O quão fácil é para os usuários realizarem tarefas básicas do mesmo?                                                       | Atividades básicas de leitura e criação de artigo são de fáceis localizações no site, entretanto para atividades mais complexas sempre existem um fluxo muito complexo e profundo para realizar a atividade não-usuais o que aumentar a curva de aprendizagem do sistema.                                                                                                                               | O sistema deve ser fácil para usuários que acessam o site pela primeira vez, entendam como utilizá-lo, apresentando uma parte do site com link com ajuda e perguntas frequentes sobre o mesmo.                                                                                                                                                                                           |
| M06 | Memorabilidade | O sistema é fácil de se lembrar ou relembrar como usar?                                                                       | Para atividades básicas o fluxo para se realizar a atividade é simples, entretanto para fluxo mais aprofundados do sistema é uma tarefa árdua para se lembrar a sua localização.                                                                                                                                                                                                                           | O sistema deve ser fácil de se usar mediante tipografia sem serifa, simples e palavras de hiperlinks que remeta de maneira objetiva o que o mesmo faz.                                                                                                                                                                                                                                     |
| M07 | Erros          | Quantos erros os usuários cometem, o quão grave são esse erros?                                                              | O sistema facilmente permite que usuários revertam o erro cometido, mediante avisos por mensagem, e possam reverter artigos caso o mesmo não tenham sido verificado por algum administrador da Wikipédia.                                                                                                                                                                                                     | O sistema deve informar o usuário por meio de avisos de mensagens e sonoros, se possível sobre quando os usuários preencherem informações erradas em formulários simples internos do site e haver possibilidade de reverter edições que façam a qualidade de artigos diminuírem de qualidade ou não seguirem o padrão definidos nas políticas do site.                        |
| M08 | Erros          | Com que facilidade eles podem se recuperar dos erros?                                                                           | O sistema permite simplesmente apagar a informação errada e continua o fluxo do sistema ou com um fluxo simples bastando estar logado reverter um artigo no qual o erro foi cometido.                                                                                                                                                                                                                          | O usuário deve poder reescrever suas informações sem perder o que foi escrito anteriormente e deve haver um botão para pode reverter alterações feitas em artigos indevidamente.                                                                                                                                                                                                     |

<div style="text-align: center">
    <p> Tabela 3: Metas de Usabilidade  (Fonte: Gabriel. 2023).</p>
</div>

### Legenda

| ID | Descrição                                                    |
| -- | -------------------------------------------------------------- |
| M  | Meta de Usabilidade. Ex. M01 é igual a meta de usabilidade 01 |

<div style="text-align: center">
    <p> Tabela 4: Legenda (Fonte: Autor. 2023).</p>
</div>

## Referências Bibliográficas

[1] Processo de Design. Disponível em: https://interacao-humano-computador.github.io/2023.1-Wikipedia/planejamento/processo/ . Acesso em 14 de maio de 2023.

[2] Nielsen, Jacob. Usability 101: Introduction to Usability. Disponível em : https://www.nngroup.com/articles/usability-101-introduction-to-usability/ . Acesso em : 15 de maio de 2023.

[3] PREECE, J.; ROGERS, Y.; SHARP, H. Interation Design. 4th edition. John Wiley & Sons Ltd, 2015.

## Bibliografia

‌BARBOSA, Simone Diniz Junqueira; DA SILVA, Bruno Santana. Interação Humano - Computador. Rio de janeiro: Elsevier, 2010. Acesso em 13 de maio de 2023.

Pastel, Robert. CS4760 & CS5760: Human-Computer Interactions & Usability. Disponível em: http://cs4760.csl.mtu.edu/2017/lectures/usability/ .  Acesso em 15 de maio de 2023.

## Histórico de Versão

| Versão | Data       | Descrição                                         | Autor(es) | Revisor(es) |
| ------- | ---------- | --------------------------------------------------- | --------- | ----------- |
| 1.0     | 13/05/2023 | Criação da página de Metas de Usabilidade        | Gabriel   | Chaydson    |
| 1.1     | 19/06/2023 | Ajustes e Correções de Acordo com a Verificação | Gabriel   | Pedro       |
