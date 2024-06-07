# Angular_PDI

Plano de Desenvolvimento Individual (PDI) para Domínio de Angular
Objetivo Principal:
Dominar o framework Angular e suas melhores práticas até 13 de dezembro de 2024, com foco em implementação eficiente, manutenção de código, e entrega de soluções de alta qualidade.

Cronograma Detalhado:
Junho 2024
Meta: Compreender e aplicar os fundamentos do Angular.

Semana 1-2: Introdução e Configuração do Ambiente

Tarefas:
Instalar Node.js e Angular CLI:
Baixar e instalar o Node.js a partir do site oficial.
Instalar Angular CLI globalmente usando o comando npm install -g @angular/cli.
Criar um novo projeto Angular:
Utilizar o comando ng new my-app para criar um novo projeto.
Entender a estrutura de pastas e arquivos gerada automaticamente.
Configurar o ambiente de desenvolvimento:
Configurar o editor de código (recomendado: Visual Studio Code).
Instalar extensões úteis como Angular Language Service, TSLint, etc.
Referências:
Instalação e Configuração
Semana 3-4: Componentes, Templates e Data Binding

Tarefas:
Criar Componentes:
Utilizar o comando ng generate component component-name para gerar novos componentes.
Entender o ciclo de vida dos componentes e os métodos ngOnInit, ngOnChanges, etc.
Data Binding:
Interpolation: Exibir dados de componentes nas templates usando {{}}.
Property Binding: Vincular valores a propriedades de elementos HTML [property]="value".
Event Binding: Capturar eventos do usuário (event)="handler($event)".
Two-Way Binding: Usar [(ngModel)] para vinculação bidirecional em formulários.
Referências:
Componentes
Data Binding
Julho 2024
Meta: Dominar Diretivas e Pipes, Serviços e Injeção de Dependências.

Semana 1-2: Diretivas e Pipes

Tarefas:
Diretivas:
Estruturais: Criar e utilizar diretivas como *ngIf, *ngFor.
Atributo: Criar diretivas personalizadas para manipular o comportamento e aparência de elementos.
Pipes:
Usar pipes integrados como DatePipe, CurrencyPipe, etc.
Criar pipes customizados usando o comando ng generate pipe pipe-name.
Referências:
Diretivas
Pipes
Semana 3-4: Serviços e Injeção de Dependências

Tarefas:
Serviços:
Criar serviços usando o comando ng generate service service-name.
Injetar serviços em componentes e outros serviços.
Injeção de Dependências:
Entender a hierarquia de provedores de serviços.
Usar providedIn no @Injectable para registro de serviços.
HttpClient:
Configurar o módulo HttpClientModule no AppModule.
Realizar requisições HTTP GET, POST, PUT, DELETE.
Referências:
Serviços e Injeção de Dependências
HttpClient
Agosto 2024
Meta: Gerenciamento de Estado, Roteamento e Navegação.

Semana 1-2: Roteamento e Navegação

Tarefas:
Configuração de Roteamento:
Configurar rotas no AppRoutingModule.
Criar rotas aninhadas e parâmetros de rotas.
Lazy Loading:
Configurar lazy loading para módulos pesados.
Utilizar loadChildren no roteador para carregamento tardio.
Referências:
Roteamento
Semana 3-4: Gerenciamento de Estado

Tarefas:
NgRx:
Introdução ao gerenciamento de estado com NgRx Store.
Configurar Store, Actions, Reducers e Selectors.
Implementar um pequeno projeto para gerenciar o estado da aplicação.
Referências:
NgRx
Setembro 2024
Meta: Testes e Performance.

Semana 1-2: Testes

Tarefas:
Testes Unitários:
Escrever testes unitários para componentes e serviços utilizando Jasmine.
Configurar e executar testes com Karma.
Testes de Integração e E2E:
Escrever testes de integração para componentes que interagem entre si.
Utilizar Protractor para testes end-to-end.
Referências:
Testes
Semana 3-4: Performance

Tarefas:
Otimização:
Implementar técnicas de lazy loading e prefetching.
Usar ChangeDetectionStrategy para melhorar o desempenho.
Analisar e otimizar a performance com o Angular DevTools.
Referências:
Otimização de Performance
Outubro 2024
Meta: Formulários, Validação e Gerenciamento de Estados Avançado.

Semana 1-2: Formulários e Validação

Tarefas:
Formulários Reativos:
Criar formulários usando FormBuilder e FormGroup.
Implementar validações síncronas e assíncronas.
Formulários Template-Driven:
Utilizar diretivas ngForm, ngModel para criar formulários.
Aplicar validações customizadas.
Referências:
Formulários
Semana 3-4: Gerenciamento de Estados Avançado

Tarefas:
NgRx Avançado:
Implementar efeitos (Effects) para lidar com operações assíncronas.
Utilizar Entity State Adapter para gerenciar coleções de entidades.
Referências:
NgRx
Novembro 2024
Meta: Integração Contínua e Deploy.

Semana 1-2: Integração Contínua

Tarefas:
Configuração de CI/CD:
Configurar pipelines de CI/CD com Jenkins, GitHub Actions ou outra ferramenta de escolha.
Automatizar testes e builds no processo de integração contínua.
Referências:
CI/CD
Semana 3-4: Deploy

Tarefas:
Deploy:
Realizar deploy da aplicação em diferentes ambientes (desenvolvimento, staging, produção).
Otimizar a aplicação para produção utilizando ng build --prod.
Monitoramento:
Implementar ferramentas de monitoramento e logging.
Referências:
Deployment
Dezembro 2024
Meta: Revisão, Feedback e Documentação.

Semana 1-2: Revisão e Feedback

Tarefas:
Revisão do Progresso:
Revisar todas as tarefas completadas ao longo do PDI.
Identificar áreas de melhoria e pontos fortes.
Feedback:
Solicitar feedback dos colegas de equipe e do coordenador.
Implementar melhorias com base no feedback recebido.
Referências:
Feedback e Melhoria Contínua
Semana 3: Documentação

Tarefas:
Documentação do Projeto:
Documentar o projeto de forma abrangente, incluindo arquitetura, decisões de design, e desafios enfrentados.
Preparar uma apresentação do progresso e realizações para compartilhar com a equipe.
Referências:
Documentação
