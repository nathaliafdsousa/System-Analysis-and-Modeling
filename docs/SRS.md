# Software Requirements Specification(SRS)
## Sistema de Gerenciamento de Biblioteca 📚
---
## 📌 Preparação
### Atribuição de papéis
- **Stakeholders** : Representam usuários finais do sistema,bibliotecários,estudantes,professores.
- **Analistas de Requisitos**: Responsáveis por conduzir entrevistas e documentar requisitos.
- **Facilitador**: Atua como mediador,assegurando que todos os participantes contribuam e o que o processo de levantamento seja conduzida de forma organizada.

### Propósito
Desenvolver um **sistema de gerenciamento de biblioteca** que permita:
- **Cadastro de livros**: Garantir organização e restreabildade do acervo.
- **Empréstimos e Devoluções**: Permitir controle eficiente do fluxo de materiais.
- **Gestão de multa de atraso**: Assegurar responsabildade no uso dos recursos.
- **Relátorios de uso** : Fornecer informações estratégicas para acompanhamento e tomada de decisão.

---
## 📌 Levantamnto de Requisitos
### Necessidades dos Stakeholders
- Como **bibliotecário**,quero cadastrar novos livros rapidamente,com campos obrigatórios como título,autor,ISBN,categoria
- Como **bibliotecário**,quero registrar empréstimos e devoluções de forma simples
- Como **estudante**,quero renovar um empréstimo online,sem necessidade de deslocamento
- Como **professor**,quero consultar relatórios de uso da biblioteca para acompanhar a frequência dos alunos e identificar padrões de comportamento.
- Como,**usuários em geral**,quero receber notificações sobre prazo de devoluções para evitar multas e manter boa reputação

### Analistas de requisitos
- Quais informações mínimas deve ser obrigatório para o cadastro de livros e usuários?
- Como o sistema deve calcular multas(Valor fixo ou valor porcentual do livro)?
- Quais relatórios são prioritários para professores e bibliotecários (ex.: livros mais emprestados, usuários com maior número de atrasos)
- O sistema deve permitir integração com plataforma externa?(ex:sistema escolar)

---
## 📌Classificação e Priorização
### Requisitos funcionais
| ID   | Requisito | Detalhamento | Prioridade |
|------|-----------|--------------|------------|
| RF01 | Cadastro de livros | Deve incluir título, autor, ISBN e categoria. | Alta |
| RF02 | Cadastro de usuários | Deve incluir nome, matrícula, curso e tipo de usuário. | Alta |
| RF03 | Registro de empréstimos e devoluções | Deve atualizar status do livro e do usuário. | Alta |
| RF04 | Renovação de empréstimos online | Permitida se não houver reserva pendente. | Média |
| RF05 | Relatórios de uso | Deve gerar relatórios sobre acervo e frequência. | Média |

### Requisitos Não Funcionais
| ID    | Requisito | Detalhamento | Prioridade |
|-------|-----------|--------------|------------|
| RNF01 | Desempenho | Processar uma renovação em menos de 2 segundos. | Alta |
| RNF02 | Acessibilidade | Compatível com navegadores modernos e dispositivos móveis. | Média |
| RNF03 | Segurança | Autenticação de usuários e proteção de dados pessoais. | Alta |
| RNF04 | Usabilidade | Interface intuitiva, menus claros e feedback visual. | Média |







  

