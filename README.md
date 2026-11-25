
<div align="center">
  <img src="https://raw.githubusercontent.com/POLITECH-Global-Solution/Polieus/main/public/favicons/banner-polieus.svg" width="100%" alt="Banner do projeto Polieus — gestão urbana e participação cidadã" />
  <br />
  <img src="https://raw.githubusercontent.com/POLITECH-Global-Solution/Polieus/main/public/favicons/logo_polieus.png" width="170" alt="Logo do Polieus" />

  <h1>POLIEUS — Software Engineering and Business Model</h1>

  <p><strong>Engenharia de Software e modelo de negócios para uma cidade mais acessível, participativa e transparente.</strong></p>

  <p>
    <strong>Global Solution 2026/2 — CitizenTech</strong><br />
    FIAP | Análise e Desenvolvimento de Sistemas | Equipe Politech | Turma 1TDSPH-26
  </p>

  <a href="./Polieus_SEBM_GS.pdf"><img src="https://img.shields.io/badge/LER_DOCUMENTAÇÃO-78221B?style=for-the-badge&logo=adobeacrobatreader&logoColor=white" alt="Ler documentação em PDF" /></a>
  <a href="https://polieus.vercel.app/"><img src="https://img.shields.io/badge/ACESSAR_POLIEUS-EAD8C6?style=for-the-badge&logo=vercel&logoColor=78221B" alt="Acessar plataforma Polieus" /></a>
  <a href="https://youtu.be/cfb5x6vIXww"><img src="https://img.shields.io/badge/ASSISTIR_VÍDEO_PITCH-78221B?style=for-the-badge&logo=youtube&logoColor=white" alt="Assistir vídeo pitch" /></a>

  <br /><br />

  <img src="https://img.shields.io/badge/SEBM-EAD8C6?style=flat-square&logoColor=78221B" alt="Software Engineering and Business Model" />
  <img src="https://img.shields.io/badge/UML-EAD8C6?style=flat-square&logoColor=78221B" alt="UML" />
  <img src="https://img.shields.io/badge/Business_Model_Canvas-EAD8C6?style=flat-square&logoColor=78221B" alt="Business Model Canvas" />
  <img src="https://img.shields.io/badge/Trello-EAD8C6?style=flat-square&logo=trello&logoColor=78221B" alt="Trello" />
  <img src="https://img.shields.io/badge/UX_Design-EAD8C6?style=flat-square&logoColor=78221B" alt="UX Design" />
  <img src="https://img.shields.io/badge/B2G_%7C_SaaS-EAD8C6?style=flat-square&logoColor=78221B" alt="Modelo B2G e SaaS" />
  <img src="https://img.shields.io/badge/ROI_%7C_SLA-EAD8C6?style=flat-square&logoColor=78221B" alt="ROI e SLA" />
</div>

---

## Índice

