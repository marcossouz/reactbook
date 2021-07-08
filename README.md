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


# Tabela de conteúdo

- <a href="#cap1">Capítulo 1 - Hello World</a>
- <a href="#cap2">Capítulo 2 - A vida de um componente</a>
- <a href="#cap3">Capítulo 3 - Excel: um componente de tabela elegante</a>
- <a href="#cap4">Capítulo 4 - JSX</a>
- <a href="#cap5">Capítulo 5 - Preparando-se para o desenvolvimento de aplicações</a>
- <a href="#cap6">Capítulo 6 - Construindo uma aplicação</a>
- <a href="#cap7">Capítulo 7 - Lint, Flow, Testar, Repetir</a>
- <a href="#cap8">Capítulo 8 - Flux</a>

# Checklist e detalhamento de conteúdo

- [x] <span id="cap1">Capítulo 1</span> - Hello World
    - [x] Instalação
    - [x] Hello World com a React
    - [x] O que aconteceu?
    - [x] React.DOM.*
    - [x] Atributos especiais do DOM
    - [x] Extensão de navegador React e DevTools
    - [x] A seguir: componentes personalizados
- [x] <span id="cap2">Capítulo 2</span> - A vida de um componente
    - [x] O mínimo necessário
    - [x] Propriedades
    - [x] propTypes
    - [x] Valores default das propriedades
    - [x] Estado
    - [x] Um componente textarea com estado
    - [x] Uma observação sobre eventos do DOM
    - [x] Tratamento de eventos na React
    - [x] Propriedades no estado inicial: um antipadrão
    - [x] Acessando o componente de fora
    - [x] Alterando as propriedades durante a execução
    - [x] Métodos de ciclo de vida
      - [x] compoentWillUpdate()
        - Executa antes do método render() de seu componente ser chamado novamente (como resultado de mudanças nas propriedades ou no estado).
      - [x] componentDidUpdate()
        - Executado após o método render() ter sido concluído e as novas alterações no DOM subjacente terem sido aplicadas.
      - [x] componentWillMount()
        - Executado antes de o nó ser inserido no DOM
      - [x] componentDidMount()
        - Executado depois que o nó é inserido no DOM
      - [x] componentWillUnmount()
        - Executado imediatamente antes de o componente ser removido do DOM.
      - [x] shouldComponentUpdate(newProps, newState)
        - Esse método é chamado antes de componentWillUpdate() e dá a você a oportunidade de executar um return false; e cancelar a atualização, o que significa que ser método render() não será chamado.
    - [x] Exemplo de ciclo de vida: fazendo log de tudo
    - [x] Exemplo de ciclo de vida: usando uma mixin
    - [x] Exemplo de ciclo de vida: usando um componente-filho
    - [x] Ganho de desempenho: evitando atualização de componentes
    - [x] PureRenderMixin

- [ ] <span id="cap3">Capítulo 3</span> - Excel: um componente de tabela elegante
    - [x] Primeiros dados
    - [x] Laço para cabeçalho da tabela
    - [x] Depurando o aviso do controle
    - [x] Adicionando o conteúdo de `<td>`
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

- [ ] <span id="cap4">Capítulo 4</span> - JSX
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

- [ ] <span od="cap5">Capítulo 5</span> - Preparando-se para o desenvolvimento de aplicações
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

- [ ] <span id="cap6">Capítulo 6</span> - Construindo uma aplicação
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


- [ ] <span id="cap7">Capítulo 7</span> - Lint, Flow, Testar, Repetir
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


- [ ] <span id="cap8">Capítulo 8</span> - Flux
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
