# Crimes-cibernetico-e-pericia-forense-senac-2026.1
Atividade da UC [TADS25.109/2N] LEGISLAÇÃO DE TECNOLOGIA DA INFORMAÇÃO - 2026.1 Crimes cibernéticos e perícia forense Data de conclusão 15 de junho de 2026 às 22:00 Semana 13 - 12 de Junho

# 🔐 Crimes Cibernéticos e Perícia Forense Digital

> **Disciplina:** Legislação de Tecnologia da Informação — `[TADS25.109/2N]`  
> **Semana:** 13 — 12 de junho de 2026  
> **Prazo:** 15 de junho de 2026 às 22h00  
> **Aluna:** Thayná Batista da Silva  
> **Curso:** Análise e Desenvolvimento de Sistemas — Faculdade Senac Recife-PE | 2ª UC | 2026.1

---

## Questão 1 — Jurisdição nos Crimes Cibernéticos Internacionais e a Convenção de Budapeste

### O Paradoxo Jurisdicional: Fronteiras Físicas vs. Ameaças Digitais

O Direito Penal tradicional é ancorado no **princípio da territorialidade**: a lei aplicável é a do local onde o crime ocorreu. O cibercrime quebra essa lógica. Um ataque pode ser planejado em um país, executado por servidores em outro e atingir vítimas em um terceiro — surgindo o paradoxo: **qual país deve processar o autor?**

Os três pilares do problema jurisdicional são:

- **O Desafio Soberano:** cada país possui soberania legislativa própria. Legislações distintas inviabilizam punições e travam a investigação — o que é crime em um Estado pode ser conduta atípica em outro.
- **O Conflito de Localidade:** em crimes tradicionais, o local define a lei aplicável. Na Internet, a conduta pode ser delituosa em um país e perfeitamente legal em outro.
- **A Necessidade:** sem cooperação internacional e uniformização legislativa, a preservação de provas digitais torna-se intransponível.

### A Dualidade do Cibercrime

Antes de tratar da cooperação, é fundamental compreender a natureza dos crimes em questão:

| Modalidade | Descrição |
|---|---|
| **Computador como Alvo** | Crimes que atentam contra a integridade, confidencialidade ou disponibilidade dos sistemas de informação. O sistema em si é a vítima (ex: ataques de hackers, ransomware). |
| **Computador como Ferramenta** | O dispositivo é o meio utilizado para praticar tipos penais tradicionais de forma digital (ex: fraudes financeiras, estelionato, disseminação de malware). |

### A Resposta Global: A Convenção de Budapeste

A **Convenção sobre o Cibercrime de Budapeste (2001)** é o principal tratado internacional em vigor que visa harmonizar as leis nacionais sobre cibercrime. O Brasil tornou-se signatário oficialmente em **2023 através do Decreto nº 11.491/2023**, integrando a rede global de combate.

Seu objetivo central é reconhecer que o combate eficiente exige uma **cooperação internacional em assuntos penais mais intensa, rápida e estruturada**.

#### Vocabulário Legal Definido pela Convenção

A Convenção estabelece conceitos comuns entre os signatários, eliminando ambiguidades jurídicas:

| Conceito | Definição |
|---|---|
| **Sistema de Computador** | Aparelho ou conjunto interconectado que assegura, pela execução de um programa, o processamento eletrônico de dados. |
| **Dado de Computador** | Representação de fatos, informações ou conceitos em forma adequada para processamento, incluindo programas. |
| **Provedor de Serviços** | Entidade que permite comunicação aos usuários ou realiza processamento/armazenamento em nome deles. |
| **Dados de Tráfego** | Dados referentes a uma comunicação, indicando origem, destino, caminho, hora, data, duração ou tipo de serviço. |

#### Matriz de Tipificação: Crimes Contra Sistemas e Dados

| Tipificação Penal | Conduta Descrita | Agravante |
|---|---|---|
| **Acesso Ilegal** | Acesso doloso e não autorizado a um sistema de computador. | Violação de medidas de segurança ou objetivo fraudulento. |
| **Interceptação Ilícita** | Interceptação intencional de transmissões não-públicas. | Conexão a outros sistemas de computador. |
| **Violação de Dados** | Danificação, eliminação ou alteração dolosa de dados. | Sério dano para a vítima. |
| **Interferência** | Grave obstrução dolosa e não autorizada do funcionamento de um sistema. | — |
| **Uso Indevido** | Produção, venda ou posse de ferramentas desenvolvidas para cometer cibercrimes. | Intenção clara de uso delituoso. |

### Desafios na Produção e Preservação de Provas Digitais

As evidências digitais possuem características que tornam sua gestão especialmente desafiadora:

- **Volatilidade** — dados em memória RAM, logs e registros de conexão podem ser sobrescritos ou perdidos rapidamente sem intervenção imediata.
- **Integridade** — qualquer alteração, mesmo acidental, compromete a validade da prova.
- **Autenticidade** — é necessário comprovar que a evidência não foi manipulada entre a coleta e a apresentação em juízo.
- **Fragmentação transfronteiriça** — a prova pode estar distribuída em servidores de diferentes países, com prazos de retenção e padrões técnicos distintos.

