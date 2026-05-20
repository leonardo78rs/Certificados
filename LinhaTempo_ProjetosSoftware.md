# 📝 Principais projetos realizados 

## 📌 Projetos em Destaque 

[   [2026 Criação Nova Base] ](https://github.com/leonardo78rs/Certificados/blob/main/LinhaTempo_ProjetosSoftware.md#2026-cria%C3%A7%C3%A3o-da-base-centralizadora-9806)
[   [2023 Transf.Dívida] ](https://github.com/leonardo78rs/Certificados/blob/main/LinhaTempo_ProjetosSoftware.md#2023-transferencia-de-d%C3%ADvida)
[   [2022 Projeção de Juros] ](https://github.com/leonardo78rs/Certificados/blob/main/LinhaTempo_ProjetosSoftware.md#2022-proje%C3%A7%C3%A3o-de-juros-futuros)
[   [2019 Cálculo CET Rural] ](https://github.com/leonardo78rs/Certificados/blob/main/LinhaTempo_ProjetosSoftware.md#2019-c%C3%A1lculo-cet-rural)
[   [2015 Mapeador de Código] ](https://github.com/leonardo78rs/Certificados/blob/main/LinhaTempo_ProjetosSoftware.md#2015-mapeador-de-c%C3%B3digo)
[   [2011 Sistema de Eventos] ](https://github.com/leonardo78rs/Certificados/blob/main/LinhaTempo_ProjetosSoftware.md#2011-sistema-de-eventos)
[   [2010 Arquivo Digital] ](https://github.com/leonardo78rs/Certificados/blob/main/LinhaTempo_ProjetosSoftware.md#2010-arquivo-digital)
[   [1997 Dashboard Fiscal] ](https://github.com/leonardo78rs/Certificados/blob/main/LinhaTempo_ProjetosSoftware.md#1997-planilhas-fiscaisdashbords-clientes)

## 📆 Linha do tempo: principais projetos 

#### 2026 Criação da base centralizadora 9806
     +20.000 Objetos de banco de dados e seus relacionamentos
     Definição e previsão de uso da base: Rotinas e funcionalidades que serão utilizados.   
     Conectando +10 áreas diferentes (Infra, Dba, cadastro, entidades, opti, devops, gestão de mudanças,
     gestão de configuração, aplicações, cc, risco, credito, acessos, segurança, auditoria)

#### 2025 Rotina de Sobras (Reciprocidade)
     Ajuste obtenção valores corretos todas operações 9802 e 9803 
     Performance e teste -> +630mil operações  +50 milhões de movimentos por ano
     Recálculo em produção 

#### 2025 TFCB - Novo indexador 
     Permitir nova forma de cálculo pelo sistema, nova moeda
     Mapeamento necessidades, definição e desenvolvimento
     
#### 2024 Prorrogações não equalizadas 
     Definição da estrategia e desenvolvimento de toda rotina 
     Package configurável a futuras mudanças sem precisar implementação
     
#### 2024 Evolução de cálculos 
     Xxxxxxx preencher
     xxxxxxxx     

#### 2023 Transferencia de Dívida 
     Concepção e criação funcionalidade que cria todo ciclo de uma operação rural **em menos de 1 min** 
     Clona as operações com todas as suas ramificações: 
     - Solicitação, cadastro; 
     - Liberação nova, liquidação antiga;
     - Registros externos (bndes,bacen,risco, etc). 
     - Replicação cooperativa e banco. 
     - Criei as packages com funções que não existiam no sistema e agora são reutilizaveis.
     - Atende a todos os tipos de operações Bndes, entendendo quais registros e tabelas precisa clonar;
     - Inclusive tabelas estrangeiras (ForeignKey) e tabelas auxiliares (CLob, Blob e Memo).  

#### 2023 Condições e Prazos 
     Ajuste do sistema para cálculo de cronogramas complexos de liberação e vencimento
     Implementando os prazos máximo e mínimo em conformidade com as instituições (interna e externa)  

#### 2023 Liquidações automáticas 
     Implementação de melhorias e processos para que as operações pudessem ficar totalmente on-line
     Trabalhos de consistência e performance também foram necessários 

#### 2022 Procap Coobrigação 
     Concepção e criação de uma nova modalidade Bndes sistema com replicação
     Esta modalidade permitiu a liberação de novas fontes de recursos para os associados
     além de aumentar o capital das cooperativas

#### 2022 Projeção de Juros Futuros 
     Melhoria e performance robusta da rotina de 11hs para 3hs
     Sem perda de informação ou realização de cálculos incorretos.
     Rotina mensal que gira na média entre 19 a 30 mil operações, rodando com todos os indexadores possíveis.

#### 2021 Crédito Imobiliario 
     Participei da adaptação do sistema para se comunicar com sistema imobiliario externo
     Realizando a exposição externa das APIs de forma segura. 
     O sistema externo necessitava obter informações em tempo real sobre algumas condições do associado, como:
     Realizada a exposição segura do Fator de Risco de Empréstimo, bloqueios judiciais e condições internas do cliente. 
     Ao mesmo tempo que o sistema interno também necessitava de informações desta aplicação apartada do ecossistema. 

#### 2020 TCR Pós Taxa Negativa 
     Implementei metodologia de cálculo em operações com indexadores TCR Negativos. 
     São indices passíveis de momentaneamente ficarem negativos devido à flutuação do IPCA. 
     Junto com o time, colocamos em todas as etapas dentro do ciclo de vida da operação. 

#### 2020 Finame Importados  
     Implantação do Orçamento para realização de empréstimos Finame na modalidade Importados.
     Consegui adotar o modelo sem prejuízo para as demais modalidades de empréstimos
     Permitindo inclusive a contratação mista das outras modalidades existente junto com importados. 

#### 2020 Prorrogações Pandemia  
     Atuação emergencial no bum das prorrogações devido às medidas legais provenientes da pandemia.
     Com apoio de mais dois colegas conseguimos montar a entrega da solução em um mês.
     A solução ficou muito completa e sintética a ponto de seguir durante os 4 anos seguintes sem modificações. 

#### 2020 TCR-Pos  
     Conecpção e metodologia de nova forma de cálculo de juros aproveitando os modelos anteriores

#### 2019 Cálculo CET Rural 
     Desenho, codificação e instalação de funcionalidade para todas operações rurais 
     Elaboração da técnica de cálculo e adaptação no sistema
     Até hoje nunca houve um erro de cálculo: Poucos incidentes eram de erro nos parâmetros
     +2 milhões de operações calculadas (2019-2026) 

#### 2019 TLP - Nova moeda das operações de crédito   
     Idealização e desenvolvimento na implantação de uma nova moeda/indexador para operações de crédito.
     Permitiu a captação de recursos do Bndes e disponibilização para os associados.
     Me envolvi desde as etapas iniciais dando o norte desde a solicitação e contratação dos empréstimos, 
     passando por todo o ciclo de vida da operação. 

#### 2018 Orçamento de Usados   
     Implantação do Orçamento para realização de empréstimos Finame na modalidade usados sem CFI.
     Consegui adptar o modelo sem prejuízo para as demais modalidades de empréstimos,
     permitindo inclusive a contratação mista das modalidades existente junto com equipamentos usados. 

#### 2018 Diversos projetos no crédito 
     Padronização de produtos: Cadastro e Pacote de taxas     
     Fiança honrada manual 
     Inadimplencia (regra, moedas, tlp, ...)
     Sistematica
     Porte - atualização e eliminação processos antigos
     Outras modalidades de seguro 
         
#### 2017 Diversos projetos no crédito 
     Replicação on line centralizadora + replica pac 
     Orçamento Bndes (coletivo, astec, detalhamento)  
     Ajuste nos cronogramas de liberação e vencimento 
     
#### 2016 Seguro Prestamista  
     Um projeto que estava parado, consegui rever todos os fluxos
     Primeiro projeto no crédito - acabei entendendo que uma regra principal diminuia a arrecadação para o Seguro.
     Realizamos a renovação do seguro pelos valores atualizados, evitando esta perda
     Após aprovado o ajuste pela área de negócios colocamos em produção
     Trouxe vantagem para o segurado que passou a ter cobertura do valor total e também aumentou a arrecadação da seguradora vinculada ao banco. 
         
#### 2015 Projeto de tarifas de contas  
     Analisei e encontrei uma forma de recuperar a informação fiel dos dados perdidos.
     A composição da tarifa da conta tem vários contadores para cada classe de produto que o associado tem. 
     Estes contadores foram alterados indevidamente, e estava tendo prejuízo financeiro quando cobrou a menos ou prejuízo de imagem quando cobrou a mais.
     Após a decisão de zerarem os contadores, e arcar com o prejuízo, sugeri e executei a ideia de mapear todos os usos e produtos de todos os associados 
     e montar os contadores novamente para fazer a cobrança ou devolução correta dos valores. 
         
#### 2015 Apoio na incorporação e criação da nova agencia 
     Juntamente com o time de suporte trabalhei no mapeamento e crítica dos dados.
     Correção na importação massiva de dados.
         
#### 2015 Mapeador de código  
     Aplicação que mapeia código fonte para análise de impacto
     Projeto individual em VBA que lê uma pasta com centenas de arquivos fonte e faz a busca de uma expressão,
     tabela, função ou procedimento e mostra em que pontos é chamada. E qual função chama as outras funções.
     Ao final elabora um desenho deste mapeamento. 
 
#### 2014 Suporte Conta corrente
     Sem projetos relevantes. 
     
#### 2013 Suporte Conta corrente
     Sem projetos relevantes. 
         
#### 2013 Projeto Romaneio (expedição/OP ordem de produção)  
     Dialogo cliente, ideia e desenvolvimento de rotinas automáticas.
     Conferencia de componentes e instalações de mega obras de transporte de grãos. 
     Cada pedido gerava várias NFs e transporte de 5 a 20 caminhões com centenas de peças 
     O controle era manual envolvendo várias pessoas. 
     Sistema passou a gerar também importação e exportação para Excel. 
     
#### 2013 Projeto de baterias em Autódromo  
     Reestruturação rotinas de leitura automática. 
     Entendimento do problema e ajuste das leituras. 
     Existia um erro com diferença de cálculo de tempos, que acabava impactando no resultado final, 
     o que fazia o cliente não utilizar o sistema.

#### 2012 Projeto em empresa de geradores - Módulo de vendas  
     Ideia e implantação da importação de arquivos de vendas, fornecedores e comissões, que anteriormente
     eram feitos manualmente. Projeto original era apenas arrumar as telas de digitação e as rotinas
     correspondentes, mas o cliente me relatou esta dor e sugeri tentarmos a importação dos arquivos que eles
     já utilizavam. Satisfação total cliente e no mesmo prazo.
     
#### 2012 Projeto em empresa de geradores - Módulo de Assistencia técnica      
     Levantamento de requisitos e implantação da rotina. 
     Principal ganho foi ter estranhado os requisitos e ter direcionado para a área correta.
     O sistema não era complexo, mas havia sido definido pela área de vendas ao invés da área técnica que não se conversavam. 
         
#### 2012 Projeto Performance em empresa de Mineração - travamento do sistema  
     Identifiquei que não havia muito a se melhorar nas consultas SQL. 
     Pedi ajuda para o pessoal de Infra e na investigação conjunta identificamos uma falha de configuração do Servidor do Banco de Dados,
     fazendo despejo de memória em Disco.
     Após ajustes destravou toda a operação.
         
#### 2012 Projeto em empresa Agroflorestal de grande porte       
     Análise, concepção e desenvolvimento do projeto de acompanhamento das máquinas, terrenos e operadores. 
     Empresa tinha ERP porém não atendia às necessidades e era utilizado apenas para emissão de Danfe (NF). 
    Não era complexo mas gerenciava uma quantidade muito grande de dados. 
         
#### 2012 Projeto empresa de peças de máquinas agrícolas 
     Ressurreição e ajuste em sistema de impressão e controle de estoque em codigo de barras em impressora térmica.
         
#### 2011 Setor de pessoal  
     Automatização e melhorias em informações para governo (Sefip, GFip, RAIS, DIRF). E integração destas declarações no arquivo digital

 
#### 2011 Sistema de eventos   
     Elaboração de um sistema de eventos para pequena empresa em VBA (antecipando o que o Jira faz hoje)
     Resolvendo o problema da falta de percepção da quantidade de trabalho por cliente, e implementando a priorização de tarefas.

#### 2010 Sistema de cobrança automático  
     Integração do sistema de cadastro com a cobrança de honorários via comunicação imediata com Banrisul (CNAB) e emissão de relatórios. 

#### 2010 Arquivo Digital   
     Definição do arquivo digital e implementação de Regras de GED.
     Resolveu o custo de impressão, a deficiência de controle dos processos, e também facilitou o envio de documentos para os clientes.      

#### 2009 Integrações   
     Importação arquivos .txt e .csv de clientes e integração entre todos sistemas fiscais e contábeis, eliminação digitação e retrabalho.

#### 2006-2008 
     Sem projetos relevantes   
      
#### 2005 Sistema simples para Gráfica
     Clientes, Nf, Pedidos e Controle de tele-entrega.   
      
#### 2004 Sistema simples para empresa de Ar-Condicionado 
    Apenas cadastro de clientes e ordem de serviço 
         
#### 2002-2003 NTEF: Projeto PC laboratório Física  
     Automação aquisição de dados de máquinas e sensores.
     Sensores ópticos, de tempo, temperatura. 
     Linguagens: Visual Basic, C e Fortran.  

#### 1999 Sistema para empresa de RH 
     Sistema básico de cadastro de candidatos e empresas.  
     Realizava "match" filtrando as características 

#### 1998 Sistema completo para revenda de veículos que não foi pra frente 
     Ninguém nesse ramo usava PC nesta época 
         
#### 1997 Planilhas fiscais/Dashbords clientes
     Resumo mensal das informações de faturamento, cálculo de impostos
     Continha a evolução anual   
     Em 2022, fiquei sabendo que estavam substituindo, ficou incríveis 25 anos em uso!   
      
#### 1994 - 1996 Diversos  
     implantação e configuração sistema contábil 
     Controle de declarações governamentais de empresas 
     Impressao de formulários pré-impressos para substituir datilografia 
     Projeto de otimização de contratos sociais de empresas   
	 
[ [Voltar ao topo] ](https://github.com/leonardo78rs/Certificados/blob/main/LinhaTempo_ProjetosSoftware.md#-principais-projetos-realizados)
