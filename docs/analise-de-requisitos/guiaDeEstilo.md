# Guia de Estilo

## Introdução

O Guia de Estilo é um importante documento que reúne as principais decisões de design adotadas em um projeto. Ele é criado com o objetivo de garantir que essas decisões não sejam perdidas e possam ser facilmente acessíveis para a implementação no produto final e reutilização durante as etapas de extensão do produto.

Além disso, o Guia de Estilo também pode ser utilizado como um meio de comunicação efetivo entre as equipes de design e desenvolvimento, facilitando o alinhamento das estratégias e objetivos do projeto.

No caso específico do sítio eletrônico Wikipedia, o Guia de Estilo será desenvolvido com base nas Metas de Usabilidade, seguindo o ciclo de vida para engenharia de usabilidade de Mayhew [1]. Isso garantirá que a usabilidade do site seja uma prioridade durante todo o processo de desenvolvimento, desde o planejamento até a implementação final.

### Objetivo

Seu objetivo é reunir e registrar as principais decisões de design tomadas durante o processo de desenvolvimento, garantindo que elas não sejam perdidas e possam ser facilmente acessíveis para a implementação no produto final e reutilização em futuras etapas de extensão do produto.

Além disso, o Guia de Estilo também tem como objetivo facilitar a comunicação e o alinhamento entre as equipes de design e desenvolvimento. Ele fornece uma referência clara e consistente para o estilo visual, a tipografia, as cores, os elementos de interface e outros aspectos visuais e funcionais do projeto. Isso ajuda a garantir que a equipe de desenvolvimento implemente as decisões de design de forma consistente e coerente, o que é especialmente importante em projetos complexos e colaborativos.

Outro objetivo importante do Guia de Estilo é melhorar a usabilidade do produto final. O guia pode incluir diretrizes específicas para a interface do usuário, como a organização dos elementos da tela, a forma como o usuário navega pelo site e o feedback do usuário. Ao garantir que o design e a funcionalidade do produto sejam intuitivos e fáceis de usar, o Guia de Estilo pode ajudar a melhorar a experiência do usuário e a aumentar a satisfação e a retenção do cliente.

Por fim, o Guia de Estilo pode ser uma ferramenta valiosa para manter a consistência da marca e a identidade visual do produto. Ele pode incluir diretrizes para o uso da marca, como a cor e a tipografia da logomarca, garantindo que o produto final reflita a identidade da marca de forma consistente e coerente.

### Organização e contéudo do guia de estilo

1. Introdução (com Objetivo do guia de estilo, Organização e conteúdo do guia de estilo, Públicoalvo do guia de estilos (programadores, gerentes, equipe de suporte), Como utilizar o guia (em produção e manutenção), Como manter o guia.
2. Resultados de análise • Descrição do ambiente de trabalho do usuário
3. Elementos de interface • Disposição espacial e grid • Janelas • Tipografia • Cores
4. Elementos de interação - • Estilos de interação • Seleção de um estilo • Aceleradores (teclas de atalho)
5. Elementos de ação • Preenchimento de campos • Seleçã • Ativação
6. Vocabulário e padrões • Terminologia • Tipos de tela (para tarefas comuns) • Sequências de diálogos (e.g., para feedback ou confirmação de uma operação)

### Público alvo do guia de estilo (programadores, gerentes, designers, etc)

O público-alvo do Guia de Estilo são as equipes envolvidas no desenvolvimento do projeto, incluindo designers, desenvolvedores, gerentes de projeto e outros profissionais que trabalham no produto. O guia fornece diretrizes claras e consistentes para a implementação das decisões de design, garantindo que a equipe trabalhe de forma alinhada e eficiente. Além disso, o Guia de Estilo pode ser usado como uma referência para futuros desenvolvimentos e para garantir que a identidade visual e a marca do produto sejam mantidas consistentes em todas as plataformas e canais.

### Como manter o guia

Para manter a eficácia do Guia de Estilo, é importante atualizá-lo regularmente com novas decisões de design e mudanças na identidade visual ou nas diretrizes de marca. A equipe de design deve garantir que todas as mudanças e atualizações sejam documentadas no Guia de Estilo e que as informações estejam sempre acessíveis e atualizadas. Além disso, é importante educar e conscientizar a equipe de desenvolvimento sobre o uso e a importância do Guia de Estilo, garantindo que ele seja seguido de forma consistente em todas as etapas do projeto. Ao manter o Guia de Estilo atualizado e fazer com que a equipe de desenvolvimento o siga adequadamente, é possível garantir a consistência do design e da identidade visual do produto, melhorar a eficácia da equipe e a satisfação do cliente.

## Resultados de análise
### Descrição de ambiente de trabalho do usuário

O objetivo do usuário ao acessar a Wikipedia é obter informações de forma clara e objetiva. Por isso, é importante que o site apresente um layout simples e organizado, para que o usuário possa encontrar facilmente o que está procurando. Além disso, é fundamental que o conteúdo dos artigos seja de fácil compreensão e apresentado de forma coerente, com informações precisas e confiáveis. É importante que os links para outras páginas da Wikipedia estejam disponíveis e facilmente acessíveis, para que o usuário possa aprofundar seus conhecimentos sobre o assunto que está pesquisando.

## Elementos de interface

### Disposição espacial e grid

O site possui um loyout em que os elementos são divididos em sessões e estes são centralizados na página. A Figura 1 a seguir demonstra a disposição dos elementos da página principal e inicial do sistema.

<img src="/images/guiaEstilo/layoutGrid.png"/>

<div style="text-align: center">
    <p> Figura 1: Layout (Fonte: Autores. 2023).</p>
</div>

### Janelas

São diversas as janelas contidas no site, porém, pode-se destacar as principais, como a página inicial, a página de um artigo qualquer, e a página de edição de um artigo. As páginas citadas podem ser visualizadas na Figura 2, Figura 3 e Figura 4.

<img src="/images/guiaEstilo/telaArtigo.png"/>

<div style="text-align: center">
    <p> Figura 2: Página de um artigo (Fonte: Wikipedia. 2023).</p>
</div>

<img src="/images/guiaEstilo/telaInicial.png"/>


<div style="text-align: center">
    <p> Figura 3: Página inicial (Fonte: Wikipedia. 2023).</p>
</div>

<img src="/images/guiaEstilo/telaEdicao.png"/>

<div style="text-align: center">
    <p> Figura 4: Página de edição de um artigo (Fonte: Wikipedia. 2023).</p>
</div>

### Tipografia

O site utiliza o Sans Serif (Figura 5) como família de fonte com tamanho de 16px.

<img src="/images/guiaEstilo/fonte.png"/>

<div style="text-align: center">
    <p> Figura 5: Tipografia do Sans serif (Fonte: Microsoft. 2023).</p>
</div>

### Cores

O site utiliza as cores azul e branco, como pode ser visto na Figura 6.

<img src="/images/guiaEstilo/paleta.png"/>

<div style="text-align: center">
    <p> Figura 6: Paleta de cores da wikipedia (Fonte: Autores. 2023).</p>
</div>

## Elementos de interação

### Estilos de interação

### Seleção de um estilo

### Aceleradores (teclas de atalho)

## Elementos de ação

### Preenchimento de campos

### Seleção

### Ativação

## Vobabulário e padrões

### Terminologia

### Tipos de tela (para tarefas comuns)

### Sequências de dialógos (para feedback ou confirmação de operação)
