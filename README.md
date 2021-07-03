<h1 align="center">Primeiros passos com React</h1>

<p align="center">
Livro: Primeiros Passos com React - Construindo aplicações web, Novatec, Stoyan Stefanov.

Este livro tem como foco conhecer a React do ponto de vista do desenvolvimento web. 
<strong>Nos três primeiros capítulos</strong>, você começará simplemente com um arquivo HTML em branco e continuará desenvolvendo-o a partir daí. Isso Permite que você se concentre em conhecer a React, e não nas novas sintaxes ou ferramentas auxiliares.
<strong>O capítulo 4</strong> apresenta JSX, que é uma tecnologia separada e opcional, geralmente usada em conjunto com a React.
<strong>A partir daí</strong> saberemos o que é necessário para desenvolver uma aplicação do mundo real e conhecer ferramentas adicionais que poderão ajudar no caminho. 

- Ferramentas de empacotamento (Browserify)
- Testes de unidade (Jest)
- Linting (ESLint)
- tipos (Flow)
- Organização de fluxo de dados na aplicação (Flux)
- dados imutáveis (Immutable.js)

</p>

# Conteúdo e andamento

- [ ]  Capítulo 1 - Hello World
    - [x] Instalação
    - [ ] Hello World com a React
    - [ ] O que aconteceu?
    - [ ] React.DOM.*
    - [ ] Atributos especiais do DOM
    - [ ] Extensão de navegador React e DevTools
    - [ ] A seguir: componentes personalizados
    
- [ ] Capítulo 2 - A vida de um componente
    - [ ] O mínimo necessário
    - [ ] Propriedades
    - [ ] propTypes
    - [ ] Valores default das propriedades
    - [ ] Estado
    - [ ] Um componente textarea com estado
    - [ ] Uma observação sobre eventos do DOM
    - [ ] Tratamento de eventos na React
    - [ ] Propriedades no estado inicial: um antipadrão
    - [ ] Acessando o componente de fora
    - [ ] Alterando as propriedades durante a execução
    - [ ] Métodos de ciclo de vida
    - [ ] Exemplo de ciclo de vida: fazendo log de tudo
    - [ ] Exemplo de ciclo de vida: usando uma mixin
    - [ ] Exemplo de ciclo de vida: usando um componente-filho
    - [ ] Ganho de desempenho: evitando atualização de componentes
    - [ ] PureRenderMixin

- [ ] Capítulo 3 - Excel: um componente de tabela elegante
    - [ ] Primeiros dados
    - [ ] Laço para cabeçalho da tabela
    - [ ] Depurando o aviso do controle
    - [ ] Adicionando o conteúdo de `<td>`
    - [ ] Como podemos melhorar o componente?
    - [ ] Ordenação
    - [ ] Como podemos melhorar o componehte?
    - [ ] Pistas sobre ordenação UI
    - [ ] Editando dados
    - [ ] Célula em que é possível editar
    - [ ] Célula com campo de entrada
    - [ ] Salvando
    - [ ] Conclusão e diferenças com o DOM virtual
    - [ ] Pesquisa
    - [ ] Estado e UI
    - [ ] Filtrando o conteúdo
    - [ ] Como podemos melhorar a pesquisa?
    - [ ] Reprodução instantânea
    - [ ] Como podemos melhorar a reprodução?
    - [ ] Uma implementação alternativa?
    - [ ] Download dos dados da tabela

- [ ] Capítulo 4 - JSX
    - [ ] Hello JSX
    - [ ] Trapiração do JSX
    - [ ] Babel
    - [ ] Lado do cliente
    - [ ] Sobre a transformação de JSX
    - [ ] JavaScript em JSX
    - [ ] Espaço em branco no JSX
    - [ ] Comentários no JSX
    - [ ] Entidades HTML
    - [ ] AntiXSS
    - [ ] Propagação de atributos
    - [ ] Propagação de atributos de pai para filho
    - [ ] Devolvendo vários nós no JSX
    - [ ] Diferenças entre JSX e HTML
    - [ ] Sem class nem for
    - [ ] style é um objeto
    - [ ] Tags de fechamento
    - [ ] Atributos camelCase
    - [ ] JSX e formulários
    - [ ] Handler onChange
    - [ ] value versus defaultValue
    - [ ] Valor de `<textarea>`
    - [ ] Valor de `<select>`
    - [ ] O componente Excel em JSX


