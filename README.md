<p align="center">
  <img src="./images/logo.png" width=40%>
</p>
<h1 align="center">Retenção-Grad</h1>
<p align="center">
  Plataforma inteligente para apoio à permanência estudantil
</p>

---

# 📖 Descrição

Este repositório apresenta a atividade avaliativa desenvolvida na disciplina de Processos de Software e Engenharia de Requisitos, do Instituto Federal de Educação, Ciência e Tecnologia Farroupilha (IFFar) — Campus São Borja, como requisito parcial para aprovação na disciplina.

O projeto tem como foco o levantamento e a especificação de requisitos do sistema **Retenção-Grad**, uma plataforma proposta para auxiliar no combate à evasão nos cursos de graduação da instituição.

O cenário apresentado descreve um índice preocupante de evasão estudantil identificado pelo IFFar. Como solução, foi proposta uma plataforma inteligente capaz de integrar dados acadêmicos dos estudantes, permitindo a emissão de alertas e o gerenciamento de planos de intervenção.

Atualmente, essas informações encontram-se distribuídas em diferentes sistemas e planilhas manuais, dificultando a identificação rápida de alunos em situação de risco e comprometendo ações preventivas de retenção estudantil.

# 🎯 Objetivo

Identificar quais indicadores acadêmicos e administrativos a coordenação considera críticos para sinalizar o risco de evasão e compreender o fluxo de gestão de trancamentos e planos de intervenção.

# 👥 Stakeholders

### 1. Coordenação de Curso: 
Focada no monitoramento de índices de retenção, análise de desempenho por turma e gestão de trancamentos.

### 2. Docentes: 
Focados em identificar sinais precoces de desinteresse, queda de rendimento e falta de engajamento em sala de aula.

### 3. Núcleo de Apoio ao Estudante (CAE/SAP/SRA): 
Focado em fatores socioeconômicos, apoio psicológico e orientação de carreira para alunos em risco.

# 🧠 Técnicas de Elicitação

## 📋 Entrevista

## Objetivo da Entrevista

A entrevista tem como objetivo compreender os fatores relacionados à evasão estudantil, identificar dificuldades enfrentadas pela instituição no acompanhamento acadêmico e levantar necessidades para o desenvolvimento do sistema **Retenção-Grad**.

## Stakeholder Entrevistado

- Coordenação de Curso

## 📋 Roteiro da Entrevista

### **1. Indicadores de evasão**
Quais indicadores são utilizados para identificar risco de evasão dos alunos? Além de dados métricos (notas, frequência, entregas e acesso ao ambiente virtual), existem fatores não métricos percebidos, como questões socioeconômicas, pessoais ou de trabalho? Como essas informações são registradas e acompanhadas?

### **2. Momento de intervenção**
Em que momento é possível perceber que um aluno está propenso a abandonar o curso e quais critérios orientam a decisão de intervenção da coordenação? Que tipos de ações normalmente são realizadas nesses casos?

### **3. Monitoramento acadêmico**
Como ocorre atualmente o monitoramento do desempenho das turmas e dos alunos? Com que frequência essas análises são feitas e quais dificuldades existem nesse acompanhamento?

### **4. Identificação de problemas**
Quais as maiores dificuldades para identificar eventuais problemas antes que o aluno abandone o curso? De que forma um sistema poderia apresentar informações acadêmicas para permitir a identificação rápida de problemas?

### **5. Planejamento acadêmico e evasão**
Durante o planejamento das disciplinas e horários do semestre, existem estratégias adotadas para reduzir a evasão? A organização da carga horária ou a distribuição das disciplinas influencia na permanência dos alunos? Abandonar uma disciplina representa necessariamente evasão do curso ou são situações distintas?

### **6. Comunicação institucional**
Como ocorre a comunicação entre coordenação, professores e setores de apoio institucional (como CAE/SAP) no acompanhamento de alunos em risco? Existe algum processo ou informação adicional considerado essencial para fortalecer ações de retenção estudantil?

## 📝 Questionário

## Objetivo do Questionário

O questionário tem como objetivo identificar quais fatores acadêmicos, financeiros, psicológicos e sociais mais influenciam a permanência dos estudantes no curso, além de compreender quais formas de apoio institucional são consideradas mais relevantes para auxiliar na redução da evasão estudantil.

## Perguntas do Questionário

### **1. Intenção de evasão**

Com que frequência você já pensou em desistir do curso?

**Escala de resposta:**
- (1) Nunca
- (2) Raramente
- (3) Às vezes
- (4) Frequentemente

### **2. Fatores que influenciam a permanência no curso**

Em que medida os aspectos abaixo influenciam sua permanência no curso?

**Itens avaliados:**
- Trabalho
- Tempo para estudo
- Psicológico/Financeiro
- Deveres familiares

**Alternativas da grade:**
- Não influencia
- Influencia pouco
- Influencia moderadamente
- Influencia muito

### **3. Impactos das dificuldades no desempenho acadêmico**

Quando apresenta dificuldades, o quanto elas costumam afetar os aspectos acadêmicos abaixo?

**Itens avaliados:**
- Frequência
- Notas baixas
- Entrega de tarefas
- Interação em aula
- Acompanhar matérias

**Alternativas da grade:**
- Não afeta
- Afeta levemente
- Afeta moderadamente
- Afeta muito

### **4. Retorno percebido do esforço acadêmico**

Você sente que o esforço dedicado às disciplinas está sendo compensado pelo conhecimento adquirido?

