# Medicao-Trabalho-Final

# Plano de Experimento – Scoping e Planejamento

## **1. Identificação básica**

## **1.1 Título do experimento**
Avaliação comparativa de técnicas de testes automatizados (Selenium vs. Cypress) em um aplicativo web.

## **1.2 ID / código**
EXP-TST-AUTO-001

## **1.3 Versão do Documento e Histórico de Revisão**
- v1.0 (23/11/2025) — Versão inicial.
- v1.1 (24/11/2025) — Adição de tabelas GQM e métricas detalhadas.
- v1.2 (28/11/2025)-  Adição de modelo conceitual, variáveis, desenho experimental, população e sujeitos, instrumentação, protocolo operacional e plano de análise de dados.
- v2.0 (12/12/2025) - Entrega Final
- v2.1 (13/12/2025) - Versão Corrigida após a apresentação 

## **1.4 Datas (criação, última atualização)**
- Criação: 23/11/2025
- Última atualização: 13/12/2025

## **1.5 Autores (nome, área, contato)**
Gabriel Oliveira – Engenharia de Software – gabrielfoliveira@hotmail.com

## **1.6 Responsável principal (PI / dono do experimento)**
Gabriel Oliveira

## **1.7 Projeto / produto / iniciativa relacionada**

* **Projeto de pesquisa aplicado em Engenharia de Software**, com foco na melhoria de processos de qualidade.
* Relacionado a **ferramentas de automação de testes** utilizadas para apoiar o desenvolvimento e aumentar a produtividade das equipes.
* Contribui para a tomada de decisão sobre **seleção de ferramentas** em ambientes reais de desenvolvimento de software.

## **2. Contexto e Problema**

## **2.1 Descrição do problema / oportunidade**

Equipes de desenvolvimento frequentemente enfrentam dificuldade para definir qual ferramenta utilizar na automação de testes funcionais. As ferramentas mais populares, **Selenium** e **Cypress**, apresentam diferentes vantagens, mas não há consenso sobre qual oferece **melhor eficácia**, **tempo de execução menor** e **mais estabilidade**.
O experimento busca responder essa lacuna comparando as duas ferramentas em condições controladas.

---

## **2.2 Contexto organizacional e técnico**

O experimento será conduzido em um **aplicativo web simples**, representativo de cenários comuns do mercado.
O ambiente inclui:

* pipeline de desenvolvimento padrão;
* execução dos testes em máquina local;
* ferramentas **open-source**;
* foco em **testes funcionais automatizados**.
  O propósito é simular a realidade de uma equipe que precisa escolher a ferramenta mais adequada sem grandes investimentos.

---

## **2.3 Trabalhos e evidências prévias (internos e externos)**

A base do experimento inclui:

* documentação oficial do **Selenium** e do **Cypress**;
* estudos acadêmicos sobre automação de testes e qualidade de software;
* benchmarks existentes na literatura que analisam desempenho, manutenção e estabilidade;
* relatos de uso das ferramentas por desenvolvedores em empresas e comunidades técnicas.
  Essas evidências mostram a relevância prática e acadêmica da comparação.

---

## **2.4 Referencial teórico e empírico essencial**

Os principais conceitos que embasam o experimento incluem:

* **Testes funcionais automatizados** e suas etapas;
* **Métricas de qualidade de software** (tempo de execução, taxa de falhas, manutenibilidade);
* Modelo **GQM (Goal–Question–Metric)** para estruturar objetivos e métricas;
* Comparações empíricas de ferramentas de automação realizadas em artigos científicos;
* Características técnicas das ferramentas, como arquitetura, API, linguagem de scripting e suporte à comunidade.

## 3. Objetivos e Questões (GQM)

## 3.1 Objetivo Geral
Analisar as ferramentas Selenium WebDriver e Cypress com o propósito de caracterizar sua eficácia, eficiência e usabilidade sob a perspectiva do desenvolvedor/testador no contexto de projetos de automação de testes web em aplicações de pequeno e médio porte.

## 3.2 Objetivos Específicos
- **O1:** Comparar a eficiência no desenvolvimento de testes
- **O2:** Avaliar o desempenho na execução dos testes
- **O3:** Mensurar a confiabilidade e estabilidade dos testes
- **O4:** Analisar a usabilidade e facilidade de manutenção

## 3.3 Tabela GQM (Goal-Question-Metric)

