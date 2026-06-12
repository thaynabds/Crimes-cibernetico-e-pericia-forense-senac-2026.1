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

### O Problema da Jurisdição

Crimes cibernéticos desafiam o conceito tradicional de jurisdição, que é baseado em território. Um ataque pode ser planejado em um país, executado por servidores em outro e atingir vítimas em um terceiro — tudo em questão de segundos. Isso gera conflitos sobre **qual Estado tem competência para investigar e julgar** o crime.

Os principais obstáculos jurisdicionais são:

- **Anonimato e dificuldade de localização** do agente criminoso
- **Legislações incompatíveis** entre países (o que é crime em um pode ser legal em outro)
- **Soberania nacional** limitando o acesso a evidências armazenadas em outros territórios
- **Lentidão dos acordos de cooperação** diante da velocidade dos crimes digitais

### A Convenção de Budapeste

A **Convenção sobre o Cibercrime de Budapeste (2001)**, elaborada pelo Conselho da Europa e aberta à adesão de países não membros, é o principal instrumento internacional de combate ao cibercrime. O Brasil a ratificou em **2021 (Decreto nº 11.491/2023)**.

Ela é relevante porque:

| Aspecto | Contribuição |
|---|---|
| **Harmonização legal** | Estabelece definições comuns de crimes cibernéticos entre os signatários |
| **Cooperação investigativa** | Cria canais formais para troca de informações e provas entre países |
| **Preservação rápida de dados** | Permite solicitar a retenção urgente de evidências digitais a outros Estados |
| **Acesso transfronteiriço a dados** | Facilita o acesso a dados armazenados em servidores no exterior |

### Desafios na Produção e Preservação de Provas Digitais

As provas digitais têm características que exigem cuidados especiais:

- **Volatilidade** — dados em memória RAM, logs e registros de conexão podem ser sobrescritos rapidamente
- **Integridade** — qualquer alteração, mesmo acidental, pode invalidar a prova
- **Autenticidade** — é necessário comprovar que a evidência não foi manipulada após a coleta
- **Admissibilidade** — a prova deve seguir procedimentos legais para ser aceita no processo

A cooperação internacional também enfrenta barreiras práticas: diferentes padrões técnicos de coleta, prazos de retenção de dados distintos entre países e o crescente uso de criptografia e anonimizadores dificultam o trabalho investigativo transfronteiriço.

---

## Questão 2 — Perícia Forense Digital: Etapas, Cadeia de Custódia e Análise Técnica

### O Papel da Perícia Forense Digital

A perícia forense digital é o conjunto de procedimentos técnicos e legais para **identificar, coletar, preservar, analisar e apresentar evidências digitais** de forma que sejam válidas juridicamente. Ela é essencial para comprovar tanto a **materialidade** (existência do crime) quanto a **autoria** (quem praticou).

### Etapas da Perícia Forense Digital

```
[1. Identificação] → [2. Preservação] → [3. Coleta] → [4. Análise] → [5. Laudo Pericial]
```

#### 1. Identificação
Reconhecimento das fontes de evidência: dispositivos físicos (HDs, celulares, pendrives), registros de rede (logs, IPs), dados em nuvem e metadados de arquivos.

#### 2. Preservação
Etapa crítica. O objetivo é garantir que as evidências **não sejam alteradas** após a descoberta. Aqui entra a **cadeia de custódia** e a **clonagem pericial**.

#### 3. Coleta
Realização da clonagem forense e extração controlada dos dados. Toda ação é documentada com data, hora, responsável e método utilizado.

#### 4. Análise Técnica
Exame dos dados coletados para reconstruir eventos, identificar rastros digitais, recuperar arquivos deletados e correlacionar evidências com o crime investigado.

#### 5. Laudo Pericial
Documento formal que apresenta os achados da perícia de forma técnica e acessível, com metodologia, resultados e conclusões. É a peça que sustenta a acusação ou defesa no processo judicial.

---

### Cadeia de Custódia

A **cadeia de custódia** é o registro cronológico e documentado de **todo o ciclo de vida da evidência**: desde sua identificação até sua apresentação em juízo. Deve registrar:

- Quem teve contato com a evidência
- Quando e onde o contato ocorreu
- O que foi feito com ela em cada etapa
- Como foi armazenada e transportada

A ruptura da cadeia de custódia pode resultar na **inadmissibilidade da prova** no processo, mesmo que ela seja tecnicamente válida. No Brasil, o Código de Processo Penal (art. 158-A ao 158-F, inseridos pela Lei nº 13.964/2019) regulamenta formalmente a cadeia de custódia.

### Clonagem Pericial

A clonagem pericial consiste na criação de uma **cópia bit a bit** do dispositivo original, gerando uma imagem forense idêntica. A análise é sempre feita sobre a **cópia**, nunca sobre o original, para preservar a integridade da evidência.

O processo inclui:
- Uso de **bloqueadores de escrita** para impedir qualquer gravação no dispositivo original
- Geração de **hash criptográfico** (MD5, SHA-256) do original e da cópia para atestar que são idênticos
- Armazenamento seguro da mídia original lacrada e identificada

### Análise Técnica e Comprovação dos Delitos

A análise forense permite:

- **Materialidade:** confirmar que o crime ocorreu (ex.: arquivos maliciosos encontrados, registros de acesso não autorizado, logs de transações fraudulentas)
- **Autoria:** identificar o responsável por meio de endereços IP, contas de usuário, metadados, histórico de navegação e comunicações eletrônicas

Ferramentas como **Autopsy**, **FTK (Forensic Toolkit)** e **Wireshark** são comumente utilizadas nessa fase para recuperação de dados, análise de tráfego de rede e reconstrução de eventos.

---

## Referências

- **Convenção de Budapeste sobre o Cibercrime** — Conselho da Europa, 2001
- **Lei nº 12.737/2012** — Lei Carolina Dieckmann (crimes informáticos)
- **Lei nº 14.155/2021** — Agravamento dos crimes cibernéticos no Brasil
- **Lei nº 13.964/2019** — Pacote Anticrime (cadeia de custódia, art. 158-A a 158-F do CPP)
- **Decreto nº 11.491/2023** — Promulgação da Convenção de Budapeste no Brasil
- Material de referência da disciplina: *Cybercrime, Digital Perícia Forense* — Faculdade Senac Recife-PE