**Escala de resposta:**
- (1) Não sinto retorno vindo do esforço
- (2) Sinto pouco retorno
- (3) Sinto retorno moderado
- (4) Sinto forte retorno e motivação

### **5. Importância dos apoios institucionais**

Quais apoios institucionais você considera mais importantes para ajudar estudantes a permanecer no curso?

**Itens avaliados:**
- Coordenação de SI
- Docentes
- Núcleo de apoio ao estudante (CAE, SAP, SRA)

**Alternativas da grade:**
- Pouco importante
- Moderadamente importante
- Importante
- Muito importante

# ⚙️ Requisitos do Sistema

## ✅ Requisitos Funcionais

### RF001 — Visualizar dados unificados dos alunos
O sistema deverá exibir os principais dados dos alunos (perfil, frequência, desempenho acadêmico, disciplinas cursadas e indicadores de risco) centralizados em uma dashboard única para o coordenador do curso.

### RF002 — Importar diários de classe
O sistema deverá permitir que o docente ou coordenador importe o diário de classe de cada disciplina contendo frequência e informações acadêmicas.

### RF003 — Visualizar acompanhamento individual do aluno
O sistema deverá permitir acessar a visão detalhada de um aluno específico, apresentando histórico acadêmico, disciplinas vinculadas, indicadores de desempenho e alertas registrados.

### RF004 — Identificar automaticamente o risco de infrequência
O sistema deverá analisar dados de frequência por disciplina e emitir alertas automáticos ao docente quando forem identificados riscos de abandono da disciplina.

### RF005 — Identificar riscos de evasão do curso
O sistema deverá processar dados cadastrais, acadêmicos e comportamentais previamente registrados para identificar automaticamente alunos com potencial risco de evasão, exibindo alertas aos usuários responsáveis.

### RF006 — Gerenciar notificações institucionais automáticas
O sistema deverá enviar notificações automáticas para diferentes perfis institucionais conforme o nível de risco identificado (ex.: alertas de infrequência para docentes e alertas de evasão para coordenadores).

### RF007 — Importar e analisar semestralmente as notas
O sistema deverá permitir a importação das notas finais do semestre para compor o histórico de desempenho acadêmico do aluno e possibilitar análise evolutiva.

### RF008 — Enviar mensagens automatizadas para estudantes
O sistema deverá gerar e enviar mensagens pré-formatadas para estudantes identificados com risco de evasão, utilizando canais institucionais definidos (ex.: e-mail institucional).

### RF009 — Encaminhar alunos para apoio estudantil
O sistema deverá permitir o encaminhamento de alunos em risco para serviços institucionais de apoio estudantil (assistência pedagógica, psicológica ou social).

### RF010 — Exibir histórico de intervenções
O sistema deverá registrar e apresentar o histórico de intervenções realizadas, incluindo datas de alertas, notificações enviadas, encaminhamentos realizados e comunicações institucionais relacionadas ao aluno.

## 🚀 Requisitos Funcionais Evolutivos

### RFE001 — Importação dos conselhos de classe
O sistema poderá permitir a importação de registros e observações provenientes dos conselhos de classe, auxiliando na identificação de padrões relacionados ao desempenho e permanência dos estudantes.

### RFE002 — Registro automatizado de presença
O sistema poderá realizar o registro automatizado de presença dos estudantes por meio de integrações futuras com sistemas institucionais ou tecnologias de controle de acesso.

## 🔒 Requisitos Não Funcionais

### RNF001 — Interoperabilidade de formatos
O sistema deverá operar de forma independente do SIGAA, não exigindo integração direta com a plataforma para recebimento e processamento de dados acadêmicos.

### RNF002 — Segurança e privacidade de dados sensíveis
O sistema deverá garantir a proteção e confidencialidade dos dados acadêmicos, pessoais e socioeconômicos dos estudantes, restringindo o acesso às informações conforme o perfil institucional do usuário.

### RNF003 — Periodicidade do processamento de indicadores
O sistema deverá processar e atualizar os indicadores de evasão em intervalos máximos de 15 dias, garantindo informações recentes para acompanhamento institucional.

# 👨‍💻 Colaboradores

### Naiele de Ávila Fagundes
📍 Instituição: Instituto Federal de Educação, Ciência e Tecnologia Farroupilha (IFFAr) — Campus São Borja <br>
🐙 GitHub: https://github.com/NaieleFagundes <br>
✉️ email: `naiele.11092@aluno.iffar.edu.br`

### Lian Lago Silva
📍 Instituição: Instituto Federal de Educação, Ciência e Tecnologia Farroupilha (IFFAr) — Campus São Borja <br>
🐙 GitHub: https://github.com/lian14s <br>
✉️ email: `lian.41056@aluno.iffar.edu.br`

### Raiane da Silva Silveira
📍 Instituição: Instituto Federal de Educação, Ciência e Tecnologia Farroupilha (IFFAr) — Campus São Borja <br>
🐙 GitHub: https://github.com/Raiane-ssilva <br>
✉️ email: `raiane.42080@aluno.iffar.edu.br`

### Lian Lago Silva
📍 Instituição: Instituto Federal de Educação, Ciência e Tecnologia Farroupilha (IFFAr) — Campus São Borja <br>
🐙 GitHub: https://github.com/floresTiago <br>
✉️ email: `tiago.85032@aluno.iffar.edu.br`

# 🎓 Disciplina
**Processos de Software e Engenharia de Requisitos**  

Instituto Federal de Educação, Ciência e Tecnologia Farroupilha — Campus São Borja  

Docente: *Rafael Baldiati Parizi*  

Semestre: *2026/1*
