# Documento de Requisitos de Software (DRS)

## Introdução

O FitControl é um sistema de gerenciamento de academia desenvolvido para auxiliar no controle de alunos, planos, mensalidades, pagamentos, fichas de treino e acesso por catraca.

---

## Objetivo

Desenvolver uma solução para automatizar os processos administrativos e operacionais de uma academia, proporcionando melhor controle e organização.

---

## Escopo

O sistema permitirá:

- Cadastro de alunos
- Gerenciamento de planos
- Controle de mensalidades
- Registro de pagamentos
- Controle de acesso
- Criação de fichas de treino
- Emissão de relatórios

---

## Stakeholders

- Aluno
- Recepcionista
- Instrutor
- Proprietário

---

## Requisitos Funcionais

### RF01
Cadastrar aluno.

### RF02
Editar dados do aluno.

### RF03
Consultar aluno.

### RF04
Desativar aluno.

### RF05
Cadastrar planos.

### RF06
Associar plano ao aluno.

### RF07
Gerar mensalidades.

### RF08
Registrar pagamentos.

### RF09
Validar acesso.

### RF10
Liberar catraca.

### RF11
Registrar acesso.

### RF12
Criar ficha de treino.

### RF13
Editar ficha de treino.

### RF14
Consultar ficha de treino.

### RF15
Gerar relatórios.

---

## Requisitos Não Funcionais

### RNF01
O sistema deve exigir autenticação.

### RNF02
O sistema deve utilizar controle de perfis.

### RNF03
O sistema deve responder consultas em até 3 segundos.

### RNF04
O sistema deve utilizar banco de dados relacional.

### RNF05
O sistema deve registrar logs de acesso.

### RNF06
As senhas devem ser armazenadas de forma segura.

---

## Regras de Negócio

### RN01
Somente alunos ativos poderão acessar a academia.

### RN02
Mensalidades vencidas bloqueiam o acesso.

### RN03
Toda entrada deverá ser registrada no histórico.

### RN04
Cada aluno poderá possuir apenas um plano ativo.

### RN05
Somente instrutores podem alterar fichas de treino.

### RN06
Somente recepcionistas podem registrar pagamentos.

### RN07
Somente proprietários podem consultar relatórios gerenciais.
