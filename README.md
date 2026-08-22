# Perspectivacontece-SST

## Sistema de Avaliação de Riscos Profissionais

Aplicação web desenvolvida para apoiar as atividades de **Segurança e Saúde no Trabalho (SST)** da Perspectivacontece, com especial enfoque na **Avaliação de Riscos Profissionais (ARP)**.

O projeto encontra-se em evolução e será progressivamente transformado numa plataforma integrada de apoio ao trabalho técnico da Perspectivacontece.

---

## 🎯 Objetivo

O objetivo deste projeto é disponibilizar uma ferramenta simples, prática e profissional para apoiar o Técnico de Segurança no Trabalho na realização de avaliações de riscos profissionais.

A aplicação deverá permitir trabalhar tanto em contexto de escritório como durante visitas a clientes.

### Dispositivos suportados

* 💻 Computador
* 📱 Telemóvel
* 📲 Tablet

A utilização em dispositivos móveis é uma prioridade do projeto, permitindo realizar e consultar avaliações diretamente no local de trabalho.

---

# 🦺 Avaliação de Riscos Profissionais

A aplicação constitui a base para a realização de Avaliações de Riscos Profissionais.

A evolução da ferramenta deverá permitir trabalhar com:

* Empresas;
* Estabelecimentos;
* Postos de trabalho;
* Atividades;
* Tarefas;
* Perigos;
* Riscos profissionais;
* Trabalhadores expostos;
* Medidas preventivas;
* Medidas corretivas;
* Probabilidade;
* Gravidade;
* Nível de risco;
* Risco residual;
* Responsáveis;
* Prazos;
* Não conformidades;
* Acompanhamento das medidas.

---

# 🤖 Perspectiva AI

A evolução prevista para este projeto é a criação de uma plataforma denominada **Perspectiva AI**.

A Perspectiva AI será um assistente digital destinado a apoiar as atividades profissionais da Perspectivacontece.

A Inteligência Artificial deverá funcionar como **assistente do profissional**, ajudando na análise, organização e preparação de informação.

A decisão e validação técnica permanecerão sempre sob responsabilidade do profissional.

---

# 🏗️ Estrutura futura

A plataforma deverá evoluir para uma arquitetura modular:

```text
PERSPECTIVA AI
│
├── 🤖 Assistente IA
│
├── 👥 Clientes
│
├── 🦺 Avaliação de Riscos Profissionais
│
├── 🔎 Inspeções
│
├── 📋 Checklists
│
├── ⚠️ Não Conformidades
│
├── 📄 Relatórios
│
├── 📚 Base de Conhecimento
│
├── 📅 Agenda e Tarefas
│
└── 🎯 Gestão Comercial
```

Cada módulo deverá ser desenvolvido de forma independente sempre que possível, permitindo a evolução progressiva da plataforma.

---

# 📱 Aplicação multiplataforma

A aplicação será desenvolvida para funcionar corretamente em diferentes tamanhos de ecrã.

### Mobile-first

A utilização em telemóvel será considerada desde o início do desenvolvimento.

Durante uma visita a um cliente, o utilizador deverá conseguir:

* consultar o cliente;
* iniciar uma avaliação;
* consultar avaliações anteriores;
* registar observações;
* registar perigos;
* identificar riscos;
* definir medidas;
* consultar checklists;
* registar não conformidades;
* tirar ou associar fotografias;
* consultar tarefas;
* utilizar o assistente de IA;
* guardar informação no local.

A mesma aplicação deverá funcionar também em computador e tablet.

---

# 👥 Gestão de Clientes

Um dos módulos futuros será a gestão integrada dos clientes.

Cada cliente poderá possuir:

* Dados da empresa;
* Contactos;
* Estabelecimentos;
* Trabalhadores;
* Avaliações de risco;
* Inspeções;
* Não conformidades;
* Medidas corretivas;
* Relatórios;
* Documentos;
* Histórico;
* Tarefas;
* Datas de acompanhamento.

O objetivo é evitar a existência de informação dispersa por diferentes ferramentas.

---

# 🔎 Inspeções

