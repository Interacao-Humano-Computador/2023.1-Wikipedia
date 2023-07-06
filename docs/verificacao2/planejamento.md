# Metodologia de verificação

## Introdução

A etapa de verificação é uma parte essencial do desenvolvimento de projetos, que tem como objetivo garantir que os produtos de trabalho atendam aos requisitos especificados. Existem algumas abordagens para a realização da verificação, por exemplo: Inspenção, estratégias formais e reutilização de dóminios. A verificação por inspenção é aplicada para verificação em artefatos, produzidos por clientes e sem alguma estrutura ou produzidos por engenheiros de software. Tem como objetivo encontrar defeitos nos artefatos, deve ter definições claras sobre os papéis dos avaliadores e os resultados que devem ser alcançados. Esse método tem sido excelente, portanto consegue-se, efetivamente, descobrir os defeitos de um artefato [2].

## Metodologia

O objetivo básico das inspenções é verificar se o artefato produzido está de acordo com o esperado, com isso, Fagan estabele-se os 6 passos principais para uma boa inspenção:

- Planejamento,
- Visão Geral,
- Preparação,
- Inspenção,
- Correção,
- Acompanhamento.

Vale ressaltar que a verificação da verificação será feita pelo autor do artefato verificado, assim, não havendo a necessidade de uma coluna chamada "Revisor" na tabela 1.

## Planejamento

<center>

| Artefato                                                               | Avaliador(es)    |
| ---------------------------------------------------------------------- | ---------------- |
| Cronogramas                                                            | Pedro            |
| Sites avaliados                                                        | Ana              |
| Site selecionado                                                       | Chaydson         |
| Metodologia                                                            | Gabriel          |
| Ferramentas                                                            | Lucas            |
| Processo de design                                                     | Samuel           |
| Perfil de Usuario                                                      | Lucas            |
| Personas                                                               | Samuel           |
| Análise das tarefas do usuário (técnicas HTA e GOMS)                | Pedro            |
| Aspectos éticos de pesquisa envolvendo pessoas                        | Gabriel          |
| Definir os princípios gerais do projeto                               | Lucas            |
| Determinar as metas de usabilidade                                     | Pedro            |
| Criar o guia de estilo                                                 | Gabriel e Samuel |
| Determinar as características da plataforma para o projeto            | Ana e Chaydson   |
| Planejar a avaliação do Story Board                                  | Chaydson         |
| Planejar a avaliação da Análise de Tarefas                          | Ana e Pedro      |
| Planejar o relato da avaliação do Story Board                        | Samuel           |
| Planejar o relato da avaliação da Análise de Tarefas                | Gabriel          |
| Relatar os resultados do Story Board                                   | Gabriel e Samuel |
| Relatar os resultados da análise de tarefas                           | Ana e Lucas      |
| Planejar a avaliação do protótipo de papel                          | Chaydson         |
| Planejar o relato dos resultados da avaliação do protótipo de papel | Pedro            |
| Planejar a avaliação do protótipo de alta fidelidade                | Chaydson         |
| Planejar o relato do protótipo de alta fidelidade                    | Lucas            |

<div style="text-align: center">
<p> Tabela 1: Tabela do cronograma de avaliação (Fonte: Lucas Frazão, 2023). </p>
</div>
</center>

## Preparação

Antes da verificação, precisamos inserir os metadados do artefato avaliado, conforme a tabela 2 abaixo:

<center>

| Versão avaliada | Autor             | Revisor             |
| ---------------- | ----------------- | ------------------- |
| versão x        | Autor do artefato | Revisor do artefato |

<div style="text-align: center">
<p> Tabela 2: Metadados do artefato (Fonte: NomeAutor, 2023). </p>
</div>

</center>

Para a verificação, será adotada a técnica de inspeção, a qual será realizada por meio de uma checklist. Essa checklist consiste em uma série de perguntas que têm como objetivo avaliar se o artefato foi desenvolvido de acordo com as exigências da disciplina.

A checklist será preenchida com base em diferentes classificações, que incluem:

- 🟢: Completamente Satisfatório;
- 🟡: Incompleto;
- 🔴: Não realizado ou Errado;
- N/A: Não se aplica.

Os membros avaliarão os artefatos com base no livro: da Simone [1].

A seguir, na tabela 3, temos as perguntas que serão feitas em todos os artefatos, são as perguntas padrões.

<center>

| ID |                                 Questão                                 | Inspeção |
| :-: | :-----------------------------------------------------------------------: | :--------: |
| 1 |                 As legendas estão no padrão do projeto?                 |     🟢     |
| 2 |                  Possui links para os outros artefatos?                  |     🟡     |
| 3 |                   Existe uma introdução no artefato?                   |     🔴     |
| 4 |                Existe tabela de versionamento padronizado?                |     🟢     |
| 5 |      Há referências bibliográficas ou referências no artefato?      |     🟢     |
| 6 | As tabelas e imagens possuem legenda, fonte e são introduzidas no texto? |     🟢     |
| 7 |                         O artefato possui autor?                         |     🟢     |
| 8 |                        O artefato possui revisor?                        |     🟢     |

<div style="text-align: center">
<p> Tabela 3: Tabela de avaliação com as padroẽs para todos os artefatos (Fonte: NomeAutor, 2023). </p>
</div>

</center>