- [ ] Capítulo 5 - Preparando-se para o desenvolvimento de aplicações
    - [ ] Uma aplicação bolerplate
    - [ ] Arquivos e pastas
    - [ ] index.html
    - [ ] CSS
    - [ ] JavaScript
    - [ ] JavaScript: modernizado
        - [ ] Módulos
        - [ ] Módulos ECMAScript
        - [ ] Reunindo tudo
    - [ ] Instalando os pré-requisitos
    - [ ] Node.js
    - [ ] Browserify
    - [ ] Babel
    - [ ] React e outros pacotes
    - [ ] Vamos fazer a construção
    - [ ] Transpilar o JavaScript
    - [ ] Empacotar o JavaScript
    - [ ] Empacotar o CSS
    - [ ] Resultados!
    - [ ] Versão para Windows
    - [ ] Contruindo o desenvolvimento
    - [ ] Implantação
    - [ ] Prosseguindo

- [ ] Capítulo 6 - Construindo uma aplicação
    - [ ] Whinepad v0.0.1
        - [ ] Configuração
        - [ ] Comece a programar
    - [ ] Os componentes
        - [ ] Configuração
        - [ ] Descoberta
        - [ ] Componentes `<Button>`
        - [ ] Button.css
        - [ ] Button.js
        - [ ] Formulários
        - [ ] `<Suggest>`
        - [ ] Componente `<Rating>`
        - [ ] Uma "Factory" `<FormInput>`
        - [ ] `<Form>`
        - [ ] `<Actions>`
        - [ ] Diálogos
    - [ ] Configuração da aplicação
    - [ ] `<Excel>`: novo e melhorado
    - [ ] `<Whinepad>`
    - [ ] Concluindo


- [ ] Capítulo 7 - Lint, Flow, Testar, Repetir
    - [ ] package.json
        - [ ] Configurando o Babel
        - [ ] scripts
    - [ ] ESLint
        - [ ] Configuração
        - [ ] Execução
        - [ ] Todas as regras
    - [ ] Flow
        - [ ] Configuração
        - [ ] Execução
        - [ ] Inscrevendo-se para verificação de tipos
        - [ ] Conrrigindo `<Button>`
        - [ ] app.js
        - [ ] Mais sobre verificação de tipos em propriedades e no estado
        - [ ] Exportação/importação de tipos
        - [ ] Casting de tipo
        - [ ] Invariantes
    - [ ] Testes
        - [ ] Configuração
        - [ ] Primeiro Teste
        - [ ] Primeiro Teste com a React
        - [ ] Testando o componente `<Button>`
        - [ ] Testando `<Actions>`
        - [ ] Mais interações simuladas
        - [ ] Testando interações completas
        - [ ] Cobertura


- [ ] Capítulo 8 - Flux
    - [ ] A grande ideia
    - [ ] Analisando o Whinepad novamente
    - [ ] A Store
        - [ ] Eventos da Store
        - [ ] Usando Store em `<Whinepad>`
        - [ ] Usando Store em `<Excel>`
        - [ ] Usando Store em `<Form>`
        - [ ] Definindo o limite
    - [ ] Actions
        - [ ] CRUDActions
        - [ ] Pesquisando e ordenando
        - [ ] Usando Actions em `<Whinepad>`
        - [ ] Usado Actions em `<Excel>`
    - [ ] Recapitulando o Flux
    - [ ] Imutável
        - [ ] Dados imutáveis na Store
        - [ ] Manipulação de dados imutáveis