A plataforma deverá permitir criar e acompanhar inspeções técnicas.

Exemplos:

* Segurança e Saúde no Trabalho;
* Avaliação de Riscos;
* SCIE;
* Auditorias;
* Verificações de conformidade;
* Acompanhamento de medidas corretivas.

Cada inspeção deverá ficar associada ao respetivo cliente e estabelecimento.

---

# 📋 Checklists

Será criado um sistema de checklists configuráveis.

As checklists poderão estar associadas a diferentes tipos de atividade.

Exemplos:

* SST;
* Avaliação de Riscos;
* SCIE;
* Evacuação;
* Meios de primeira intervenção;
* Inspeções;
* Auditorias.

O objetivo é permitir que o técnico utilize a checklist diretamente no telemóvel durante a visita.

---

# ⚠️ Não Conformidades

As não conformidades deverão poder ser registadas diretamente durante uma inspeção ou avaliação.

Cada registo poderá incluir:

* Descrição;
* Local;
* Perigo;
* Risco;
* Evidência;
* Fotografia;
* Requisito aplicável;
* Medida corretiva;
* Responsável;
* Prioridade;
* Prazo;
* Estado.

Estados possíveis:

```text
Aberta
   ↓
Em tratamento
   ↓
Resolvida
   ↓
Validada
```

---

# 📄 Relatórios

A plataforma deverá permitir gerar relatórios a partir dos dados registados.

O objetivo é reduzir o trabalho administrativo e evitar a duplicação de informação.

A informação registada durante uma visita deverá poder ser utilizada posteriormente para criar o respetivo relatório.

---

# 📚 Base de Conhecimento

A Perspectiva AI deverá possuir uma base de conhecimento técnica.

Esta base poderá incluir:

* Legislação;
* Regulamentos;
* Procedimentos;
* Normas aplicáveis;
* Modelos;
* Checklists;
* Documentação técnica;
* Metodologias;
* Documentos internos da Perspectivacontece.

A informação deverá ser organizada e pesquisável pelo agente de IA.

---

# 🤖 Assistente de IA

O assistente deverá apoiar o técnico em tarefas como:

### Durante uma visita

> "Regista esta situação como uma não conformidade."

> "Que riscos devo considerar nesta tarefa?"

> "Adiciona esta medida corretiva."

> "Mostra-me as pendências deste cliente."

### Depois da visita

> "Resume os principais riscos encontrados."

> "Prepara o relatório desta avaliação."

> "Quais as medidas que continuam pendentes?"

> "Prepara um email para o cliente."

A IA deverá sempre distinguir entre **sugestão** e **decisão técnica validada**.

---

# 📅 Agenda e Tarefas

A plataforma deverá futuramente permitir gerir:

* Visitas;
* Inspeções;
* Avaliações;
* Prazos;
* Medidas corretivas;
* Follow-ups;
* Reuniões;
* Tarefas administrativas;
* Tarefas comerciais.

O objetivo é criar um único ponto de controlo das atividades da Perspectivacontece.

---

# 🎯 Gestão Comercial

Num estágio posterior será desenvolvido um módulo de apoio comercial.

Possíveis funcionalidades:

* Leads;
* Potenciais clientes;
* Contactos;
* Propostas;
* Follow-ups;
* Emails;
* Campanhas;
* LinkedIn;
* Histórico de contactos;
* Estado da oportunidade.

A informação comercial deverá ficar separada da informação técnica, mantendo controlo de acesso adequado.

---

# 🔐 Segurança

A segurança da informação é uma prioridade.

**Nunca devem ser colocados no GitHub:**

* Passwords;
* Chaves de API;
* Tokens;
* Dados pessoais de clientes;
* Documentação confidencial;
* Informação sensível de empresas;
* Credenciais de serviços externos.

Informação confidencial deverá ser armazenada através de mecanismos apropriados de autenticação, base de dados e armazenamento seguro.

---

# 🌿 Git e controlo de versões

O projeto utiliza **Git/GitHub** para controlo de versões.

Um commit representa uma alteração guardada no histórico do projeto.

Exemplo:

```text
Commit
│
├── Nova funcionalidade
├── Correção
├── Melhoria
└── Alteração de interface
```

Alterações relevantes deverão ser acompanhadas por mensagens de commit claras.

Para funcionalidades maiores poderá ser utilizada uma branch própria:

```text
main
│
├── feature/assistente-ia
├── feature/clientes
├── feature/inspecoes
└── feature/relatorios
```

A branch `main` deverá procurar manter uma versão estável do projeto.

---

# 🗺️ Roadmap

## Fase 1 — Análise e preservação

* [ ] Analisar a aplicação existente
* [ ] Identificar todas as funcionalidades atuais
* [ ] Identificar a lógica de avaliação de risco
* [ ] Identificar o sistema de cálculo
* [ ] Identificar o armazenamento de dados
* [ ] Identificar funcionalidades a preservar
* [ ] Documentar a aplicação

## Fase 2 — Interface multiplataforma

* [ ] Interface responsive
* [ ] Otimização para telemóvel
* [ ] Otimização para tablet
* [ ] Otimização para computador
* [ ] Navegação simplificada
* [ ] Preparação para PWA

## Fase 3 — Núcleo da plataforma

* [ ] Sistema de autenticação
* [ ] Dashboard
* [ ] Gestão de clientes
* [ ] Gestão de estabelecimentos
* [ ] Gestão de tarefas
* [ ] Base de dados
* [ ] Histórico

## Fase 4 — Avaliação de Riscos Profissionais

* [ ] Integrar a ferramenta existente
* [ ] Histórico de avaliações
* [ ] Postos de trabalho
* [ ] Perigos
* [ ] Riscos
* [ ] Medidas preventivas
* [ ] Medidas corretivas
* [ ] Risco residual
* [ ] Não conformidades
* [ ] Relatórios

## Fase 5 — Inteligência Artificial

* [ ] Assistente IA
* [ ] Base de conhecimento
* [ ] Pesquisa documental
* [ ] Apoio à identificação de riscos
* [ ] Apoio à elaboração de medidas
* [ ] Apoio à análise
* [ ] Apoio à elaboração de relatórios

## Fase 6 — Inspeções

* [ ] Inspeções SST
* [ ] Inspeções SCIE
* [ ] Checklists
* [ ] Registo de fotografias
* [ ] Não conformidades
* [ ] Acompanhamento

## Fase 7 — Gestão profissional

* [ ] Agenda
* [ ] Tarefas
* [ ] Follow-ups
* [ ] Histórico de clientes
* [ ] Documentos
* [ ] Notificações

## Fase 8 — Gestão comercial

* [ ] Leads
* [ ] Potenciais clientes
* [ ] Propostas
* [ ] Contactos
* [ ] Follow-ups
* [ ] Campanhas
* [ ] Apoio ao LinkedIn

---

# 🧠 Princípios do projeto

### 1. Reutilizar

O trabalho já desenvolvido deverá ser aproveitado sempre que tecnicamente adequado.

### 2. Evoluir por fases

A plataforma será construída progressivamente, evitando alterações demasiado grandes de uma só vez.

### 3. Mobile + PC

A aplicação deverá funcionar desde o início em:

**📱 Telemóvel + 📲 Tablet + 💻 Computador**

### 4. Segurança

Os dados dos clientes deverão ser protegidos e nunca expostos no repositório público.

### 5. Modularidade

Os diferentes módulos deverão poder evoluir de forma independente.

### 6. IA como assistente

A Inteligência Artificial apoia o profissional, mas não substitui a validação técnica.

### 7. Código controlado

As alterações deverão ser registadas através do Git e manter um histórico claro do desenvolvimento.

---

# 🚀 Visão

O objetivo final é transformar esta ferramenta numa plataforma profissional que permita à Perspectivacontece centralizar o trabalho técnico, administrativo e comercial.

A visão é simples:

> **Uma única plataforma para apoiar o trabalho do técnico — antes, durante e depois da visita ao cliente.**

---

## Perspectivacontece

**Segurança que acontece.**
# Perspectivacontece-SST
