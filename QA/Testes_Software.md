
• **O que são testes?**

» Testar é o processo de executar um programa de software com a **intenção de encontrar erros**

» É um processo de que engloba diversas atividades, incluindo a execução de **teste** junto da verificação dos resultados apenas uma delas. O processo do teste também inclui atividades como **planejamento** de testes, **análise, modelagem e implementação** dos testes, **relatórios** de progresso e resultados de testes e a avaliação da qualidade de um objeto de teste.

----

• **Conceitos Básicos | Terminologia**

↪ **Teste Estático**: Atividade de teste que contempla apenas a **revisão** ( manual ou automática ) de artefatos de teste ou do próprio código, porém **sem executar o software**

| **Tipos de testes estáticos** | **Exemplos de produtos testados estaticamente** |
| ----------------------------- | ----------------------------------------------- |
| Revisão                       | Requisitos e Casos de Uso                       |
| Acompanhamento                | Arquitetura e Design                            |
| Inspeção                      | Código Fonte                                    |
| --------------------          | Manual do usuário                               |
↪ **Teste Dinâmico**: Atividade de teste que envolve a **execução do software**, fornecendo entradas e avaliando as saídas e o comportamento apresentado.

| **Tipos de testes dinâmicos** |
| ----------------------------- |
| Funcionais                    |
| Não funcionais                |

↪ **Erro**: Também chamado de **engano** ( mistake ), é uma ação **humana** que produz o resultado incorreto.

↪ **Defeito**: Também chamado de **falta** ou **bug**, é uma imperfeição ou deficiência em um produto de trabalho ( código ou outro ) **causada por um erro**.

↪ **Falha**: Evento causado por um **defeito** no qual um sistema, ou parte dele, não executa uma função conforme os registros estabelecidos.

» **Erros** podem ocorrem por diversos fatores como:

- Ignorância/ Falta de conhecimento
- Pressão de tempo
- Negligência
- Inexperiência
- Complexidade
- Mal-entendido
- Falha de comunicação

• **Defeitos, Causa-raiz e efeitos**

» As **causas-raiz** de efeitos são as primeiras ações ou condições que contribuem no surgimento de um defeito.

» A análise de **causa-raiz** ( *Root-cause Analysis - RCA* ) é a atividade de investigar o defeito para identificar suas causas-raízes, de tal modo que possam ser implementadas melhorias que evitem que tais erros voltem a se repetiri no futuro.

» Os efeitos são as consequências das falhas, como reclamações de clientes, perdas de receita ou reputação entre outros.

↪ **Caso de teste**: Conjunto de pré-condições, procedimentos e resultados esperados usado pelo testador para determinar se o sistema **satisfaz** o requisito ou funciona corretamente.

↪ **Suíte de teste**: Conjunto de casos de teste, organizados em uma ordem lógica que devem ser executadas em uma dada atividade de teste.

↪ **Plano de teste**: Documento que descreve o escopo, a abordagem, recursos necessários e cronograma previstos para suas atividades de teste do software. Também indica as funções que serão testadas, quem executará as tarefas, o ambiente a ser usado, motivações das escolhas, riscos identificados e planos de contingência.

• **Diferenças entre Verificação e Validação**

| Validação                                                                                                                                    | Verificação                                                                                                               |
| -------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------- |
| Processo de avaliar o software com intuito de avaliar se ele satisfaz as necessidades e expectativas do usuário em seu ambiente de execução. | Processo de avaliar os documentos, artefatos e os software para certificar que eles atendem aos requisitos especificados. |

---------------------------------

• **Psicologia do Teste**

» Teste é um processo **destrutivo**, que irá apontar defeitos nos requisitos ou falhas no software, onde pode ser percebido como uma crítica pelos autores. O testador, sendo portador de más notícias com resultado de teste que não passou, pode ser mal interpretado, criando uma tensão entre desenvolvimento de qualidade, portando a **comunicação construtiva** é um fator vital para manter o equilíbrio em ambiente de trabalho.

----------------------------

• **Os 7 Princípios do Teste de Software**

↪**Teste mostra a presença de defeitos e não a sua ausência**: O teste reduz a probabilidade de defeitos não descobertos permanecerem no software, mas se nenhum defeito for encontrado o teste **não** é uma forma de correção.

↪ **Testes exaustivos são impossíveis**: Testar tudo ( todas as combinações de entradas e pré-condições ) não é viável, exceto em casos **triviais**. AO invés de testar exaustivamente, a análise de risco, as técnicas de teste e as prioridades devem ser usadas para concentrar esforços de teste.

↪ **O teste inicial economiza tempo de dinheiro**: Para encontrar antecipadamente os defeitos, as atividades de teste estático e dinâmico devem iniciar o mais cedo possível n o ciclo de vida de desenvolvimento de software. O teste inicial é por vezes referido como **shift-left**. Esse teste no início do ciclo de vida do desenvolvimento ajuda a reduzir ou eliminar alterações dispensiosas.

↪ **Defeitos se agrupam**: Um pequeno defeito de módulos geralmente contém a maioria dos defeitos descobertos durante o teste de pré-lançamento ou é responsável pela maioria das falhas operacionais. Agrupamento de defeitos previstos e agrupamento de defeitos observados reais em teste ou produção, são uma entrada importante em uma análise de risco usada para focar o esforço de teste. ( Mencionada no princípio **2** ).