- [Sobre a disciplina e o repositório](#sobre-a-disciplina-e-o-repositório)
- [Descrição do projeto Polieus](#descrição-do-projeto-polieus)
- [Problema, público e proposta de valor](#problema-público-e-proposta-de-valor)
- [Objetivos da entrega](#objetivos-da-entrega)
- [Estrutura da documentação](#estrutura-da-documentação)
- [Modelo de negócios — B2G e SaaS](#modelo-de-negócios--b2g-e-saas)
- [Mercado-alvo e benchmark](#mercado-alvo-e-benchmark)
- [Engenharia de Software — backlog e requisitos](#engenharia-de-software--backlog-e-requisitos)
- [Casos de uso e diagramas UML](#casos-de-uso-e-diagramas-uml)
- [Protótipos e experiência do usuário](#protótipos-e-experiência-do-usuário)
- [Precificação e análise financeira](#precificação-e-análise-financeira)
- [Retorno sobre o investimento — ROI](#retorno-sobre-o-investimento--roi)
- [Acordo de Nível de Serviço — SLA](#acordo-de-nível-de-serviço--sla)
- [Uso de inteligência artificial na documentação](#uso-de-inteligência-artificial-na-documentação)
- [Ferramentas e artefatos da disciplina](#ferramentas-e-artefatos-da-disciplina)
- [Vídeo pitch e materiais de apoio](#vídeo-pitch-e-materiais-de-apoio)
- [Integração com as demais disciplinas](#integração-com-as-demais-disciplinas)
- [Estrutura do repositório](#estrutura-do-repositório)
- [Integrantes e autores](#integrantes-e-autores)

---

## Sobre a disciplina e o repositório

Este repositório reúne a entrega da disciplina **Software Engineering and Business Model (SEBM)**, elaborada pela **Equipe Politech** para a **Global Solution 2026/2 — CitizenTech**, da FIAP.

O trabalho articula duas frentes complementares:

1. **Engenharia de Software:** levantamento e organização de requisitos, backlog, histórias de usuário, casos de uso, diagramas de atividades e protótipos.
2. **Modelo de negócios:** definição da proposta de valor, análise de mercado, Business Model Canvas, precificação, estimativa de retorno sobre o investimento e proposta de acordo de nível de serviço.

O principal artefato deste repositório é o documento **[Polieus_SEBM_GS.pdf](./Polieus_SEBM_GS.pdf)**, com **98 páginas**. A documentação também inclui o vídeo pitch, links dos artefatos externos e registros sobre o uso de ferramentas de inteligência artificial.

> **Escopo deste repositório:** documentação acadêmica de Engenharia de Software e Modelo de Negócios. A implementação do **front-end React/TypeScript** e da **API REST Java** pertence aos seus respectivos repositórios. Os processos e recursos descritos no PDF incluem soluções previstas, propostas e protótipos; não representam necessariamente funcionalidades já homologadas ou integradas em produção.

---

## Descrição do projeto Polieus

O **Polieus** é uma proposta de plataforma *CitizenTech* destinada a aproximar cidadãos e gestores públicos por meio do registro, acompanhamento e análise de demandas urbanas.

O **MVP tem como município-piloto São Paulo (capital)**, priorizando:

- **Acessibilidade urbana:** obstáculos, calçadas danificadas, falta de rampas e barreiras que dificultam a circulação.
- **Pavimentação:** buracos, rachaduras e problemas de conservação das vias públicas.

A proposta prevê um fluxo no qual o cidadão informa o problema, a localização e, quando disponível, uma fotografia; recebe um protocolo e acompanha as atualizações. Gestores municipais autorizados consultam solicitações, analisam informações territoriais, justificam decisões e registram o histórico administrativo.

A solução também estuda o uso de **agrupamento territorial** e **regressão com dados históricos** para apoiar análises. Essas técnicas não substituem as decisões de servidores públicos e não garantem a execução de obras ou prazos de intervenção.

### Visão funcional da proposta

| Público | Recursos descritos no estudo |
| --- | --- |
| **Cidadãos** | Registro de ocorrências; geração de protocolo; consulta das próprias solicitações; acompanhamento do histórico; informações públicas de transparência. |
| **Gestores públicos** | Consulta e filtragem de demandas; análise de prioridades; atualização administrativa do status; justificativas; indicadores e relatórios. |
| **Administração municipal contratante** | Visão agregada das demandas, recursos de acompanhamento e proposta de contratação institucional da plataforma. |

**A responsabilidade pela avaliação administrativa e pela realização de intervenções urbanas permanece com os órgãos públicos competentes.**

---

## Problema, público e proposta de valor

O estudo parte da dificuldade de registrar e acompanhar demandas de infraestrutura em canais fragmentados, além dos desafios de rastreabilidade, acessibilidade e transparência pública.

A proposta de valor do Polieus combina:

- **Participação cidadã:** um canal digital para registrar e consultar solicitações.
- **Rastreabilidade:** protocolos e históricos de acompanhamento.
- **Acessibilidade:** atenção às pessoas com deficiência e mobilidade reduzida.
- **Análise territorial:** organização das demandas por localização, categoria e período.
- **Transparência:** apresentação contextualizada de indicadores e referências orçamentárias verificáveis, quando disponíveis.
- **Apoio à gestão:** priorização explicável e análises auxiliares, sempre sujeitas à revisão humana.

**Públicos do modelo de negócios:** prefeituras e órgãos municipais são os potenciais **contratantes**; gestores e servidores são **usuários administrativos**; cidadãos utilizam gratuitamente as **funcionalidades públicas**.

---

## Objetivos da entrega

A disciplina foi utilizada para organizar os principais aspectos funcionais, econômicos e operacionais da proposta:

- Identificar o problema e delimitar o MVP;
- Explicitar atores, necessidades e regras de negócio;
- Organizar o **backlog** e suas prioridades;
- Modelar os **casos de uso UML** e **diagramas de atividades**;
- Apresentar os **protótipos** e relacioná-los à experiência do usuário;
- Construir o **Business Model Canvas** e analisar alternativas existentes;
- Estimar custos, preço comercial e retorno econômico por meio de premissas declaradas;
- Propor compromissos de disponibilidade, suporte e atendimento em um **SLA**;
- Documentar o vídeo pitch e o uso responsável de ferramentas de IA.

---

## Estrutura da documentação

O PDF contém **15 capítulos**, organizados da seguinte forma:

| Capítulo | Tema | Página inicial no PDF | Conteúdo |
| :---: | --- | :---: | --- |
| 01 | **Sumário executivo** | 2 | Problema, solução, público, diferenciais e síntese financeira. |
| 02 | **Problema e oportunidade** | 3 | Contexto urbano, acessibilidade e desafios de acompanhamento. |
| 03 | **Solução** | 4 | Fluxos para cidadãos e gestores, escopo e limites do projeto. |
| 04 | **Modelo de negócios** | 6 | Proposta B2G/SaaS, estrutura operacional e Business Model Canvas. |
| 05 | **Mercado-alvo e benchmark** | 14 | Segmentação, concorrentes e posicionamento competitivo. |
| 06 | **Backlog** | 20 | Épicos, histórias de usuário, prioridades e evidências do Trello. |
| 07 | **Casos de uso** | 22 | Atores, diagramas UML e especificações UC-01 a UC-03. |
| 08 | **Diagramas de atividades** | 31 | Fluxos de registro, acompanhamento e gerenciamento. |
| 09 | **Protótipo** | 34 | Telas de cidadão, transparência, gestão e relatórios. |
| 10 | **Precificação** | 39 | Custos, Horas/Homem, preço SaaS e implantação. |
| 11 | **Retorno sobre o investimento (ROI)** | 52 | Premissas, economia administrativa e ROI simulado. |
| 12 | **Acordo de Nível de Serviço (SLA)** | 62 | Disponibilidade, suporte, incidentes e compensações. |
| 13 | **Vídeo pitch** | 77 | Link da apresentação da proposta. |
| 14 | **Uso de inteligência artificial** | 78 | Ferramentas, evidências, revisão crítica e roteiros propostos. |
| 15 | **Referências** | 95 | Fontes e materiais bibliográficos utilizados. |

📄 **[Abrir a documentação completa — 98 páginas](./Polieus_SEBM_GS.pdf)**

---

## Modelo de negócios — B2G e SaaS

O documento propõe o modelo **B2G (Business-to-Government)**, com contratação institucional por administrações municipais. A prestação tecnológica é apresentada em formato **SaaS (Software as a Service)**: disponibilização via internet, com hospedagem, manutenção, atualizações e suporte contemplados no planejamento comercial.

Nesse cenário:

| Elemento | Proposta documentada |
| --- | --- |
| **Cliente contratante** | Administração municipal, sujeita aos procedimentos legais e institucionais aplicáveis. |
| **Usuário administrativo** | Gestores e servidores públicos autorizados. |
| **Beneficiário público** | Cidadãos que registram e acompanham solicitações sem cobrança individual. |
| **Entrega de valor** | Centralização de demandas urbanas, rastreabilidade, transparência e análise territorial. |
| **Receita projetada** | Contratação recorrente do serviço SaaS, com implantação inicial cobrada separadamente. |
| **Atividades operacionais** | Desenvolvimento, manutenção, monitoramento, suporte e capacitação. |
| **Premissa comercial** | Simulação inicial para um município contratante; condições sujeitas à validação. |

### Business Model Canvas (BMC)

O trabalho apresenta duas representações do modelo de negócios, ambas com a estrutura tradicional de nove blocos. A segunda foi desenvolvida com apoio de IA para a apresentação visual, conforme registrado no PDF.

- [**Business Model Canvas — versão da equipe no Canva**](https://canva.link/1589k2ysl2ua934)
- [**Business Model Canvas — versão visual complementar**](https://canva.link/4k61dnhe2mkw7i2)

As imagens e as explicações estão no documento, nas **páginas 12 e 13**.

---

## Mercado-alvo e benchmark

O mercado-alvo considerado compreende **administrações municipais brasileiras**, especialmente aquelas interessadas em melhorar o acompanhamento das demandas de acessibilidade, pavimentação e zeladoria.

O documento compara propostas comerciais e um serviço público de referência:

| Referência analisada | Natureza na análise | Relação com o Polieus |
| --- | --- | --- |
| **Colab** | Concorrente direto | Participação cidadã, relacionamento com prefeituras e gestão de solicitações. |
| **FixMyStreet Pro** | Concorrente direto funcional | Registro geolocalizado e acompanhamento de problemas em vias e espaços públicos. |
| **1Doc** | Solução comercial adjacente | Gestão administrativa e fluxos digitais para instituições. |
| **SP156** | Alternativa pública indireta | Serviço municipal de registro, protocolos e acompanhamento de solicitações em São Paulo. |

A avaliação considera os eixos **público e mercado**, **registro e acompanhamento**, **gestão e inteligência**, **transparência** e **condições comerciais e limitações**.

> O benchmark utiliza informações institucionais e apresenta diferenças de escopo e contexto. Não presume que a ausência de uma funcionalidade em informações públicas signifique que ela inexista em qualquer plano contratado.

Veja a análise e o quadro comparativo no **capítulo 5, páginas 14 a 20**.

---

## Engenharia de Software — backlog e requisitos

O backlog da proposta foi organizado no Trello, com **6 épicos e 20 histórias de usuário (HUs)**. As histórias incluem descrição orientada ao usuário, **requisitos funcionais (RF)**, **requisitos não funcionais (RNF)**, regras de negócio e tarefas.

[![Trello](https://img.shields.io/badge/ACESSAR_BACKLOG_NO_TRELLO-78221B?style=for-the-badge&logo=trello&logoColor=white)](https://trello.com/b/q1UmmXNq/polieus)

### Organização dos épicos

| Grupo de histórias | Escopo representado |
| --- | --- |
| **HU 1.x — Acesso** | Contas, entrada na área administrativa e permissões. |
| **HU 2.x — Ocorrências do cidadão** | Registro, protocolo, consulta e identificação de registros semelhantes. |
| **HU 3.x — Classificação e análise** | Classificação, sugestões de prioridade, estimativas e filtros. |
| **HU 4.x — Informações orçamentárias** | Consulta a informações e estimativas de custo, quando cabíveis. |
| **HU 5.x — Gestão administrativa** | Consulta de demandas, atualização de status e indicadores. |
| **HU 6.x — Transparência e acompanhamento** | Informações públicas, andamento e indicadores. |

### Critérios de prioridade descritos no documento

| Prioridade | Significado |
| --- | --- |
| **P1** | Núcleo do MVP. |
| **P2** | Melhoria incremental. |
| **P3** | Evolução comercial. |

A **página 21** apresenta a evidência do backlog, com status, prioridade e liderança sugerida para as 20 histórias. Ela documenta o estado da exportação de **13/11/2026**, não o andamento atualizado do Trello em tempo real.

**Exemplos de histórias documentadas:** HU 2.1 (registro de ocorrência), HU 2.2 (geração de protocolo), HU 2.3 (consulta das próprias ocorrências), HU 3.2 (sugestão de prioridade), HU 5.2 (atualização de status) e HU 6.4 (consulta de indicadores públicos).

---

## Casos de uso e diagramas UML

A modelagem de **casos de uso** descreve dois atores principais:

- **Cidadão:** registra ocorrências, recebe protocolo e acompanha solicitações.
- **Gestor público:** consulta demandas, analisa informações e atualiza o histórico administrativo.

### Casos de uso especificados

| Caso | Ator principal | Histórias associadas | Objetivo |
| --- | --- | --- | --- |
| **UC-01 — Registrar Ocorrência Urbana** | Cidadão | HU 2.1 e HU 2.2 | Registrar dados da ocorrência e gerar protocolo após conclusão bem-sucedida. |
| **UC-02 — Consultar e Acompanhar Ocorrência** | Cidadão | HU 2.3 e HU 6.2 | Consultar situação, protocolos e histórico das próprias solicitações. |
| **UC-03 — Gerenciar Ocorrência Urbana** | Gestor público | HU 5.1 e HU 5.2 | Consultar, analisar e atualizar demandas com justificativa e rastreabilidade. |

A documentação apresenta um **diagrama geral unificado**, diagramas complementares e especificações com pré-condições, pós-condições, fluxos principais, alternativos e exceções. A relação UML `«include»` é explicada no contexto da **geração obrigatória de protocolo** após registro concluído com sucesso.

### Diagramas de atividades

| Diagrama | Processo representado | Página |
| --- | --- | :---: |
| **Diagrama 1** | Registro de ocorrência pelo cidadão. | 31 |
| **Diagrama 2** | Consulta e acompanhamento da ocorrência. | 32 |
| **Diagrama 3** | Gerenciamento de ocorrências pelo administrador. | 33 |

Os diagramas ilustram as ações e decisões dos processos; sua interpretação deve considerar também as exceções descritas nos casos de uso.

📖 **Diagramas e especificações completos:** [documentação da disciplina](./Polieus_SEBM_GS.pdf), **páginas 22 a 33**.

---

## Protótipos e experiência do usuário

Os protótipos relacionam as interfaces previstas às histórias do backlog e às **heurísticas de usabilidade de Nielsen**. A documentação inclui:

| Protótipo | Público | Funcionalidades e aspectos de UX |
| --- | --- | --- |
| **Registro de ocorrência** | Cidadão | Formulário, localização e envio; linguagem clara e familiar. |
| **Mensagem de erro** | Cidadão | Orientação para reconhecer e corrigir campos incompletos. |
| **Confirmação de registro** | Cidadão | Feedback do resultado e identificação por protocolo. |
| **Transparência** | Cidadão | Consulta de indicadores e informações orçamentárias contextualizadas. |
| **Gerenciar ocorrências** | Gestor público | Pesquisa, filtros e identificação de ações administrativas. |
| **Relatórios e indicadores** | Gestor público | Visualização de ocorrências, categorias e prioridades. |

Entre as heurísticas discutidas estão **visibilidade do estado do sistema**, **correspondência com o mundo real**, **controle e liberdade do usuário**, **reconhecimento em vez de memorização** e **auxílio na recuperação de erros**.

Os protótipos e suas descrições estão nas **páginas 34 a 38** do PDF.

---

## Precificação e análise financeira

A precificação do estudo foi construída a partir de custos atribuídos ao projeto acadêmico, estimativa de **Horas/Homem (HH)**, projeções para conclusão comercial e despesas recorrentes de operação. O documento distingue os custos de **desenvolvimento acadêmico** e de **preparação comercial**, evitando somá-los novamente ao custo de contratação do município.

### Esforço de desenvolvimento estimado

| Etapa | Estimativa | Custo atribuído |
| --- | ---: | ---: |
| Global Solution — desenvolvimento acadêmico | **555 HH** | **R$ 11.149,50** |
| Conclusão e preparação comercial | **480 HH** | **R$ 9.642,81** |
| **Total de desenvolvimento estimado** | **1.035 HH** | **R$ 20.792,31** |

O custo acadêmico de referência corresponde a aproximadamente **R$ 20,09 por hora técnica**. Trata-se de um parâmetro calculado com as despesas atribuídas ao projeto, **não de salário profissional ou valor médio de mercado**.

### Proposta comercial B2G/SaaS

| Componente do estudo | Valor projetado |
| --- | ---: |
| **Mensalidade SaaS** | **R$ 6.787,35** |
| **Contratação SaaS anual (12 meses)** | **R$ 81.448,20** |
| **Implantação inicial — pagamento único** | **R$ 2.265,47** |
| **Total estimado do primeiro ano** | **R$ 83.713,67** |

O preço mensal foi formado considerando custos de infraestrutura, armazenamento, backup, segurança, monitoramento, manutenção, suporte, despesas indiretas, recuperação do investimento, markup e provisão tributária. A implantação foi calculada separadamente, considerando configuração, capacitação, migração/preparação de dados e validação.

> **Atenção:** esses números pertencem a uma **simulação acadêmica**. Não constituem proposta comercial vigente, serviço contratado, cotação definitiva de infraestrutura ou comprovação de operação real em ambiente governamental.

**Detalhamento e fórmulas:** capítulo 10 do PDF, **páginas 39 a 51**.

---

## Retorno sobre o investimento — ROI

A simulação considera um município de referência com aproximadamente **1.200 ocorrências mensais**, custo administrativo hipotético de **R$ 50,00 por hora** e redução estimada do trabalho de triagem e elaboração de relatórios.

| Atividade considerada | Horas potencialmente liberadas por mês | Benefício anual estimado |
| --- | ---: | ---: |
| Triagem das ocorrências | 160 h | R$ 96.000,00 |
| Elaboração de relatórios gerenciais | 16 h | R$ 9.600,00 |
| **Total** | **176 h/mês** | **R$ 105.600,00** |

Na hipótese acadêmica, o ROI do primeiro ano é calculado a partir dos benefícios estimados e do investimento de **R$ 83.713,67**:

**Cálculo:** `(R$ 105.600,00 − R$ 83.713,67) ÷ R$ 83.713,67 × 100 ≈ 26,14%`.

**ROI projetado: 26,14%.** O cenário depende de hipóteses de volume de solicitações, tempo de trabalho e custo administrativo; **não é um resultado efetivamente medido em prefeituras contratantes**.

📖 **Memória de cálculo, premissas e limitações:** capítulo 11, **páginas 52 a 61**.

---

## Acordo de Nível de Serviço — SLA

O documento propõe um **Service Level Agreement (SLA)** para uma futura operação comercial. O acordo trata da **qualidade dos serviços tecnológicos**, e não de prazos para a prefeitura realizar obras.

### Disponibilidade e atendimento

| Indicador | Meta ou condição proposta |
| --- | --- |
| **Disponibilidade da plataforma** | **99,5% ao mês** |
| **Objetivo de acesso** | Plataforma disponível 24 horas por dia, 7 dias por semana. |
| **Atendimento humano padrão** | Segunda a sexta-feira, das **9h às 18h**, horário de Brasília, exceto feriados aplicáveis. |
| **Monitoramento** | Proposta de monitoramento automatizado contínuo, com registro técnico de incidentes. |
| **Manutenção e suporte planejados** | 30 HH por mês: 18 HH de manutenção e 12 HH de suporte. |

A plataforma projetada para acesso contínuo **não implica atendimento humano 24 horas por dia**.

### Classificação e prazos de incidentes

| Prioridade | Exemplo | Primeira resposta técnica | Restabelecimento / resolução proposta |
| --- | --- | --- | --- |
| **P1 — Crítica** | Indisponibilidade ampla ou falha grave de segurança. | Até **2 horas úteis**. | Contenção/restabelecimento em até **8 horas úteis**; correção definitiva em até **3 dias úteis**. |
| **P2 — Alta** | Falha relevante em funcionalidade importante. | Até **4 horas úteis**. | Até **2 dias úteis**. |
| **P3 — Média** | Problemas localizados em filtros ou relatórios. | Até **1 dia útil**. | Até **5 dias úteis**. |
| **P4 — Baixa** | Dúvidas e problemas visuais de baixo impacto. | Até **2 dias úteis**. | Até **10 dias úteis** para problemas simples. |

Os prazos são contados segundo o horário de suporte definido na proposta e dependeriam de homologação da estrutura técnica.

### Compensações simuladas por disponibilidade

A proposta prevê percentuais de compensação sobre a mensalidade SaaS de referência, conforme o nível de disponibilidade mensal apurado:

| Disponibilidade mensal | Compensação proposta |
| --- | ---: |
| A partir de **99,5%** | **0%** |
| De **99,0%** a menos de **99,5%** | **5%** |
| De **98,0%** a menos de **99,0%** | **10%** |
| Abaixo de **98,0%** | **15%** |

A aplicação dependeria de apuração documentada e dos termos contratuais; a proposta limita a compensação desses eventos a **15% da mensalidade de referência**.

📖 **Condições, responsabilidades e fórmulas:** capítulo 12, **páginas 62 a 76**.

---

## Uso de inteligência artificial na documentação

O capítulo 14 distingue claramente **usos registrados com evidências** de **propostas de revisão**. Essa separação é importante para não atribuir à IA atividades que não foram efetivamente documentadas como realizadas.

### Usos registrados pela equipe

| Ferramenta | Finalidade documentada |
| --- | --- |
| **ChatGPT** | Apoio à organização inicial de histórias de usuário, RF, RNF, tarefas e regras do backlog. |
| **Gemini (Pesquisa)** | Apoio à conferência e formatação de fontes e notas de rodapé acadêmicas. |
| **ChatGPT** | Apoio à estruturação inicial do roteiro e da sequência narrativa do vídeo pitch. |

O documento também cita auxílio de ferramentas de **IA visual** na apresentação do BMC e do benchmark. As seções posteriores incluem **roteiros sugeridos** de revisão de diferentes disciplinas, que não devem ser apresentados automaticamente como usos já executados.

A revisão humana, a adaptação ao escopo e a conferência de referências foram registradas como partes necessárias do processo.

**Evidências e reflexão crítica:** capítulo 14, **páginas 78 a 94**.

---

## Ferramentas e artefatos da disciplina

| Recurso | Utilização documentada |
| --- | --- |
| **UML** | Casos de uso, atores, relacionamentos e diagramas de atividades. |
| **Trello** | Organização do backlog, épicos, histórias de usuário e etapas de trabalho. |
| **Canva** | Representação e disponibilização de versões do Business Model Canvas. |
| **Prototipação de interfaces** | Representação dos fluxos da experiência de cidadão e gestor. |
| **Heurísticas de Nielsen** | Análise e justificativas das decisões de interface. |
| **Planilhas e cálculos financeiros** | Estimativas de custos, Horas/Homem, precificação, ROI e compensações. |
| **PDF acadêmico** | Consolidação da entrega, figuras, tabelas, demonstrações e referências. |

**Importante:** estas são ferramentas, métodos e artefatos apresentados na documentação SEBM. Eles não constituem um stack de execução de software dentro deste repositório.

---

## Vídeo pitch e materiais de apoio

A entrega inclui um vídeo pitch que apresenta a proposta do Polieus, com foco no problema, solução, público, modelo de negócios e diferenciais.

- 🎬 **[Assistir ao vídeo pitch da disciplina](https://youtu.be/cfb5x6vIXww)**
- 📋 **[Consultar o backlog no Trello](https://trello.com/b/q1UmmXNq/polieus)**
- 🧩 **[Business Model Canvas — versão 1](https://canva.link/1589k2ysl2ua934)**
- 🧩 **[Business Model Canvas — versão 2](https://canva.link/4k61dnhe2mkw7i2)**
- 📑 **[Ler a documentação da Global Solution — PDF](./Polieus_SEBM_GS.pdf)**

---

## Integração com as demais disciplinas

O Polieus foi desenvolvido como um projeto multidisciplinar. O estudo SEBM descreve o produto, seus processos e seu modelo de negócios; os códigos de aplicação e os materiais técnicos das demais disciplinas estão em outros repositórios.

| Frente / disciplina | Repositório | Escopo |
| --- | --- | --- |
| **Front-End Design Engineering** | [Polieus — aplicação web](https://github.com/POLITECH-Global-Solution/Polieus) | React, TypeScript, interfaces, mapas, navegação e integração com API. |
| **Domain Driven Design Using Java** | [Polieus — API Java](https://github.com/MilenaConegin/polieus) | Spring Boot, API REST, regras de negócio e persistência Oracle. |
| **Building Relational Database** | [data-base-polieus](https://github.com/POLITECH-Global-Solution/data-base-polieus) | Modelos de dados, regras de integridade, Oracle SQL e consultas. |
| **Computational Thinking Using Python** | [polieus-py](https://github.com/POLITECH-Global-Solution/polieus-py) | Sistema de terminal para ocorrências e consultas com API pública. |
| **Artificial Intelligence & Chatbot** | [Polieus-IA](https://github.com/POLITECH-Global-Solution/Polieus-IA) | Estudos de agrupamento e regressão, preparação de dados e API experimental. |
| **Software Engineering and Business Model** | **Este repositório** | Planejamento, artefatos de software, modelo de negócios, precificação, ROI e SLA. |

### Comunicação entre a interface e a API Java

A **aplicação web** foi organizada para se comunicar com a **API REST em Java**, hospedada separadamente. O repositório principal documenta seus serviços HTTP, rotas e a integração planejada/implementada entre as partes.

- **Front-end:** [https://polieus.vercel.app](https://polieus.vercel.app)
- **API Java:** [https://polieus.onrender.com](https://polieus.onrender.com)
- **Detalhes de rotas e endpoints:** [README técnico do repositório principal](https://github.com/POLITECH-Global-Solution/Polieus#integração-com-a-api-java)

> A existência de documentação, API e telas não comprova, por si só, integração completa entre todas as disciplinas em produção. O projeto acadêmico contém recursos demonstrativos e etapas planejadas.

---

## Estrutura do repositório

Este repositório é **documental**, portanto não exige instalação de dependências nem possui um comando para iniciar a aplicação.

```text
polieus-software-engineering/
├── README.md            # Apresentação completa da entrega
├── Polieus_SEBM_GS.pdf   # Documento acadêmico original — 98 páginas
└── LICENSE              # Licença disponibilizada no repositório
```

Para estudar ou avaliar a disciplina, abra o **[documento completo](./Polieus_SEBM_GS.pdf)**. Para executar o front-end ou o back-end, consulte os READMEs dos respectivos repositórios técnicos.

---

## Integrantes e autores

Projeto desenvolvido pela **Equipe Politech**, turma **1TDSPH**, para a **Global Solution 2026/2 — CitizenTech**, da FIAP.

A apresentação dos integrantes segue o mesmo padrão do [README principal do Polieus](https://github.com/POLITECH-Global-Solution/Polieus#-integrantes--autores), com **foto, nome completo, RM, turma, função no projeto e acesso aos perfis profissionais**. As imagens estão vinculadas ao repositório principal da equipe.

<table>
  <tr>
    <td align="center">
      <img src="https://raw.githubusercontent.com/POLITECH-Global-Solution/Polieus/main/src/img/fotoHenrique.jpeg" width="120" alt="Foto de Henrique Bonachela" />
    </td>
    <td>
      <strong>Henrique Bonachela de Carvalho Carabante</strong><br />
      RM <strong>573620</strong> | Turma: <strong>1TDSPH</strong><br />
      Especialista em Inteligência Artificial<br /><br />
      <a href="https://www.linkedin.com/in/henrique-bonachela-de-carvalho-carabante-260b86338/"><img src="https://img.shields.io/badge/LinkedIn-78221B?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn de Henrique Bonachela" /></a>
      <a href="https://github.com/henriquebonachela"><img src="https://img.shields.io/badge/GitHub-411516?style=flat-square&logo=github&logoColor=white" alt="GitHub de Henrique Bonachela" /></a>
    </td>
  </tr>
  <tr>
    <td align="center">
      <img src="https://raw.githubusercontent.com/POLITECH-Global-Solution/Polieus/main/src/img/fotoIsa.png" width="120" alt="Foto de Isabelle Ferreira" />
    </td>
    <td>
      <strong>Isabelle Ferreira Neri Feitoza</strong><br />
      RM <strong>573507</strong> | Turma: <strong>1TDSPH</strong><br />
      Engenheira de Dados<br /><br />
      <a href="https://www.linkedin.com/in/isabelle-ferreira-8844593ab"><img src="https://img.shields.io/badge/LinkedIn-78221B?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn de Isabelle Ferreira" /></a>
      <a href="https://github.com/isabelleferreiraa"><img src="https://img.shields.io/badge/GitHub-411516?style=flat-square&logo=github&logoColor=white" alt="GitHub de Isabelle Ferreira" /></a>
    </td>
  </tr>
  <tr>
    <td align="center">
      <img src="https://raw.githubusercontent.com/POLITECH-Global-Solution/Polieus/main/src/img/fotoMilena.png" width="120" alt="Foto de Milena Conegin" />
    </td>
    <td>
      <strong>Milena Silva Conegin</strong><br />
      RM <strong>568923</strong> | Turma: <strong>1TDSPH</strong><br />
      Desenvolvedora Back-end — Java<br /><br />
      <a href="https://www.linkedin.com/in/milena-conegin-996b22269"><img src="https://img.shields.io/badge/LinkedIn-78221B?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn de Milena Conegin" /></a>
      <a href="https://github.com/MilenaConegin"><img src="https://img.shields.io/badge/GitHub-411516?style=flat-square&logo=github&logoColor=white" alt="GitHub de Milena Conegin" /></a>
    </td>
  </tr>
  <tr>
    <td align="center">
      <img src="https://raw.githubusercontent.com/POLITECH-Global-Solution/Polieus/main/src/img/fotoMarina.jpg" width="120" alt="Foto de Marina Fernandes" />
    </td>
    <td>
      <strong>Marina Fernandes Gomes Mesquita</strong><br />
      RM <strong>571265</strong> | Turma: <strong>1TDSPH</strong><br />
      Desenvolvedora Front-end<br /><br />
      <a href="https://www.linkedin.com/in/marifernandesgm-58460a40a"><img src="https://img.shields.io/badge/LinkedIn-78221B?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn de Marina Fernandes" /></a>
      <a href="https://github.com/marifernandesgm"><img src="https://img.shields.io/badge/GitHub-411516?style=flat-square&logo=github&logoColor=white" alt="GitHub de Marina Fernandes" /></a>
    </td>
  </tr>
  <tr>
    <td align="center">
      <img src="https://raw.githubusercontent.com/POLITECH-Global-Solution/Polieus/main/src/img/fotoMurilo.jpeg" width="120" alt="Foto de Murilo Almeida" />
    </td>
    <td>
      <strong>Murilo Almeida Rodrigues de Souza</strong><br />
      RM <strong>573977</strong> | Turma: <strong>1TDSPH</strong><br />
      Desenvolvedor Back-end — Python<br /><br />
      <a href="https://www.linkedin.com/in/murilo-a-souza/"><img src="https://img.shields.io/badge/LinkedIn-78221B?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn de Murilo Almeida" /></a>
      <a href="https://github.com/murilo-a-souza"><img src="https://img.shields.io/badge/GitHub-411516?style=flat-square&logo=github&logoColor=white" alt="GitHub de Murilo Almeida" /></a>
    </td>
  </tr>
</table>

---

<div align="center">
  <img src="https://raw.githubusercontent.com/POLITECH-Global-Solution/Polieus/main/public/favicons/logo_polieus.png" width="100" alt="Logo do Polieus" />
  <br />
  <strong>POLIEUS — Equipe Politech</strong><br />
  FIAP · Global Solution 2026/2 · CitizenTech · Turma 1TDSPH-26<br />
  <em>Tecnologia a serviço de cidades mais acessíveis e de uma gestão pública transparente.</em>
  <br /><br />
  <img src="https://raw.githubusercontent.com/POLITECH-Global-Solution/Polieus/main/public/favicons/banner-polieus.svg" width="100%" alt="Banner do Polieus" />
</div>