Sem a harmonização promovida por Budapeste, a preservação de provas digitais em crimes internacionais permanece intransponível.

---

## Questão 2 — Perícia Forense Digital: O Duto Forense, Cadeia de Custódia e Análise Técnica

### A Ciência da Verdade: Introdução à Perícia Forense

A perícia forense digital é a área da ciência que cuida de **preservar, identificar e analisar as evidências digitais** para apontar a **materialidade**, a **autoria** e a **dinâmica do crime**.

Seus três pilares probatórios são:

| Pilar | Objetivo |
|---|---|
| **Materialidade** | Comprovar que o crime digital de fato ocorreu e deixou rastros tangíveis e inalterados. |
| **Autoria** | Vincular técnica e logicamente o ataque ou a fraude à identidade real de um indivíduo ou grupo. |
| **Método** | Desvendar o modus operandi — a dinâmica exata de como o sistema foi comprometido e explorado. |

### O Duto Forense: As 4 Fases da Perícia

```
[01. Coleta e Preservação] → [02. Extração] → [03. Análise] → [04. Laudo Pericial]
```

#### Fase 01 — Coleta e Preservação: A Cadeia de Custódia

Isolamento imediato dos dispositivos suspeitos (computadores, celulares, nuvem). O objetivo principal é **evitar qualquer adulteração ou destruição de dados**, marcando o início da cadeia de custódia legal.

A **cadeia de custódia** é o registro cronológico e documentado de todo o ciclo de vida da evidência, estabelecendo quem teve contato com ela, quando, onde e o que foi feito. No Brasil, é regulamentada pelos **art. 158-A a 158-F do CPP** (inseridos pela Lei nº 13.964/2019 — Pacote Anticrime). Sua ruptura pode resultar na **inadmissibilidade da prova**, mesmo que tecnicamente válida.

#### Fase 02 — Extração: A Clonagem Pericial

Utilização de hardwares (*write-blockers*) e softwares especializados para copiar absolutamente todos os dados, criando uma **imagem forense idêntica sem modificar um único bit do dispositivo original**.

O processo garante integridade por meio de:
- **Bloqueadores de escrita (*write-blockers*):** impedem qualquer gravação no dispositivo original durante a cópia.
- **Hash criptográfico (MD5 / SHA-256):** gerado tanto do original quanto da cópia, atestando matematicamente que são idênticos. Qualquer alteração, por mínima que seja, resulta em um hash completamente diferente.

Toda análise subsequente é realizada exclusivamente sobre a **imagem clonada**, preservando a mídia original lacrada e identificada.

#### Fase 03 — Análise: A Caçada Digital

O perito examina a imagem clonada em um ambiente isolado, realizando busca ativa por:

- Rastros de invasões e malwares
- Histórico de navegação e comunicações
- Transações fraudulentas
- Comunicações criptografadas
- Arquivos ocultos ou deletados

Essa fase aponta a **materialidade** (o crime ocorreu) e a **autoria** (quem o cometeu), reconstruindo também o **método** utilizado.

#### Fase 04 — Laudo Pericial: A Tradução Técnico-Jurídica

Documentação exaustiva e metódica de todas as descobertas. O laudo **traduz a linguagem técnica e binária** para que juízes, advogados e delegados compreendam com clareza cristalina como o crime ocorreu. É a peça que sustenta a acusação ou a defesa no processo judicial.

### Principais Focos de Investigação Forense

| Especialidade | O que investiga |
|---|---|
| **Forense Mobile** | Dados de smartphones, interceptações e metadados de aplicativos de mensagens. |
| **Rastreamento de Fraudes** | Desvios financeiros, phishing complexo, estelionato virtual e clonagem de cartões. |
| **Crimes Contra a Honra** | IPs, perfis falsos, autores de cyberbullying e vazamentos de dados sensíveis. |
| **Invasões e Ataques** | Engenharia reversa e análise de ransomware, sequestro de sistemas e roubo de propriedade intelectual. |

---

## Síntese: O Ciclo da Justiça Digital

> *"A tecnologia cria a arma, a legislação define a regra, e a ciência garante a justiça."*

```
        [Cibercrime]
        ↙          ↘
  [A Perícia]  ←  [A Convenção]
```

Sem a harmonização de Budapeste e o rigor da Perícia Forense, o cibercrime permanece invisível. Juntos, transformam rastros digitais em condenações reais.

---

## Referências

- **Convenção de Budapeste sobre o Cibercrime** — Conselho da Europa, 2001
- **Decreto nº 11.491/2023** — Promulgação da Convenção de Budapeste no Brasil
- **Lei nº 13.964/2019** — Pacote Anticrime (cadeia de custódia, art. 158-A a 158-F do CPP)
- **Lei nº 12.737/2012** — Lei Carolina Dieckmann (crimes informáticos)
- **Lei nº 14.155/2021** — Agravamento dos crimes cibernéticos no Brasil
- Material de referência da disciplina: *O Código e a Lei: Cibercrime e Perícia Forense* — Faculdade Senac Recife-PE, 2026.1