| Objetivo | Pergunta | Métricas |
|----------|----------|----------|
| **O1:** Eficiência no desenvolvimento | Q1.1: Qual ferramenta permite desenvolvimento mais rápido? | M1, M2 |
| | Q1.2: Qual ferramenta requer menos esforço cognitivo? | M3, M4 |
| | Q1.3: Qual ferramenta possui melhor integração com ferramentas de desenvolvimento? | M5, M6 |
| **O2:** Desempenho na execução | Q2.1: Qual ferramenta executa testes mais rapidamente? | M7, M8 |
| | Q2.2: Qual ferramenta consome menos recursos computacionais? | M9, M10 |
| | Q2.3: Qual ferramenta escala melhor com aumento de testes? | M7, M11 |
| **O3:** Confiabilidade e estabilidade | Q3.1: Qual ferramenta produz testes mais estáveis? | M12, M13 |
| | Q3.2: Qual ferramenta possui melhor tratamento de elementos assíncronos? | M14, M15 |
| | Q3.3: Qual ferramenta oferece melhor feedback em falhas? | M16, M17 |
| **O4:** Usabilidade e manutenção | Q4.1: Qual ferramenta é mais fácil de aprender? | M18, M19 |
| | Q4.2: Qual ferramenta facilita a depuração? | M20, M21 |
| | Q4.3: Qual ferramenta possui documentação mais eficaz? | M22, M23 |

## 3.4 Tabela de Métricas Detalhadas

| Métrica | Descrição | Unidade |
|---------|------------|---------|
| **M1** - Tempo de desenvolvimento | Tempo total para implementar conjunto padrão de testes | Horas |
| **M2** - Velocidade de codificação | Número de linhas de código por hora | LOC/hora |
| **M3** - Complexidade cognitiva | Pontuação em escala de complexidade percebida | Pontos (1-5) |
| **M4** - Curva de aprendizado | Tempo para implementar primeiro teste funcional | Minutos |
| **M5** - Integração com IDE | Facilidade de configuração e uso com VS Code | Pontos (1-5) |
| **M6** - Qualidade de autocompletar | Eficácia do autocompletar e sugestões de código | Pontos (1-5) |
| **M7** - Tempo de execução total | Tempo para executar suite completa de testes | Segundos |
| **M8** - Tempo médio por teste | Tempo médio de execução por teste individual | Segundos/teste |
| **M9** - Uso de CPU | Percentual de uso da CPU durante execução | Percentual (%) |
| **M10** - Uso de memória RAM | Consumo de memória durante execução | Megabytes (MB) |
| **M11** - Overhead de execução | Tempo adicional por teste ao aumentar suite | Segundos/teste |
| **M12** - Taxa de sucesso | Percentual de testes que passam consistentemente | Percentual (%) |
| **M13** - Flaky tests | Número de testes com comportamento inconsistente | Quantidade |
| **M14** - Estabilidade em waits | Eficácia no tratamento de elementos dinâmicos | Pontos (1-5) |
| **M15** - Timeouts necessários | Número de waits explícitos necessários | Quantidade |
| **M16** - Clareza de mensagens | Qualidade das mensagens de erro | Pontos (1-5) |
| **M17** - Screenshots automáticos | Qualidade e utilidade de screenshots automáticos | Pontos (1-5) |
| **M18** - Facilidade inicial | Facilidade para configuração inicial | Pontos (1-5) |
| **M19** - Intuitividade da API | Facilidade para entender e usar a API | Pontos (1-5) |
| **M20** - Ferramentas de debug | Qualidade das ferramentas de depuração | Pontos (1-5) |
| **M21** - Logs detalhados | Utilidade dos logs gerados | Pontos (1-5) |
| **M22** - Qualidade documentação | Clareza e completude da documentação | Pontos (1-5) |
| **M23** - Exemplos práticos | Qualidade e quantidade de exemplos | Pontos (1-5) |

# **4. Escopo e Contexto do Experimento**

## **4.1 Escopo funcional / de processo (incluído e excluído)**

**Incluído:**
- Testes funcionais automatizados para: Login, CRUD de produtos, carrinho de compras, checkout.
- Desenvolvimento de scripts de teste idênticos em Selenium WebDriver (com WebDriverIO) e Cypress.
- Execução local dos testes em ambiente controlado (máquina única).
- Coleta das 23 métricas definidas (tempo de desenvolvimento, execução, recursos, qualidade, usabilidade).
- Análise quantitativa (estatística) e qualitativa (percepções do desenvolvedor).

**Excluído:**
- Testes de performance (carga, stress, endurance).
- Testes de segurança (OWASP, vulnerabilidades).
- Testes cross-browser (Firefox, Safari, Edge).
- Testes em dispositivos móveis (responsive, native apps).
- Integração avançada com CI/CD (Jenkins, GitLab CI, GitHub Actions).
- Testes de acessibilidade (WCAG).
- Análise de cobertura de código (code coverage).

---

