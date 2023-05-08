# AHT

## Introdução

A análise hierárquica de tarefas (AHT) é uma metodologia de design de interface que busca compreender as atividades que os usuários realizam em um sistema, a fim de criar uma interface mais intuitiva e eficiente. 

Nesta seção, verificaremos como a análise hierárquica de tarefas foi utilizada no contexto da Wikipedia, levando em consideração as particularidades dessa plataforma tão utilizada e de grande alcance.

Quando aplicada à Wikipedia, a AHT busca identificar as principais tarefas que os usuários realizam na plataforma, como, por exemplo, buscar por informações, criar e editar artigos, entre outras. Nesta seção abordaremos a edição de um artigo, pois conforme constatado no [perfil do usuário](perfil_usuario.md), essa é uma das principais funcionalidades do site em questão.

## Analise da tarefa: Edição de um artigo

Realizar uma contribução/edição a algum artigo é uma das principais atividades que o usuário executa no Wikipédia, visto que a colaboração é parte fundamental da manutenção da aplicação. A Tabela 1 e a Figura 1 ilustram, em diagrama e texto , respectivamente, a análise hierárquica dessa tarefa.

| Objetivos / Operações               | Problemas e Recomendações                                                                                                                                                                                                                                                                               |
| :------------------------------------ | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 0. Editar uma página na Wikipedia    | input: tela de edição de alguma seção de um artigo<br />feedback: página alterada é exibida para o usuário<br />plano: realizar a contribuição e **depois** poder visualizar as alterações realizadas<br />recomendação: exibir mensagem de sucesso ao concluir com sucesso a edição |
| 1. Selecionar tipo de contribuição |                                                                                                                                                                                                                                                                                                           |
| 1.1 Realizar alterações             |                                                                                                                                                                                                                                                                                                           |
| 1.2 Revisar                           |                                                                                                                                                                                                                                                                                                           |
| 1.2.1 Revisar código escrito         |                                                                                                                                                                                                                                                                                                           |
| 1.2.2 Revisar artigo pela previsão  |                                                                                                                                                                                                                                                                                                           |
| 1.2.3 Revisar alterações            |                                                                                                                                                                                                                                                                                                           |
| 1.3 Publicar alterações            |                                                                                                                                                                                                                                                                                                           |
| 1.4 Visualizar as alterações feitas |                                                                                                                                                                                                                                                                                                           |
| 2. Ler artigo                         |                                                                                                                                                                                                                                                                                                           |
| 3. Ver histórico de contribuições  |                                                                                                                                                                                                                                                                                                           |

<div style="text-align: center">
    <p> Tabela 1: HTA em tabela (Fonte: Autores. 2023).</p>
</div>

<img src="../../images/aht.png"/>
<div style="text-align: center">
    <p> Figura 1: Diagrama HTA (Fonte: Autores. 2023).</p>
</div>

## Histórico de Versão

| Versão | Data       | Descrição            | Autor(es) | Revisor(es) |
| ------- | ---------- | ---------------------- | --------- | ----------- |
| 1.0     | 07/05/2023 | Criação do documento | Chaydson  | Lucas       |