Após o preenchimento da tabela padrão, o avaliador deve fazer uma tabela separada onde deve ter as questões do cenários especifico, veja mais na tabela 4.

<center>

| ID |        Questão        | Inspeção |
| :-: | :--------------------: | :--------: |
|  9  | Questão específica 1 |     🟢     |
| 10 | Questão específica 2 |     🟡     |
| 11 | Questão específica 3 |     🔴     |
| 12 | Questão específica 3 |     🔴     |
| ... |          ...          |    ...    |

<div style="text-align: center">
<p> Tabela 4: Tabela de avaliação com as questões específicas do artefato (Fonte: Lucas, 2023). </p>
</div>

</center>

## Preparação dos ajustes

Por fim, o avaliador deve fazer uma série de planejamentos para melhorar o artefato analisado.

### Tarefas

<center>

| ID Correção | Tarefa         |
| ------------- | -------------- |
| IDC1          | Ajustar x      |
| IDC2          | Incluir X      |
| IDC3          | Remover x      |
| IDC4          | Especificar x |

<div style="text-align: center">
<p> Tabela 5: Tabela do que precisa ser ajustado (Fonte: Lucas, 2023). </p>
</div>

</center>

## Acompanhamento

Para saber a porcentagem de aproveitamento do artefato, será utilizado a expressão da Figura 1, no qual a Tabela 5 apresenta o significado dessa legendas.

<center>

<img src="../../images/formulaCalculoAproveitamento.png"  alt="legenda da fórmula da figura 1"/>
<div style="text-align: center">

<p> Figura 1: Fórmula para calcular aproveitamento (Fonte: Gabriel, 2023). </p>
</div>

</center>

<center>

| Acrônimo | Descrição                     |
| --------- | ------------------------------- |
| QTDE      | Quantidade Total de Exigências |
| EC        | Exigências Completas           |

<div style="text-align: center">
<p> Tabela 6: Legenda da Figura 1 (Fonte: Gabriel, 2023). </p>
</div>

</center>

Nos checklists realizados e que serão descritos, podemos observar que:

- y/x exigências são atendidas;
- w/x exigências estão incompletas;
- z/x exigências estão erradas ou não foram realizadas.

onde x é a quantidade de exigências.

```vegalite
{
    "title": "Acompanhamento",
  "$schema": "https://vega.github.io/schema/vega-lite/v5.json",
  "description": "A simple donut chart with embedded data.",
  "data": {
    "values": [
      {"legenda": "Completo", "value": 15},
      {"legenda": "Incompleto", "value": 1},
      {"legenda": "Errado", "value": 4}
    ]
  },
  "mark": {"type": "arc", "innerRadius": 50, "tooltip": true},
  "encoding": {
    "theta": {"field": "value", "type": "quantitative"},
    "color": {
      "field": "legenda",
      "type": "nominal",
      "scale": {
        "domain": ["Completo", "Incompleto", "Errado"],
        "range": ["green", "yellow", "red"]
      }
    }
  }
}
```

Portanto, com base na formula apresentada, pode-se dizer que o aproveitamento deste artefato está em p% correto.

## Correção

### Cronograma

A tabela 7, contém o cronograma para a correção dos problemas identficiados nos artefatos.

<center>

| Data início | Data fim |
| ------------- | -------- |
| 20/06         | 05/07    |

<div style="text-align: center">
<p> Tabela 7: Cronograma de correção dos artefatos (Fonte: Lucas, 2023). </p>
</div>

</center>

Depois da verificação, o autor do artefato, indicado na tabela 2, deverá fazer as correções indicadas no planejamento dos ajustes e preencher a tabela 8, escrevendo o que ele fez para corrigir cada problema indentificado na verificação.

<center>

| ID Correção | Tarefa         | Ajuste                        |
| ------------- | -------------- | ----------------------------- |
| IDC1          | Ajustar x      | Foi ajustado x realizando...  |
| IDC2          | Incluir X      | Foi incluido x em ...         |
| IDC3          | Remover x      | Foi removido x ...            |
| IDC4          | Especificar x | X foi especificado melhor... |

<div style="text-align: center">
<p> Tabela 8: Tabela de ajustes feitos (Fonte: Lucas, 2023). </p>
</div>
</center>

## Referências

[1] Barbosa, S. D. J.; Silva, B. S. da; Silveira, M. S.; Gasparini, I.; Darin, T.; Barbosa, G. D. J. (2021) Interação Humano-Computador e Experiência do usuário. Autopublicação. ISBN: 978-65-00-19677-1.

[2] EICKELMANN, Nancy S. et al. An empirical study of modifying the Fagan inspection process and the resulting main effects and interaction effects among defects found, effort required, rate of preparation and inspection, number of team members and product 1st pass quality. In: 27th Annual NASA Goddard/IEEE Software Engineering Workshop, 2002. Proceedings. IEEE, 2002. p. 58-64.

## Histórico de versão

|    Data    | Versão |           Descrição           | Autor(es) | Revisor(es) |
| :--------: | :-----: | :------------------------------: | :-------: | :---------: |
| 17/06/2023 |   1.0   |      Criação do documento      |   Lucas   |   Gabriel   |
| 17/06/2023 |   1.1   |      Criação da fórmula      |  Gabriel  |    Lucas    |
| 05/07/2023 |   1.2   | Adicionando metodologia do Fagan |   Lucas   |   Gabriel   |
