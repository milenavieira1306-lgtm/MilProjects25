# 📄 Planejamento Completo do Projeto MyCar

## **1. What -- O que é o MyCar?**
O MyCar é um aplicativo de gerenciamento de veículos que ajuda motoristas a acompanhar manutenções, despesas, prazos e lembretes automáticos dos veículos.

**Principais funcionalidades:**
- Cadastro de usuário  
- Cadastro de múltiplos veículos  
- Lembretes e notificações (push/e-mail)  
- Registro de manutenções  
- Histórico de eventos  
- Relatórios de despesas  

---

## **2. Why -- Por que o projeto existe?**
- Motoristas se esquecem de manutenções e prazos obrigatórios.  
- Manter o carro em dia reduz riscos, custos e imprevistos.  
- O mercado carece de apps simples e intuitivos para gestão completa do veículo.  
- Há espaço para crescimento, monetização premium e parcerias futuras (oficinas, seguradoras etc).

---

## **3. Who -- Quem participa (Equipe necessária)?**
| Função | Quantidade | Responsabilidades |
|--------|------------|------------------|
| Product Owner | 1 | Requisitos, backlog, priorização |
| Designer UX/UI | 1 | Telas, protótipos, experiência do usuário |
| Dev Mobile | 2 | App (Flutter/React Native) |
| Dev Backend | 2 | API, banco, notificações |
| QA | 1 | Testes, validações |
| Scrum Master | 1 | Organização, prazos, reuniões |

**Total: 8 pessoas**

---

## **4. Where -- Onde será desenvolvido?**
- GitHub (issues, backlog, Kanban, milestones)  
- Reuniões remotas via Teams/Discord  
- Figma, Miro, Lucidchart para design e protótipos 
- Firebase/Supabase para back-end  

---

## **5. When -- Cronograma de 1 ano:**

### **Mês 1–2: Arquitetura, requisitos e protótipos**
- Arquitetura completa do sistema  
- Requisitos funcionais e não funcionais  
- Estrutura de segurança, escalabilidade, integração e logs  
- Protótipo navegável  
- Infraestrutura inicial (banco, autenticação)

---

### **Mês 3–5: CRUDs e Funcionalidades Básicas**
- Login + perfil  
- Cadastro de veículos  
- Edição/exclusão de veículos  
- Histórico básico  
- Persistência local e remota  
- Testes unitários iniciais  

---

### **Mês 6–7: Lembretes e Notificações**
- CRUD de lembretes  
- Configuração de antecedência  
- Notificações push  
- Notificações via e-mail  
- Logs internos  

---

### **Mês 8–9: Relatórios e Histórico Completo**
- Relatórios de despesas  
- Histórico de manutenções  
- Filtros, visualizações e gráficos  
- Melhorias de UI/UX  

---

### **Mês 10–11: Estabilidade, segurança e RNFs**
Requisitos Não Funcionais implementados:
- Autenticação segura  
- Criptografia de dados sensíveis  
- Alta disponibilidade (mínimo 99%)  
- Tempo de resposta aceitável (< 600 ms)  
- Backup automático  
- Logs estruturados e monitoramento  
- Testes automatizados  
- Acessibilidade  

---

### **Mês 12: Deploy e Publicação**
- Beta fechado  
- Ajustes finais  
- Publicação na Google Play  
- Manual e documentação  
- Apresentação final aos investidores  

---

## **6. How -- Como será feito?**
- Metodologia ágil (Scrum + Kanban)  
- Sprints de 2 semanas  
- Entregas programadas para cada marco  
- Testes contínuos  
- Monitoramento de performance e segurança  
- Versionamento pelo GitHub  

---

## **7. How Much -- Quanto custará o projeto (Período de 1 ano)**

### **Custo anual da equipe (12 meses)**  
| Função | Qtde | Valor Mensal | Custo Anual |
|--------|------|---------------|--------------|
| Dev Mobile | 2 | R$ 6.000 | R$ 144.000 |
| Dev Backend | 1 | R$ 6.000 | R$ 72.000 |
| Designer | 1 | R$ 4.000 | R$ 48.000 |
| QA | 1 | R$ 3.000 | R$ 36.000 |
| Product Owner | 1 | R$ 5.000 | R$ 60.000 |
| Scrum Master | 1 | R$ 5.000 | R$ 60.000 |

**Subtotal equipe: R$ 420.000**

### Infraestrutura (Firebase, servidores, storage)
- R$ 2.000 / mês → R$ 24.000 / ano

### Reserva técnica (10%)
- R$ 43.200

## TOTAL ESTIMADO PARA 1 ANO DE DESENVOLVIMENTO: 
# R$ 475.200

## Detalhes Adicionais (Arquitetura e Monetização)

### Arquitetura Inicial do Sistema:
> Front-end (Aplicativo Mobile)

- Framework: Flutter (Android + iOS)
- Linguagem: Dart
- Gerenciamento de estado: Provider / Riverpod
- Notificações: Firebase Cloud Messaging (FCM)
- Armazenamento local: Hive ou SharedPreferences

> Back-end

- Plataforma: Firebase ou Supabase
- Autenticação: Firebase Auth / OAuth 2.0
- APIs: Funções serverless (Cloud Functions)
- Banco de dados: Firestore (Firebase) ou PostgreSQL (Supabase)
- Storage: Firebase Storage / Supabase Storage

## Modelos de Monetização:
> O MyCar terá um modelo híbrido de monetização, combinando assinatura premium, parcerias e serviços adicionais. O objetivo é gerar receita recorrente e ampliar o ecossistema do aplicativo

1. Versão Gratuita (Free)

- Acesso básico com funcionalidades essenciais:
- Cadastro de veículos
- Registro simples de manutenções
- Lembretes limitados
- Histórico básico
- Backup mensal
- A versão gratuita serve para atrair usuários e validar o produto.

2. Versão Premium (Assinatura Mensal ou Anual)

- Plano pago com recursos avançados:
- Notificações ilimitadas
- Relatórios completos de despesas
- Gráficos e análises automáticas
- Exportação de dados (PDF/CSV)
- Backup diário
- Multiveículos (nº maior permitido)
- Suporte prioritário
- Personalização de lembretes e dashboards



