# Sistema de Estacionamento Inteligente

Projeto da disciplina de Circuitos Digitais do Bacharelado Interdisciplinar em Ciência e Tecnologia (BICT) da Universidade Federal do Maranhão (UFMA). O objetivo é desenvolver um sistema inteligente e autônomo para gerenciamento de vagas em um estacionamento, utilizando contagem de veículos, display de 7 segmentos e LEDs de sinalização.

---

## Sumário

- Visão geral
- Objetivos
- Justificativa
- Escopo
- Premissas
- Critérios de sucesso
- Cronograma macro
- Partes interessadas
- Equipe

---

## Visão geral

O projeto consiste em um Sistema de Estacionamento Inteligente Autônomo, capaz de administrar automaticamente a ocupação das vagas sem necessidade de interação direta dos usuários.  
O sistema monitora em tempo real a entrada e saída de veículos, utilizando sensores (ou botões que os simulam) e uma interface visual para exibição dos dados.

Todo o processamento e a tomada de decisão são feitos de forma autônoma, tornando o sistema autossuficiente.  
O usuário apenas acompanha o funcionamento e se beneficia da melhor organização do estacionamento.

---

## Objetivos

### Objetivo geral

Criar um sistema autônomo capaz de administrar e otimizar o uso de vagas em estacionamentos, reduzindo o tempo de busca por vaga e melhorando a organização, sem necessidade de interação direta do usuário.

### Objetivos específicos

- Monitorar a ocupação das vagas em tempo real.  
- Informar o condutor, por meio de uma interface visual, sobre a disponibilidade de vagas.  
- Simular ou implementar sensores de presença para detecção de entrada e saída de veículos.  
- Reduzir congestionamentos internos e melhorar o fluxo de tráfego local.  
- Utilizar LEDs para indicar o estado do sistema (disponível/ocupado/lotado).

---

## Justificativa

A gestão de estacionamentos em áreas urbanas enfrenta desafios constantes relacionados à organização, uso eficiente do espaço e fluxo de veículos.  
Motoristas frequentemente perdem tempo procurando vagas livres, o que aumenta congestionamentos internos, consumo de combustível e a frustração geral.

Além disso, muitos sistemas atuais ainda dependem de controle manual ou intervenção direta dos usuários, o que reduz a eficiência e aumenta a chance de falhas operacionais.  
Um sistema automatizado e autônomo contribui para maior confiabilidade, melhor experiência do usuário e uso mais inteligente da infraestrutura disponível.

---

## Escopo

O projeto contempla o desenvolvimento de um sistema inteligente de estacionamento capaz de:

- Monitorar e controlar automaticamente a ocupação de vagas por meio de contagem bidirecional de veículos.  
- Identificar entradas e saídas de veículos.  
- Exibir a quantidade de vagas disponíveis em um display de 7 segmentos.  
- Indicar o estado do estacionamento (disponível ou lotado) por meio de LEDs.

Será implementado um protótipo funcional (físico ou simulado), com foco em automação, confiabilidade da contagem e clareza visual para fins didáticos, sem incluir integração com aplicativos ou sistemas externos.

---

## Premissas

Para o desenvolvimento do projeto, são consideradas as seguintes premissas:

- Sensores de presença podem ser simulados por botões.  
- O sistema trabalhará com um número limitado de vagas (por exemplo, de 0 a 9), facilitando controle e visualização.  
- A equipe terá acesso às ferramentas e componentes necessários para desenvolvimento e testes.  
- O projeto será concluído dentro do prazo definido pela disciplina.  
- Os integrantes possuem conhecimento básico de circuitos digitais suficiente para implementar a lógica do sistema.

---

## Critérios de sucesso

### 1. Funcionamento do sistema

- O contador deve responder corretamente aos sinais de entrada e saída.  
- Não devem ocorrer erros de contagem, como valores negativos ou acima do limite de vagas.

### 2. Exibição correta

- O display de 7 segmentos deve representar corretamente os valores do contador.  
- A transição entre números deve ocorrer de forma estável, sem piscadas ou estados inválidos.

### 3. Controle de lotação

- O sistema deve reconhecer quando a capacidade máxima for atingida.  
- O LED de “LOTADO” deve ser acionado corretamente.  
- Novas entradas devem ser bloqueadas quando o estacionamento estiver cheio.

### 4. Clareza na apresentação

- O funcionamento do sistema deve ser facilmente compreendido pelo público-alvo.  
- O projeto deve ser bem explicado e documentado, incluindo relatórios e materiais de apoio.

---

## Cronograma macro

Etapas principais do projeto:

| Etapa                      | Descrição                          | Responsável                            |
|----------------------------|------------------------------------|----------------------------------------|
| Levantamento de requisitos | Definição do funcionamento do sistema | Equipe                                |
| Projeto lógico             | Desenho do circuito (diagramas)   | João Pedro                             |
| Implementação              | Montagem/simulação do circuito    | Leonardo Sampaio, Ruan Pactrick        |
| Testes                     | Verificação do funcionamento      | Equipe                                 |
| Ajustes                    | Correção de erros                 | Equipe                                 |
| Documentação               | Elaboração de relatório técnico   | Equipe                                 |
| Apresentação               | Demonstração final                | Todos                                  |

---

## Partes interessadas

As principais partes interessadas do projeto são:

| Parte interessada      | Representantes                                                                 | Relacionamento com o projeto                                                                                         |
|------------------------|-------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------|
| Executores do projeto  | Ruan Pactrick, Leonardo Sampaio, Marcos de Alencar, Deyvison Sousa, João Pedro Moura | Responsáveis pela concepção, planejamento, execução e entrega dos resultados do projeto.                             |
| Orientação acadêmica   | Prof. Luiz Henrique                                                          | Fornece supervisão técnica e metodológica, valida as entregas e garante alinhamento com os objetivos acadêmicos.     |
| Comunidade acadêmica   | Estudantes e professores da UFMA                                             | Beneficiários indiretos, podem usar o projeto como referência, inspiração para pesquisas ou ferramenta didática.     |

---

## Equipe

- Ruan Pactrick de Sousa e Sousa  
- Leonardo Sampaio Serra  
- João Pedro Moura de Mendonça  
- Marcos Antonio Nunes de Alencar  
- Deyvison Sousa Nogueira
