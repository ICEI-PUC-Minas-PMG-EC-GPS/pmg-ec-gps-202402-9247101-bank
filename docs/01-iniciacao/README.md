# Iniciação

> A fase de iniciação, em gerência de projetos, é o estágio que estabelece as bases para o sucesso do empreendimento. 
> Durante essa etapa, os objetivos definidos, identificando-se suas metas, escopo, partes interessadas (*stakeholders*) e restrições. 
> É o momento em que a viabilidade do projeto é avaliada, analisando-se recursos necessários, riscos potenciais e benefícios esperados.
> Nesta etapa é elaborado o Termo de Abertura do Projeto (TAP).
> Essa fase serve como um alicerce estratégico, proporcionando uma compreensão abrangente do que o projeto busca alcançar e delineando as diretrizes que orientarão as etapas subsequentes. 
> O sucesso na fase de iniciação contribui significativamente para a eficácia do gerenciamento de projetos como um todo.

# Estrutura do Documento

- [Fase de Iniciação](#iniciação)
- [Introdução](#introdução)
  - [Problema](#problema)
  - [Objetivos](#objetivos)
  - [Justificativa](#justificativa)
  - [Critérios de Sucessos](#critérios-de-sucesso)
- [Partes Interessadas](#partes-interessadas)
  - [Identificação das Partes Interessadas](#identificação-das-partes-interessadas)
  - [Avaliação das Partes Interessadas](#avaliação-das-partes-interessadas)
- [Termo de Abertura do Projeto](#termo-de-abertura-do-projeto)
  - [Estimativa de Custo](#estimativa-de-custo)
  - [Estimativa de Prazo](#estimativa-de-prazo)
  - [Escopo Preliminar e Premissas](#escopo-preliminar-e-premissas)
    - [Requisitos Funcionais](#requisitos-funcionais)
    - [Requisitos Não Funcionais](#requisitos-não-funcionais)
    - [Restrições](#restrições)
    - [Contra-Escopo](#contra-escopo)
    - [Condições para início do Projeto](#condições-para-início-do-projeto)
  - [Marcos Agendados e Entregas](#marcos-agendados-e-entregas)
- [Metodologia](#metodologia)
  - [Divisão de Papéis](#divisão-de-papéis)
  - [Ferramentas](#ferramentas)

# Introdução
A aplicação de controle financeiro proposta é uma solução digital desenvolvida para auxiliar indivíduos e empresas na gestão eficaz de suas finanças. Com um conjunto robusto de funcionalidades, a aplicação visa fornecer uma visão clara e detalhada das finanças pessoais e empresariais, permitindo o acompanhamento preciso de despesas, receitas e orçamentos. Este sistema pretende apoiar a tomada de decisões financeiras informadas, através de recursos que incluem dashboards visuais, relatórios detalhados, e integração com contas bancárias e cartões de crédito.

## Problema
No contexto atual, muitos indivíduos e pequenas empresas enfrentam desafios significativos na administração de suas finanças. A falta de uma visão consolidada e a dificuldade em monitorar e categorizar despesas e receitas frequentemente resultam em planejamento financeiro inadequado e falta de controle sobre os gastos. Além disso, a ausência de ferramentas eficazes para a definição e acompanhamento de metas financeiras e para a gestão de dívidas e investimentos contribui para a ineficiência financeira e o desperdício de recursos.

## Objetivos
O objetivo da aplicação é facilitar o acompanhamento financeiro ao oferecer uma visão consolidada das finanças pessoais e/ou empresariais por meio de dashboards visuais, que apresentam contas, saldos, despesas e receitas de maneira clara e intuitiva.

## Justificativa
A implementação de uma aplicação de controle financeiro é justificada pela necessidade crescente de soluções que oferecem maior transparência e controle sobre as finanças.

## Critérios de Sucesso
- Aplicabilidade real: a solução deve demonstrar eficácia na gestão financeira real, ajudando usuários a monitorar e controlar suas finanças com precisão. Isso será medido pela adoção contínua da aplicação e pela capacidade de resolver problemas financeiros específicos enfrentados pelos usuários.

- Aceitação do público alvo: será avaliada através de feedback positivo dos usuários, incluindo indivíduos, pequenas empresas e consultores financeiros. O sucesso será indicado pelo nível de satisfação do usuário, a frequência de uso da aplicação e a adoção generalizada no mercado-alvo.
  
- Resultados positivos:  incluirão melhorias mensuráveis na gestão financeira dos usuários, como redução de despesas desnecessárias, melhor planejamento orçamentário e atingimento de metas financeiras.

# Partes Interessadas

> Relacione as partes interessadas no seu projeto. 
> Você deve descrever as partes interessadas e indicar qual o nível de influência em relação ao projeto.
> Indique as principais pessoas (clientes, fornecedores, etc), indicando possíveis expectativas, nível de influência e possível importância para o sucesso do projeto.

> Você pode utilizar como referência o seguinte documento:
> [Registro de Partes Interessadas](artefatos/registro-partes-interessadas.xlsx)

## Identificação das Partes Interessadas

| Nome            | Posição / Cargo | Papel Projeto | E-mail      | Telefone    |
|-----------------|-----------------|---------------|-------------|-------------|
|Clientes Individuais e Famílias  |Usuários da Aplicação                 |Usuários principais que determinarão a aceitação da aplicação             |            |             |
|Pequenos Empreendedores e Freelancers             |Usuários da aplicação                  |Utilizadores que influenciam a adoção e feedback sobre a aplicação              |             |             |
|Gestores/Consultores Financeiros                 |Profissionais financeiros              |Usuários que podem recomendar e validar a aplicação no mercado empresarial             |             |             |
|Desenvolvedores e Fornecedores de Serviços                 |Equipe de desenvolvimento e suporte                 |Responsáveis pelo desenvolvimento, manutenção e atualização da aplicação               |             |             |
|                 |                 |               |             |             |
|                 |                 |               |             |             |
|                 |                 |               |             |             |
|                 |                 |               |             |             |


> Opções de identificação dos stakeholders:
> - Nome: nome da parte interessada (inclui funcionários da empresa e do cliente)
> - Posição / Cargo: Identificação do cargo da parte interessada
> - - Ex.: Gerente de TI, Funcionário da Linha de Produção, Presidente, Analista de Sistema do Cliente, Desenvolvedor, etc.
> - Papel no Projeto: Papel da pessoa no projeto
> - - Ex.: Desenvolvedor, Analista de Requisitos, Analista de Testes, Product Owner, etc.
> - E-mail: E-mail do Stakeholder (*não utilizar informações pessoais*)
> - Telefone: Telefone do Stakeholder, incluindo WhatsApp (*não utilizar informações pessoais*)

## Avaliação das Partes Interessadas

| Nome            | Expectativa no Projeto | Influência    | Importância / Poder | Apoio       | Observações   |
|-----------------|------------------------|---------------|---------------------|-------------|---------------|
|Clientes Individuais e Famílias                |Facilidade de uso, segurança dos dados, funcionalidades de orçamento e planejamento                      |Baixa               |Alta                     |Neutro             |               |
|Empreendedores/Freelancers                 |Integração com contas bancárias, relatórios detalhados, gestão de receitas e despesas                        |Baixa               |Alta                     |Positivo             |               |
|Gestores/Consultores Financeiros                 |Ferramentas para orçamento e fluxo de caixa, relatórios avançados                       |Alta               |Média                     |Positivo             |               |
|Desenvolvedores e Fornecedores de Serviços           |Comunicação clara sobre requisitos, cronograma realista, manutenção eficiente                        |Alta               |Alta                     |Positivo             |               |
|                 |                        |               |                     |             |               |
|                 |                        |               |                     |             |               |
|                 |                        |               |                     |             |               |
|                 |                        |               |                     |             |               |

> Opções de avaliação:
> - Expectativa: descrição da expectativa da parte interessada no projeto.
> - - Ex.: Diminuição do tempo de realização das tarefas, aumento da produtividade, aumento da satisfação do cliente, etc.
> - Influência: Alta, Média, Baixa
> - Importância: Alta, Média, Baixa
> - Apoio: Positivo, Negativo, Neutro
> - Observações: Informações adicionais, para o cliente.

```diff
+ Tarefa 01
+ Fim da seção a ser atualizada.
```


-----
```diff
+ Tarefa 02
+ Termo de Abertura do Projeto
```

# Termo de Abertura do Projeto

> O Termo de Abertura do Projeto (TAP) representa o ponto de partida oficial para o empreendimento. 
> Ele sintetiza de maneira clara e concisa os objetivos, escopo, partes interessadas envolvidas, entregas esperadas, cronograma preliminar e recursos necessários para a execução bem-sucedida do projeto. 
> O TAP funciona como um contrato inicial entre a equipe do projeto e as partes interessadas, estabelecendo as bases para uma compreensão compartilhada dos propósitos e limites do projeto. 
> Ao delinear esses elementos de forma detalhada, o Termo de Abertura do Projeto (TAP) fornece uma direção sólida para orientar as atividades subsequentes, facilitando a gestão eficaz do projeto desde o início até o encerramento. 
> Essa documentação garante a clareza, alinhamento e comprometimento de todos os envolvidos, contribuindo assim para o sucesso do projeto.

> Você pode utilizar como referência o seguinte documento:
> [Termo de Abertura do Projeto](artefatos/termo-abertura-projeto.docx)

## Estimativa de Custo

Esta tabela fornece uma visão geral dos custos estimados associados ao desenvolvimento da aplicação:

> A avaliação da viabilidade econômica busca determinar a sustentabilidade financeira e o retorno sobre o investimento do empreendimento. 
> Este processo envolve a análise dos custos associados ao projeto, incluindo investimentos iniciais, despesas operacionais e potenciais custos de manutenção. 
> Simultaneamente, são examinados os benefícios esperados, como receitas, economias de custos e ganhos tangíveis e intangíveis. 
> A elaboração de projeções financeiras realistas e a aplicação de métricas como o Valor Presente Líquido (VPL) e a Taxa Interna de Retorno (TIR) contribuem para uma avaliação abrangente da viabilidade econômica do projeto. 
> Este processo permite que os gestores de projeto e as partes interessadas tomem decisões informadas sobre a continuidade, ajustes ou mesmo a interrupção do projeto, garantindo uma alocação eficiente de recursos e maximizando os benefícios econômicos esperados.

......  ATUALIZE OS ITENS DE CUSTO DO SISTEMA. ADICIONE NOVOS OU SUBDIVIDA ITENS, CASO NECESSÁRIO ......

| Item de Custo           | Descrição | Qtd. horas | Valor / hora | Valor total |
|-------------------------|-----------|------------|--------------|-------------|
| Recursos Humanos        |Desenvolvimento e design da aplicação; análise de requisitos e testes           | 800           | R$ 150            | R$ 120.000            |
| Hardware                |Servidores e equipamentos de desenvolvimento           | 1           |R$ 5.000              | R$ 5.000            |
| Serviços de Rede        |Configuração e manutenção de rede para testes e desenvolvimento           |40            |R$ 200              | R$ 8.000            |
| Hospedagem e Nuvem      |Custos de servidores na nuvem e armazenamento           |6380(Plano Semestral)           | R$ 1,64             | R$ 10.500            |
| Software de terceiros   |Licenças e ferramentas de desenvolvimento (IDE, bibliotecas, etc.)           |  1          |   R$ 10.000           | R$ 10.000            |
| Serviços e treinamento  |Treinamento da equipe e suporte técnico adicional           | 20           |R$ 250              | R$ 5.000            |
| **Total Geral**         |   N/A        |7242            |R$20.351,64              | R$158.500            |


## Estimativa de Prazo

......  COLOQUE AQUI O SEU TEXTO ......

> A estimativa de prazo orienta tanto o cliente quanto a equipe de desenvolvimento do projeto em termos do tempo necessário para a conclusão do projeto como um todo. 
> Esta estimativa possibilita a criação de um cronograma realista e viável, permitindo o planejamento adequado das fases do projeto, alocação de recursos de maneira eficiente e antecipação de eventuais desafios.
> Uma estimativa precisa orienta a execução do projeto, contribui para a gestão de expectativas e para o estabelecimento de metas alcançáveis.

> Indique:
> * Prazo previsto (em horas) 
> * Data de início
> * Data de término

* Prazo previsto (em horas): 6380 horas
* Data de início: 05 / 09 / 24
* Data de término: 05 / 03 / 25

## Escopo Preliminar e Premissas

> Os requisitos preliminares fornecem uma visão inicial do escopo, funcionalidades-chave e as expectativas a serem atendidas. 
> 
> ***A quantidade mínima de requisitos a serem preenchidos nas seções abaixo não incluem os exemplos previamente fornecidos.***

## Declaração de Escopo

> Você pode utilizar como referência o seguinte documento:
- [Declaração de Escopo](artefatos/declaracao-escopo.docx)

> Enumere os requisitos da sua solução. Classifique esses requisitos em dois grupos:
>
> - [Requisitos Funcionais (RF)](https://pt.wikipedia.org/wiki/Requisito_funcional):
>   correspondem a uma funcionalidade que deve estar presente na
>   plataforma (ex: cadastro de usuário).
>
> - [Requisitos Não Funcionais (RNF)](https://pt.wikipedia.org/wiki/Requisito_n%C3%A3o_funcional):
>   correspondem a uma característica técnica, seja de usabilidade,
>   desempenho, confiabilidade, segurança ou outro (ex: suporte a
>   dispositivos iOS e Android).
>
> Lembre-se que cada requisito deve corresponder à uma e somente uma
> característica alvo da sua solução. Além disso, certifique-se de que
> todos os aspectos capturados nas Histórias de Usuário foram cobertos.
> 
> **Links Úteis**:
> 
> - [O que são Requisitos Funcionais e Requisitos Não Funcionais?](https://codificar.com.br/requisitos-funcionais-nao-funcionais/)
> - [O que são requisitos funcionais e requisitos não funcionais?](https://analisederequisitos.com.br/requisitos-funcionais-e-requisitos-nao-funcionais-o-que-sao/)


### Requisitos Funcionais

......  ATUALIZE OS REQUISITOS FUNCIONAIS DO SISTEMA (MÍNIMO 10) ......

A tabela a seguir apresenta os requisitos funcionais do projeto. 

|ID    | Descrição do Requisito  | Prioridade |
|------|-----------------------------------------|-------|
|RF-001| Dashboard Financeiro | ALTA | 
|RF-002| Gestão de Despesas e Receitas  | MÉDIA |
|RF-003| Integração com Bancos e Cartões | ALTA | 
|RF-004| Orçamento e Planejamento Financeiro  | MÉDIA |
|RF-005| Relatórios Financeiros | ALTA | 

### Requisitos Não Funcionais

......  ATUALIZE OS REQUISITOS NÃO FUNCIONAIS DO SISTEMA (MÍNIMO 5) ......

A tabela a seguir apresenta os requisitos não funcionais do projeto. 

|ID     | Descrição do Requisito                                            |Prioridade |
|-------|-------------------------------------------------------------------|-----------|
|RNF-001| A aplicação deve implementar autenticação multifator e criptografia de dados | MÉDIA     | 
|RNF-002| A aplicação deve garantir tempos de resposta rápidos para todas as operações principais, como a importação de transações e a geração de relatórios.            | BAIXA     | 
|RNF-003| A aplicação deve ser projetada para suportar um aumento no número de usuários e transações sem comprometer o desempenho.| MÉDIA     | 
|RNF-004| A aplicação deve ser compatível com diferentes sistemas operacionais e dispositivos, incluindo Windows, macOS, iOS e Android. | BAIXA     | 
|RNF-005| A aplicação deve ter uma interface intuitiva e amigável, com design responsivo que permita fácil navegação e acessibilidade para todos os perfis de usuários, incluindo aqueles com deficiência.| MÉDIA     | 


### Restrições

......  ATUALIZE AS RESTRIÇÕES DO SISTEMA (MÍNIMO 5) ......

A tabela a seguir apresenta as restrições do projeto. 

|ID    | Descrição do Requisito  | Prioridade |
|------|-----------------------------------------|-------|
|RE-001| A aplicação deve atender às leis de proteção de dados como LGPD e GDPR. | ALTA | 
|RE-002| O projeto deve ser concluído em até 6 meses. | ALTA |
|RE-003| Permitir que o usuário forneça seus dados e estabeleça rotinas de compras | ALTA | 
|RE-004| O projeto deve usar tecnologias e frameworks previamente definidos (ex.: JavaScript, React).  | MÉDIA|
|RE-005| A equipe é composta por um número fixo de profissionais, sem aumento previsto. | ALTA | 

### Contra-Escopo

......  ATUALIZE O CONTRA-ESCOPO DO SISTEMA (MÍNIMO 5) ......

A tabela a seguir apresenta as atividades que não serão executadas no projeto

|ID    | Descrição do Contra-Escopo          | 
|------|-------------------------------------|
|CE-001| Integração com Todos os Bancos Internacionais |
|CE-002| Suporte a Dispositivos IoT |
|CE-003| Versão para Desktop Nativa |
|CE-004| Suporte Multilíngue Completo |
|CE-005| Funcionalidades de Balanço Patrimonial |


### Condições para início do Projeto

......  ATUALIZE AS CONDIÇÕES PARA INÍCIO DOS PROJETOS (MÍNIMO 3) ......

A tabela a seguir, apresente as condições para que o projeto seja iniciado.

|ID    | Descrição de Condições para Início do Projeto    | 
|------|--------------------------------------------------|
|CI-001| Definição do Orçamento Aprovado |
|CI-002| Formação Completa da Equipe |
|CI-003| Requisitos de Projeto Claros |
|CI-004| Infraestrutura Tecnológica |
|CI-005| Assinatura do Contrato |

## Marcos Agendados e Entregas

......  ATUALIZE OS MARCOS AGENDADOS DO PROJETO E AS DATAS PARA ENTREGAS DAS TAREFAS ......

A tabela a seguir, identifique os marcos do projeto e os entregáveis previstos (requisitos).

|ID   | Marco do Projeto                                                  | 
|-----|-------------------------------------------------------------------|
|M-1  | Início do Desenvolvimento |
|M-2  | Entrega do MVP (Produto Mínimo Viável) |
|M-3  | Integração com Bancos |
|M-4  | Lançamento Beta |
|M-5  | Entrega Final |


```diff
+ Tarefa 02
+ Fim da seção a ser atualizada.
```

-----
```diff
+ Tarefa 03:
+ Metodologia do Projeto
```

# Metodologia

......  COLOQUE AQUI O SEU TEXTO ......

> Nesta parte do documento, você deve apresentar a metodologia adotada pelo grupo, descrevendo o processo de trabalho baseado nas metodologias ágeis, a divisão de papéis e tarefas e as ferramentas empregadas.
>
> Coloque detalhes sobre o processo utilizado e a implementação do Framework Scrum seguido pelo grupo. 
> O grupo deverá gerenciar as tarefas utilizando o GitHub Project para acompanhar o andamento do projeto, a execução das tarefas e o status de desenvolvimento da solução.
> 
> **Links Úteis**:
> - [Github Project](https://docs.github.com/en/issues/planning-and-tracking-with-projects/creating-projects/creating-a-project)
> - [O que é o GitHub Projects? | Guia de Iniciantes](https://www.youtube.com/watch?v=vxYTpsFKdiQ&ab_channel=JulioArruda)
> - [Introduction to GitHub Project Boards](https://www.youtube.com/watch?v=idZyqNIrt84&list=PLiO7XHcmTslc5hGrbnnmHIb0SeJLTpOEu&ab_channel=MickeyGousset)
> - [11 Passos Essenciais para Implantar Scrum no seu Projeto](https://mindmaster.com.br/scrum-11-passos/)
> - [Scrum em 9 minutos](https://www.youtube.com/watch?v=XfvQWnRgxG0)

## Divisão de Papéis

......  COLOQUE AQUI O SEU TEXTO ......

> Apresente a divisão de papéis e tarefas entre os membros do grupo.
> Indique as responsabilidades de cada membro do grupo no projeto.

## Ferramentas

......  COLOQUE AQUI O SEU TEXTO - SIGA O EXEMPLO DA TABELA ABAIXO  ......

> Liste as ferramentas empregadas no desenvolvimento do projeto, justificando a escolha delas, sempre que possível.
> Todas as ferramentas utilizadas devem ser listadas.
> Qualquer tipo de ferramenta que for utilizada para construção de um artefato deve ser identificada, uma vez que podem ser necessárias alterações.
> A necessidade de uso de licenças e possíveis custos relacionados devem ser indicados.

| Ambiente              | Plataforma         | Link de Acesso             | Justificativa |
|-----------------------|--------------------|----------------------------|---------------|
| Quadro Kanban         | Github             | https://github.com/XXXXXXX | Centralização e organização do projeto no próprio repositório. |
| Repositório de código | GitHub             | https://github.com/XXXXXXX |               |
| Protótipo Interativo  | MavelApp ou Figma  | https://figma.com/XXXXXXX  |               |
| Documentos Textuais   | LibreOffice Writer | N/A                        |               |
| Planilhas e Gráficos  | Google Planilhas   | https://docs.google.com/   |               |
| EAP / WBS             | | | |
| Cronograma do Projeto | | | |
| Matriz RACI           | | | |

```diff
+ Tarefa 03:
+ Fim da seção a ser atualizada.
```

----