## **4.2 Contexto do estudo**
- **Tipo:** Experimento acadêmico.
- **Pesquisador:** Único, com perfil de desenvolvedor.
- **Ambiente técnico:** Computador pessoal (Windows 11), Node.js, Chrome estável.
- **Aplicação sob teste:** Sauce Demo (https://www.saucedemo.com/) - e-commerce demo padrão do setor.
- **Simulação:** Cenário realista de adoção inicial de ferramenta de automação por pequena equipe.

---

## **4.3 Premissas**
- A aplicação Sauce Demo permanecerá funcionalmente estável e acessível durante todo o período experimental.
- As ferramentas Selenium WebDriver (versão 4.x) e Cypress (versão 13.x) estarão operacionais sem mudanças de API críticas.
- O ambiente de desenvolvimento (Node.js, npm, VS Code) manterá compatibilidade.
- A documentação oficial das ferramentas será suficiente para implementação dos testes.
- O pesquisador manterá consistência nos procedimentos entre as duas condições experimentais.

---

## **4.4 Restrições**
- **Tempo:** 4 semanas totais (preparação: 1 semana, execução: 2 semanas, análise: 1 semana).
- **Recursos computacionais:** 1 computador pessoal (limitação para testes concorrentes).
- **Orçamento:** Zero (utilização exclusiva de ferramentas open-source gratuitas).
- **Acesso:** Apenas à aplicação web pública Sauce Demo (sem acesso a backend ou logs do servidor).
- **Participantes:** Apenas o pesquisador (devido a escopo do experimento e recursos).

---

## **4.5 Limitações previstas**
- **Validade externa:** Resultados aplicáveis principalmente a aplicações web de complexidade similar à Sauce Demo (CRUD básico, SPA simples).
- **Generalização limitada:** Percepções baseadas em único pesquisador com perfil específico (intermediário, conhecimento prévio em JavaScript).
- **Ambiente artificial:** Execução local não reflete totalmente ambientes corporativos com CI/CD, testes paralelos, múltiplos browsers.
- **Evolução das ferramentas:** Conclusões válidas para as versões testadas (Selenium 4.x, Cypress 13.x) podem não se aplicar a versões futuras.
- **Escopo funcional limitado:** Testes realizados não cobrem cenários complexos como upload de arquivos, drag-and-drop, testes de iframes.

## 5. Stakeholders e Impacto Esperado

## 5.1 Stakeholders Principais
- Pesquisador/autor do TCC
- Orientador acadêmico
- Comunidade de desenvolvedores/testadores
- Equipes de desenvolvimento de software

## 5.2 Interesses e Expectativas
- Evidências concretas para seleção de ferramentas
- Entendimento de trade-offs entre Selenium e Cypress
- Diretrizes para adoção em diferentes cenários

## 5.3 Impactos Potenciais
- Influência na decisão de ferramentas em projetos futuros
- Melhor entendimento dos pontos fortes e fracos de cada ferramenta
- Redução de tempo e custo em processos de seleção tecnológica

## 6. Riscos de Alto Nível e Critérios de Sucesso

## 6.1 Riscos de Alto Nível
- **Técnico:** Instabilidade na aplicação demo
- **Tempo:** Não conclusão dentro do prazo do TCC
- **Validade:** Resultados não generalizáveis

## 6.2 Critérios de Sucesso Globais
- Coleta completa de pelo menos 20 das 23 métricas
- Análise estatisticamente significativa das métricas quantitativas
- Documentação clara dos procedimentos e resultados

## 6.3 Critérios de Parada Antecipada
- Impossibilidade de configurar ambas ferramentas
- Problemas críticos na aplicação demo não resolvíveis
- Restrições de tempo que impossibilitem coleta mínima de dados

## 7. Modelo Conceitual e Hipóteses

### 7.1 Modelo Conceitual do Experimento

O modelo conceitual proposto estabelece que as diferenças arquiteturais entre Selenium WebDriver (arquitetura cliente-servidor) e Cypress (arquitetura única em Node.js) resultam em impactos significativos em quatro dimensões principais de avaliação:

```mermaid
graph TD
    A[Ferramenta de Automação] --> B[Selenium WebDriver]
    A --> C[Cypress]
    
    B --> D[Arquitetura Cliente-Servidor]
    C --> E[Arquitetura Node.js Integrada]
    
    D --> F[Variáveis Dependentes]
    E --> F
    
    F --> G[Eficiência Desenvolvimento]
    F --> H[Desempenho Execução]
    F --> I[Confiabilidade Testes]
    F --> J[Usabilidade]
```

### 7.2 Hipóteses Formais (H0, H1)

| Hipótese | Nulo (H0) | Alternativo (H1) | Direção |
|----------|-----------|------------------|---------|
| **H1** | Não há diferença no tempo de desenvolvimento entre as ferramentas | Cypress requer menos tempo de desenvolvimento que Selenium | Unicaudal |
| **H2** | Não há diferença no tempo de execução dos testes | Cypress executa testes mais rapidamente que Selenium | Unicaudal |
| **H3** | Não há diferença na estabilidade dos testes | Selenium produz testes mais estáveis que Cypress | Unicaudal |
| **H4** | Não há diferença na usabilidade percebida | Cypress possui melhor usabilidade que Selenium | Unicaudal |

### 7.3 Nível de Significância e Considerações de Poder
- **Nível de significância (α):** 0.05
- **Poder estatístico (1-β):** 80% (mínimo)
- **Tamanho de efeito considerado relevante:** d = 0.8 (grande efeito)
- **Justificativa:** Considerando a natureza exploratória do estudo e restrições de amostra, optou-se por detectar apenas efeitos grandes.

## 8. Variáveis, Fatores, Tratamentos e Objetos de Estudo

### 8.1 Objetos de Estudo
- **Aplicação Web:** Sauce Demo (https://www.saucedemo.com/)
- **Scripts de Teste:** 5 casos de teste funcionais (login, navegação, adição ao carrinho, checkout, logout)
- **Ambiente:** Windows 11, Node.js 18+, Chrome 119+

### 8.2 Sujeitos / Participantes (Visão Geral)
- **Perfil:** Desenvolvedor full-stack com experiência intermediária
- **Quantidade:** 1 pesquisador (estudo piloto)
- **Experiência:** 2+ anos em desenvolvimento web, conhecimentos básicos em ambas ferramentas

### 8.3 Tabela de Variáveis Independentes (Fatores) e Seus Níveis

| Fator | Níveis | Descrição |
|-------|--------|-----------|
| **Ferramenta de Automação** | Selenium WebDriver | Framework tradicional com arquitetura cliente-servidor |
| | Cypress | Framework moderno com arquitetura integrada Node.js |
| **Ordem de Aplicação** | Selenium → Cypress | Grupo A: Exposto primeiro ao Selenium |
| | Cypress → Selenium | Grupo B: Exposto primeiro ao Cypress |

### 8.4 Tabela de Tratamentos (Condições Experimentais)

| Tratamento | Descrição | Combinações |
|------------|-----------|-------------|
| **Controle** | Selenium WebDriver com WebDriverIO | Ferramenta: Selenium<br>Binding: WebDriverIO<br>Linguagem: JavaScript |
| **Experimental** | Cypress Framework | Ferramenta: Cypress<br>Versão: 13.6.0<br>Linguagem: JavaScript |

### 8.5 Tabela de Variáveis Dependentes (Respostas)

| Variável | Métrica | Descrição | Unidade |
|----------|---------|-----------|---------|
| **Tempo Desenvolvimento** | M1 | Tempo total para implementar testes | Horas |
| **Velocidade Codificação** | M2 | Linhas de código por hora | LOC/hora |
| **Tempo Execução** | M7 | Tempo total execução suite | Segundos |
| **Uso CPU** | M9 | Percentual médio de uso da CPU | % |
| **Taxa Sucesso** | M12 | Percentual de testes bem-sucedidos | % |
| **Flaky Tests** | M13 | Número de testes inconsistentes | Quantidade |
| **Facilidade Uso** | M18 | Pontuação em escala Likert | 1-5 |

### 8.6 Variáveis de Controle / Bloqueio

| Variável | Método de Controle | Justificativa |
|----------|-------------------|---------------|
| **Hardware** | Mesmo computador para todos testes | Eliminar variação de performance |
| **Aplicação** | mesma versão Sauce Demo | Consistência do sistema sob teste |
| **Navegador** | Chrome versão 119 | Eliminar variações entre browsers |
| **Conhecimento Prévio** | Treinamento padronizado | Reduzir viés de aprendizado |

### 8.7 Possíveis Variáveis de Confusão Conhecidas

| Variável | Efeito Potencial | Estratégia de Mitigação |
|----------|------------------|------------------------|
| **Fadiga** | Pior performance no segundo tratamento | Contrabalanceamento da ordem |
| **Learning Effect** | Melhora performance no segundo tratamento | Período de washout |
| **Variações Ambiente** | Impacto nos tempos de execução | Múltiplas execuções |

## 9. Desenho Experimental

### 9.1 Tipo de Desenho
**Desenho Intra-sujeitos com Medidas Repetidas e Contrabalanceamento**

**Justificativa:** 
- Maximiza poder estatístico com amostra pequena
- Controla variabilidade entre sujeitos
- Adequado para comparação direta de ferramentas

### 9.2 Randomização e Alocação
- **Randomização:** Ordem dos tratamentos randomizada por moeda
- **Alocação:** Pesquisador único exposto a ambas condições
- **Ferramenta:** Random.org para definição da sequência

### 9.3 Balanceamento e Contrabalanço
- **Balanceamento:** 1 sujeito em ambas condições
- **Contrabalanço:** Ordem AB/BA randomizada
- **Washout Period:** 48 horas entre tratamentos

### 9.4 Número de Grupos e Sessões
- **Grupos:** 1 grupo único
- **Sessões:** 2 sessões principais (1 por ferramenta)
- **Repetições:** 3 execuções por suite de testes
- **Duração:** 5 horas por ferramenta (total 10 horas)

---

## 10. População, Sujeitos e Amostragem

### 10.1 População-Alvo
Desenvolvedores full-stack com experiência intermediária em desenvolvimento web (2-5 anos de experiência), trabalhando em projetos de pequeno e médio porte que utilizam JavaScript/TypeScript.

### 10.2 Critérios de Inclusão de Sujeitos
- Experiência com JavaScript/TypeScript (≥2 anos)
- Conhecimento de testes manuais de software
- Familiaridade com ferramentas de desenvolvimento web (Node.js, npm)
- Disponibilidade para 10 horas de participação

### 10.3 Critérios de Exclusão de Sujeitos
- Experiência avançada (≥1 ano) em Selenium ou Cypress
- Envolvimento prévio no desenvolvimento das ferramentas
- Impossibilidade de completar todas as sessões experimentais

### 10.4 Tamanho da Amostra Planejado
- **Total:** 1 participante (estudo piloto)
- **Por grupo:** 1 (desenho intra-sujeitos)
- **Justificativa:** Restrições de tempo e recursos para TCC; foco em validar metodologia

### 10.5 Método de Seleção / Recrutamento
- **Tipo:** Amostra de conveniência
- **Fonte:** Próprio pesquisador
- **Processo:** Auto-recruitement com aplicação dos critérios de inclusão/exclusão

### 10.6 Treinamento e Preparação dos Sujeitos
- **Duração:** 1 hora por ferramenta
- **Conteúdo:** Tutorial oficial básico + overview da arquitetura
- **Material:** Documentação oficial + exemplos básicos
- **Avaliação:** Implementação de 1 teste simples para verificação

## 11. Instrumentação e Protocolo Operacional

### 11.1 Instrumentos de Coleta

| Instrumento | Descrição | Métricas Coletadas |
|-------------|-----------|-------------------|
| **Planilha Tempos** | Google Sheets para registro de tempos | M1, M2, M4, M7, M8 |
| **Scripts Performance** | Comandos para monitorar recursos do sistema | M9, M10 |
| **Relatórios Testes** | Saída dos frameworks de teste | M12, M13 |
| **Questionário Usabilidade** | Formulário com escala Likert | M3, M5, M6, M14-23 |
| **Logs Desenvolvimento** | Registro de problemas e insights | Dados qualitativos |

### 11.2 Materiais de Suporte
- **Instruções para Participantes:** Guia com objetivos e procedimentos
- **Checklist de Configuração:** Ambiente de desenvolvimento
- **Template Código:** Estrutura básica para ambos frameworks
- **Formulário Consentimento:** Termo de participação voluntária

### 11.3 Fluxograma do Protocolo Operacional

```mermaid
flowchart TD
    A[Início do Experimento] --> B[Pré-Experimento]
    
    subgraph B [Pré-Experimento]
        B1[Recrutamento e Triagem] --> B2[Treinamento Inicial]
        B2 --> B3[Configuração Ambiente]
        B3 --> B4[Randomização Ordem]
    end
    
    B --> C{Ordem Definida}
    C -->|Selenium Primeiro| D[Sessão Selenium]
    C -->|Cypress Primeiro| E[Sessão Cypress]
    
    subgraph D [Sessão Selenium]
        D1[Desenvolvimento Testes] --> D2[Coleta Métricas M1-M6]
        D2 --> D3[Execução Testes 3x]
        D3 --> D4[Coleta Métricas M7-M17]
        D4 --> D5[Questionário Usabilidade]
    end
    
    subgraph E [Sessão Cypress]
        E1[Desenvolvimento Testes] --> E2[Coleta Métricas M1-M6]
        E2 --> E3[Execução Testes 3x]
        E3 --> E4[Coleta Métricas M7-M17]
        E4 --> E5[Questionário Usabilidade]
    end
    
    D --> F[Washout Period 48h]
    E --> G[Washout Period 48h]
    F --> E
    G --> D
    
    D --> H[Pós-Experimento]
    E --> H
    
    subgraph H [Pós-Experimento]
        H1[Consolidação Dados] --> H2[Análise Estatística]
        H2 --> H3[Entrevista Final]
    end
    
    H --> I[Relatório Final]
```

### 11.4 Procedimento Experimental Detalhado

**Fase 1 - Preparação (2 horas)**
1. Configuração do ambiente de desenvolvimento
2. Instalação de Selenium WebDriver + WebDriverIO
3. Instalação do Cypress
4. Clone da aplicação Sauce Demo
5. Preenchimento do formulário de consentimento

**Fase 2 - Execução por Ferramenta (5 horas cada)**
1. **Desenvolvimento (3 horas):** Implementação dos 5 casos de teste
   - Registro de tempo inicial e final
   - Contagem de linhas de código
   - Anotações de dificuldades encontradas
2. **Execução (1 hora):** 3 execuções completas da suite
   - Medição de tempos de execução
   - Monitoramento de recursos do sistema
   - Registro de falhas e inconsistências
3. **Avaliação (1 hora):** Preenchimento do questionário de usabilidade

**Fase 3 - Análise (3 horas)**
1. Consolidação de todos os dados coletados
2. Análise estatística preliminar
3. Entrevista final de percepções

### 11.5 Plano de Piloto
- **Participantes:** 1 (próprio pesquisador)
- **Objetivos:** Validar instrumentos, estimar tempos, identificar problemas
- **Critérios de Ajuste:** 
  - Se tempo desenvolvimento >6h: reduzir escopo de testes
  - Se instabilidade aplicação: buscar alternativa
  - Se problemas configuração: documentar solução

## 12. Plano de Análise de Dados (Pré-Execução)

### 12.1 Estratégia Geral de Análise
Análise mista quantitativa-qualitativa, com foco em:
- **Estatística descritiva** para caracterizar as métricas
- **Testes inferenciais** para comparar as ferramentas
- **Análise qualitativa** para compreender percepções

### 12.2 Métodos Estatísticos Planejados

| Questão | Métricas | Método Estatístico | Justificativa |
|---------|----------|-------------------|---------------|
| **Q1** Tempo Desenvolvimento | M1, M2 | Teste t pareado | Comparação direta entre ferramentas |
| **Q2** Desempenho Execução | M7, M8 | ANOVA medidas repetidas | Múltiplas execuções |
| **Q3** Confiabilidade | M12, M13 | Teste McNemar | Dados binários (sucesso/falha) |
| **Q4** Usabilidade | M18-23 | Estatística descritiva | Dados ordinais escala Likert |

### 12.3 Tratamento de Dados Faltantes e Outliers
- **Dados faltantes:** Exclusão listwise para análise pareada
- **Outliers:** Identificação com método IQR (1.5*IQR)
- **Valores extremos:** Manutenção com justificativa documentada

### 12.4 Plano de Análise para Dados Qualitativos
- **Método:** Análise de conteúdo temática
- **Processo:** Codificação aberta → categorização → temas emergentes
- **Fontes:** Anotações de desenvolvimento, comentários questionários
- **Software:** Excel/Google Sheets para organização

# **13. Avaliação de Validade (Ameaças e Mitigação)**

### **13.1 Validade de Conclusão**
- **Ameaça:** Com apenas um participante (n=1), análises estatísticas terão poder insuficiente para detectar diferenças pequenas ou moderadas entre as ferramentas.
- **Mitigação:** Foco em **tamanhos de efeito grandes** (d > 0.8) clinicamente relevantes para decisão prática. Análise descritiva detalhada dos dados brutos (tempos absolutos, percentuais) complementará testes inferenciais. O experimento será tratado como **estudo piloto** que valida a metodologia para pesquisas futuras com mais participantes.

### **13.2 Validade Interna**
- **Ameaça:** **Efeito de aprendizagem específico por ferramenta** - conhecimento adquirido com Selenium (ex: lidar com waits explícitos) pode beneficiar desproporcionalmente o uso do Cypress (que tem abordagem diferente para assincronicidade), ou vice-versa, criando uma causa alternativa para diferenças observadas.
- **Mitigação:** **Contrabalanceamento rigoroso** (ordem Selenium→Cypress vs Cypress→Selenium randomizada) e **período de washout de 48 horas** entre sessões para reduzir transferência de conhecimento específico. **Blindagem parcial** mantendo o pesquisador sem acesso a benchmarks prévios durante a fase de desenvolvimento.

### **13.3 Validade de Constructo**
- **Ameaça:** **Incompatibilidade de constructs entre ferramentas** - "facilidade de uso" pode significar coisas diferentes em Selenium (configuração de drivers) vs Cypress (instalação via npm). Algumas métricas (ex: "linhas de código") podem não equivaler entre APIs com diferentes níveis de abstração.
- **Mitigação:** **Triangulação de métricas** - cada constructo (ex: "eficiência") será medido por múltiplos indicadores (tempo de desenvolvimento + linhas de código + esforço cognitivo percebido). **Definições operacionais claras** adaptadas a cada ferramenta no protocolo.

### **13.4 Validade Externa**
- **Ameaça:** **Contexto excessivamente específico** - resultados podem não se generalizar para: aplicações web complexas (SPAs com heavy JavaScript), testes que envolvem múltiplos domínios/iframes, ou equipes com perfis de experiência diferentes (totalmente iniciantes ou especialistas).
- **Mitigação:** **Documentação hiperdetalhada do contexto**: stack tecnológica exata, versões das ferramentas, perfil técnico do pesquisador, características da aplicação Sauce Demo. **Delimitação explícita** no relatório dos cenários onde os resultados são mais aplicáveis (pequenas/médias aplicações web com CRUD).

### **13.5 Resumo das Principais Ameaças e Estratégias**

| Ameaça | Como se manifesta NO MEU EXPERIMENTO | Crítica | Estratégia de Mitigação ESPECÍFICA |
|--------|--------------------------------------|---------|-------------------------------------|
| **Tamanho amostral unitário** | Único participante (pesquisador) pode ter viés inconsciente ou experiência atípica | Alta | Tratar como **piloto metodológico**; coletar dados qualitativos ricos; documentar passo a passo para replicação com mais devs |
| **Viés de familiaridade prévia** | Experiência anterior com testes manuais/web pode beneficiar uma arquitetura (ex: entender HTTP ajuda mais no Selenium) | Média | Mapear conhecimento prévio antes do experimento; usar contrabalanceamento; incluir métrica de "curva de aprendizado inicial" (M4) |
| **Instabilidade do SUT** | Sauce Demo é aplicação externa; mudanças não controladas podem quebrar scripts entre sessões | Média | **Snapshot local** da aplicação; scripts com verificações de saúde antes de cada execução; plano B com aplicação dockerizada própria |
| **Efeito de ordem com aprendizado assimétrico** | Aprender Selenium primeiro pode "estragar" a experiência com Cypress (ou vice-versa) ao criar expectativas irreais | Média | **Washout period** com atividade técnica não relacionada; questionário pós-sessão sobre expectativas; randomização da ordem |
| **Generalização limitada** | Conclusões válidas apenas para apps similares à Sauce Demo (login+CRUD básico) | Média | **Especificação clara do domínio** testado; recomendação explícita de onde NÃO usar os resultados (ex: testes de performance) |


## 14. Ética, Privacidade e Conformidade

### 14.1 Questões Éticas
- **Auto-experimentação:** O pesquisador é também o sujeito do estudo, o que elimina questões de coerção.
- **Transparência:** Todos os procedimentos e objetivos serão documentados abertamente.
- **Risco mínimo:** O experimento não apresenta riscos físicos ou psicológicos significativos.

### 14.2 Consentimento Informado
- **Processo:** Auto-consentimento documentado através de formulário assinado digitalmente.
- **Conteúdo:** Incluirá objetivos, procedimentos, riscos/benefícios, e garantia de que pode desistir a qualquer momento.
- **Armazenamento:** Mantido em repositório seguro com acesso restrito.

### 14.3 Privacidade e Proteção de Dados
- **Dados coletados:** Tempos de desenvolvimento/execução, métricas de performance, respostas de questionário.
- **Anonimização:** Não aplicável (auto-experimento).
- **Armazenamento:** Dados em Google Sheets com acesso restrito ao pesquisador.
- **Retenção:** Dados mantidos por 2 anos após conclusão do TCC.

### 14.4 Aprovações Necessárias
- **Comitê de Ética:** Não requerido para auto-experimentação acadêmica.
- **Orientador:** Prof. Danilo de Quadros Maia Filho.
- **Instituição:**  Pontifícia Universidade Católica (PUC) - conforme normas para trabalhos acadêmicos.
- **Disciplina:** Medição e Experimentação em Engenharia de Software.

## 15. Recursos, Infraestrutura e Orçamento

### 15.1 Recursos Humanos e Papéis
| Papel | Responsável | Responsabilidades |
|-------|-------------|-------------------|
| **Pesquisador Principal** | Gabriel Oliveira | Design, execução, análise, documentação |
| **Orientador** | Prof. Danilo de Quadros Maia Filho | Revisão, orientação metodológica |

### 15.2 Infraestrutura Técnica Necessária
- Computador pessoal (Windows 11, 8GB RAM, SSD)
- Conexão à Internet para download de dependências
- Node.js 18+ instalado
- Chrome Browser versão 119+
- VS Code com extensões básicas

### 15.3 Materiais e Insumos
- Licenças: Todas ferramentas são open-source (gratuitas)
- Formulários: Google Forms para questionários
- Planilhas: Google Sheets para coleta de dados
- Repositório: GitHub para versionamento

### 15.4 Orçamento e Custos Estimados
| Item | Custo Estimado | Justificativa |
|------|---------------|---------------|
| **Horas do pesquisador** | 40 horas (sem custo) | Atividade acadêmica |
| **Infraestrutura** | R$ 0,00 | Uso de recursos pessoais |
| **Ferramentas** | R$ 0,00 | Software open-source |
| **Total** | **R$ 0,00** | - |

## 16. Cronograma, Marcos e Riscos Operacionais

### 16.1 Macrocronograma
| Atividade | Semana 1 | Semana 2 | Semana 3 | Semana 4 |
|-----------|----------|----------|----------|----------|
| **Planejamento** | ✓ | | | |
| **Configuração Ambiente** | | ✓ | | |
| **Piloto** | | ✓ | | |
| **Execução Selenium** | | | ✓ | |
| **Execução Cypress** | | | ✓ | ✓ |
| **Análise Dados** | | | | ✓ |
| **Documentação** | ✓ | ✓ | ✓ | ✓ |

### 16.2 Dependências entre Atividades
1. Configuração do ambiente → Pré-requisito para piloto
2. Piloto concluído → Pré-requisito para execução principal
3. Coleta de dados completa → Pré-requisito para análise

### 16.3 Riscos Operacionais e Plano de Contingência
| Risco | Probabilidade | Impacto | Ação de Contingência |
|-------|--------------|---------|---------------------|
| **Falha hardware** | Baixa | Alto | Backup em nuvem diário; usar computador alternativo |
| **Problemas aplicação demo** | Média | Médio | Ter aplicação local de backup; usar mocks |
| **Interrupções pessoais** | Média | Médio | Buffer de tempo no cronograma (20%) |
| **Erros configuração** | Alta | Baixo | Documentar procedimentos; script de setup |

## 17. Governança do Experimento

### 17.1 Papéis e Responsabilidades Formais
- **Decisor:** Gabriel Oliveira 
- **Executor:** Gabriel Oliveira
- **Revisor:** Danilo de Quadros Maia Filho
- **Informado:** Colegas de classe, comunidade acadêmica da PUC

### 17.2 Ritos de Acompanhamento
- **Reuniões com orientador:** Semanais (30 minutos)
- **Checkpoints:** Após piloto e após cada sessão experimental
- **Revisão final:** Após análise completa dos dados

### 17.3 Controle de Mudanças
- **Proposta:** Documentada em issue no GitHub
- **Análise:** Impacto no cronograma, recursos e validade
- **Aprovação:** Pesquisador + Orientador
- **Registro:** Atualização no histórico de versões

## 18. Plano de Documentação e Reprodutibilidade

### 18.1 Repositórios e Convenções
- **Repositório principal:** GitHub (privado durante execução)
- **Estrutura:** `/docs`, `/scripts`, `/data`, `/results`
- **Convenção nomes:** `YYYY-MM-DD_descricao_tipo.ext`
- **Versionamento:** Git com commits descritivos

### 18.2 Templates e Artefatos Padrão
- Template de plano de experimento (este documento)
- Template de formulário de consentimento
- Template de planilha de coleta de dados
- Template de questionário de usabilidade

### 18.3 Empacotamento para Replicação
- **Pacote incluirá:** Scripts de setup, dados anonimizados, instruções passo a passo
- **Documentação:** README detalhado com pré-requisitos e procedimentos
- **Licença:** Creative Commons Attribution
- **Disponibilização:** GitHub público após defesa do TCC

## 19. Plano de Comunicação

### 19.1 Públicos e Mensagens-chave
| Público | Mensagem Principal | Canal | Frequência |
|---------|-------------------|-------|-----------|
| **Orientador(Prof. Danilo de Quadros Maia Filho)** | Progresso, problemas, resultados | Reunião, e-mail | Semanal |
| **Colegas de classe** | Compartilhamento aprendizados | Sala de aula | Após conclusão |
| **Comunidade acadêmica** | Resultados e metodologia | Publicação, GitHub | Final do projeto |

### 19.2 Canais de Comunicação
- **Interno:** E-mail, reuniões presenciais
- **Externo:** GitHub, fóruns acadêmicos
- **Documentação:** Relatório técnico, artigo

### 19.3 Pontos de Comunicação Obrigatórios
1. Início do experimento
2. Conclusão da coleta de dados
3. Resultados preliminares
4. Conclusão e resultados finais

## 20. Critérios de Prontidão para Execução

### 20.1 Checklist de Prontidão
- [ ] Plano de experimento aprovado pelo orientador
- [ ] Ambiente de desenvolvimento configurado e testado
- [ ] Instrumentos de coleta preparados (planilhas, questionários)
- [ ] Piloto executado e ajustes incorporados
- [ ] Consentimento informado assinado
- [ ] Cronograma detalhado definido
- [ ] Plano de backup de dados estabelecido

### 20.2 Aprovações Finais
- **Aprovador principal:** Prof. Danilo de Quadros Maia Filho
- **Forma de registro:** E-mail
- **Critério:** Checklist completo
- **Data limite:** 13/12/2025



