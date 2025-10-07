Milena Vieira dos Santos, Eng. de Software 1, ADS 2/2025

# 🚗 MyCar

O **MyCar** é um projeto que visa auxiliar motoristas no gerenciamento de veículos, prazos de manutenção e lembretes automáticos.  
O objetivo é oferecer uma interface simples e intuitiva que ajude o usuário a manter seu carro sempre em dia com manutenções e obrigações.

---

## Objetivos do Projeto
- Permitir cadastro de usuário e de múltiplos veículos.
- Criar ferramenta de lembretes de manutenção.
- Enviar notificações (push/e-mail) de prazos próximos.
- Exibir histórico de manutenções e eventos.
- Interface clara e intuitiva para fácil uso.

---

## Backlog do Projeto
O backlog completo está nas **Issues** do repositório:

🔗 [Ver todas as Issues](../../issues)  
🔗 [Ver Milestones](../../milestones)
> Requisitos Não Funcionais incluídos
---

## Diagrama de Casos de Uso

![Diagrama de Casos de Uso](Use%20Case%20Diagram%20(1).jpg)


> O diagrama acima mostra o principal ator (usuário) e casos de uso do sistema **MyCar**.

---

## Diagrama de Sequência

![Diagrama de Sequência](Diagrama%20de%20Sequência1.jpg)


> O diagrama acima mostra o usuário e a sequência de uso do sistema **MyCar**.

---

# Histórias de Usuário - MyCar (Formato Gherkin)

## 1. Cadastro de Veículo
Feature: Cadastro de veículo
  Como usuário
  Quero cadastrar meu carro no aplicativo
  Para poder gerenciar informações e manutenções

  Scenario: Usuário cadastra um carro com dados válidos
    Given que o usuário esteja logado no sistema
    When ele acessar a tela de "Adicionar Veículo" e preencher marca, modelo, ano e placa corretamente
    Then o sistema deve salvar o novo veículo e exibir uma mensagem de sucesso.

 ## 2. Registro de Manutenção
 Feature: Registro de manutenção
  Como usuário
  Quero registrar as manutenções do meu carro
  Para acompanhar o histórico e custos

  Scenario: Usuário registra uma manutenção com dados completos
    Given que o usuário já tenha um veículo cadastrado
    When ele acessar a seção "Manutenções" e adicionar uma revisão com data, descrição e valor
    Then o sistema deve salvar o registro e atualizar o histórico do veículo.

 ## 3. Notificação de Revisão
 Feature: Notificação de revisão
  Como usuário
  Quero receber alertas de manutenção preventiva
  Para não esquecer de revisar meu carro

  Scenario: Revisão próxima da quilometragem limite
    Given que o carro do usuário esteja com 9.500 km rodados
    And exista uma revisão programada para 10.000 km
    When o usuário acessar o aplicativo
    Then o sistema deve exibir um alerta informando que a revisão está próxima.

 ## 4. Consulta de Despesas
 Feature: Consulta de despesas
  Como usuário
  Quero visualizar o total gasto com meu veículo
  Para controlar melhor meus custos

  Scenario: Usuário consulta relatório de despesas
    Given que o usuário tenha registrado abastecimentos e manutenções
    When ele acessar a tela de "Relatórios"
    Then o sistema deve exibir o total de despesas e permitir filtrar por período.

---

## Milestones
> Requisitos Funcionais
- **Milestone 1: Cadastro e Informações do Carro**  
  - Criar conta de usuário  
  - Cadastrar informações do carro  
  - Cadastrar múltiplos veículos  

- **Milestone 2: Gerenciamento de Lembretes**  
  - Criar ferramenta de lembretes  
  - Notificações push/e-mail  
  - Adicionar/editar/excluir eventos  
  - Definir antecedência de lembretes  

- **Milestone 3: Histórico e Relatórios**  
  - Histórico de manutenções  
  - Interface limpa e intuitiva  
  - Calcular prazos automáticos  
  - Mensagem de lembrete amigável  
  - Visualização geral de prazos

---

## Protótipos visuais do projeto MyCar (UI/UX)
Abaixo estão as principais telas do aplicativo **MyCar**:

> Wireframes/Projetos de Interface

- Tela de Login
- Tela de Perfil
- Cadastro de Veículo
- Configurações de Lembrete
- Histórico de Manutenções

---

## Wireframe da interface principal MyCar
Rascunho da tela principal do aplicativo com saudação e seleção de veículo.

![Wireframe Tela Principal MyCar](Wireframe%201.jpg)

---

## Wireframes adicionais MyCar
Rascunho das telas de configurações, histórico e login (cadastro).

![Wireframe Telas Adicionais MyCar](Wireframe%202.jpeg)

---

### Protótipo de interface MyCar  
Interface inicial com seleção de veículo e lembrete de manutenção.

![Protótipo Visual MyCar](Protótipo%20Visual%20MyCar.jpg)

---

### Protótipos adicionais 1 MyCar  
Cadastro de veículo, configurações de lembrete e histórico de manutenções.

![Telas adicionais MyCar](Telas%20adicionais%20MyCar.jpg)

---

### Protótipos adicionais 2 MyCar  
Tela de login e perfil do usuário com acesso às configurações e veículos cadastrados.

![Telas adicionais 2 MyCar](Telas%20adicionais%202%20MyCar.jpg)

## Tecnologias Usadas
- Miro (Diagrama de Casos de Uso); Lucidchart (Diagrama de Sequência); Microsoft Copilot (Protótipos Visuais, Wireframes); Backlog (GitHub)

---

> Uso acadêmico/educacional.  