↪ **Paradoxo do pesticida**: Se testes iguais forem repetidos diversas vezes, esses teste não encontraram novos defeitos. Para detectar novos defeitos, os testes existentes e dados de teste podem precisar ser alterados e novos testes precisam ser gravados. Em alguns casos, como o teste de **regressão** automatizado, o paradoxo do pesticida tem resultado benéfico, que é o número relativamente baixo de defeitos de regressão.

↪ **O teste depende do contexto**: O teste é feito de forma diferente em diferentes contextos. Por exemplo, o software de controle industrial de segurança crítica é testado de forma diferente de um aplicativo móvel de um comércio eletrônico. Também um teste de um projeto ágil é diferente de um projeto que um ciclo de vida sequencial.

↪ **Ausência de erros é uma ilusão**: Encontrar todos os defeitos possíveis é algo irrealista ( conforme os princípios 1 e 2 ). Além disso, é uma ilusão esperar que apenas encontrar e corrigir muitos defeitos garante o sucesso de um sistema, encontrar todos os defeitos possíveis ainda pode resultar em um sistema difícil de usar, que não atenda todas as necessidades e expectativas os usuários ou que seja inferior com a concorrência.


------

• **A regra de 10 Myers**

» A regra 10 de Myers sugere que é necessário cerca de **dez vezes** mais esforço para identificar, corrigir e verificar um defeito de software encontrado em uma determinada fase de testes do que teria sido necessário para prevenir esse defeito durante a fase anterior ou inicial de desenvolvimento. É a mesma ideia do **principio 3** citado acima e mais uma justificativa para o **shift-left**.

» Essa regra enfatiza que o foco dos testes e do **SQA** não se deve limitar a encontrar e corrigir defeitos, mais sim **preveni-los** desde o início.

• **Níveis de Teste**

↪ **Testes Unitários**: Consiste em escrever testes automatizados para testar **pequenas unidades de código**, geralmente funções ou métodos individuais, para garantir que eles funcionem como esperado. Testes unitários são geralmente escrito por **devs** e executados durante o processo de desenvolvimento de software.

↪ **Testes de Integração**: Se concentram em validar as **interações** entre componentes ou sistemas, garantindo eles trabalhem em conjunto corretamente e que suas interações não introduzam defeitos ou comportamentos inesperados.

↪ **Testes de Sistema**: Se concentram no **comportamento** e nas capacidades de todo um sistema ou produto, geralmente considerando as execuções das tarefas de **ponta-ponta** do sistema e seus comportamentos não funcionais exibidos ao exibidos ao executar tais tarefas.

↪ **Testes de Aceitação**: Relacionados às **necessidades do usuário**, requisitos e processos de negócios executados apara determinar se um sistema satisfaz ou não os critérios de aceitação e para permitir que o **usuário** aceita ou não a entrega.

• **Pirâmide de testes**

» É um modelo conceitual no desenvolvimento de software que orienta a proporcionalidade, a eficiência e o escopo do investimento em automação de testes.

• **Camadas da Pirâmide**

↪ **Unit Tests ( Base )**: Representa a maior quantidade de volume. Teste de unidades separadas de código, garantindo a execução rápida, baixo custo e detecção de falhas.

↪ **Integration Tests ( Meio )**: Teste de comunicação entre diferentes componentes, módulos ou serviços externos ( com banco de dados e APIs ). Executados em quantidade moderada.

↪ **UI Tests ( Topo )**: Validam o fluxo completo da aplicação atráves da interface gráfica, simulando a experiência do usuário final. Por serem frágeis e complexos existem em maior quantidade.

↪ **Manual Tests ( Nuvem )**: Ficam no topo fora do fluxo automatizado ideal. Devem ser pontuais, voltados para a exploração e validação de usabilidade humana, não para regressão continua.

-------------

• **Testes Funcionais e Não-Funcionais**

» Testes **funcionais** envolvem testes que avaliam as funções que o sistema deve executar. Os requisitos funcionais podem ser descritos em especificações de requisitos, de negócios, épicos, historia de usuários, casos de uso ou especificações funcionais. As funções são "**o que**" o sistema deve fazer.

» A cobertura funcional é a medida em que algum tipo de elemento funcional foi exercido por testes, ou seja, a porcentagem de requisitos funcionais que foram validadas por testes. O projeto e a execução de testes funcionais podem envolver habilidades ou conhecimentos especiais, como o conhecimento **específico** de um problema de negócios que o software resolve ou o papel específico que o software desempenha.

» **Alguns tipos de testes funcionais**:

- Teste de regressão
- Teste de confirmação
- Teste exploratório
- *Smoke Test*
- *Sanity Test*

• **Testes não funcionais**

» Avaliam características do software, como usabilidade, perfomance ou segurança. O teste não funcional valida "**Quão bem**" o sistema se comporta.

» A norma ISO 25010 define um modelo de oito caracteristicas de qualidade de software, com diversas classe e subclasses que podem ser objeto de testes **não-funcionais**:

- Teste de perfomance
- Teste de Compatibilidade
- Teste de Usabilidade
- Teste de Acessibilidade
- Teste de Confiabildiade
- Teste de Segurança
- Outros.

----------------------

• **Caixa Branca | Preta | Cinza 





•°» ↪→