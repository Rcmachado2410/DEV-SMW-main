npm install
npm install vite@latest --save-dev
npm run dev

# 📦– Warehouse Management System (WMS)

O **SMW COMPANY* é um sistema **WMS (Warehouse Management System)** desenvolvido para gerenciar operações logísticas de ponta a ponta, desde o agendamento de caminhões até inventário, expedição, relatórios e uso mobile no armazém.

O sistema funciona com **login de usuário** e é dividido em **7 painéis principais**, cada um responsável por uma etapa da operação logística.

---

## 🏠 Home

Painel principal do sistema.

A partir dele, o usuário acessa todos os módulos do WMS de forma centralizada.

---

## 📅 Agendamentos

Módulo responsável pelo **registro de entrada e saída de caminhões**.

Ao acessar **Agendamentos**, o sistema exibe dois fluxos:

### ➜ Inbound

* Pesquisa por:

  * Data
  * INF (Nota Fiscal)
* Botão **“+”** para adicionar novos agendamentos

Ao adicionar um agendamento:

* Data
* Hora
* Cliente
* Nota Fiscal (INF)

Exibição em tabela com:

* Data
* Hora
* Cliente
* INF
* Status

Ações disponíveis:

* Editar
* Confirmar conferência
* Excluir

---

### ➜ Outbound

* Pesquisa por nota fiscal
* Filtro por status
* Tabela para acompanhamento das notas

Ações disponíveis:

* Editar
* Marcar como expedida
* Excluir

Para adicionar um outbound:

* Seleciona o veículo (quando disponível)
* Informa a INF
* Salva o registro

---

## 📥 Inbound

Módulo responsável pela **entrada de produtos no estoque**.

Este painel é dividido em três áreas principais:

### 📦 Cadastro de Produtos

Recomendado como primeiro passo.

Cadastro contendo:

* Nome do produto
* Descrição
* Código de barras
* Mapa

Os produtos cadastrados são exibidos em uma tabela para acompanhamento.

---

### 🚚 Inbound Shipment

* Filtros por:

  * Nota
  * Status
  * Data

Exibição de informações:

* Nota
* Cliente
* Status (pendente, fechada, assignada)
* Total de itens

Ações disponíveis:

* Assignar nota
* Deletar

Ao assignar uma nota:

* Seleciona a nota
* Escolhe produtos cadastrados
* Informa a quantidade
* Permite adicionar múltiplos produtos
* Salva a operação

---

### 📑 Inbound Order

Tela responsável pelo **recebimento final** dos produtos.

Fluxo de operação:

1. Cadastro do produto
2. Cadastro da SN no Inbound Shipment
3. Recebimento no Inbound Order

---

## 📊 Inventário

Módulo de controle e auditoria de estoque.

Funcionalidades:

* Cadastro de posições
* Consulta por:

  * LPN
  * Posição
  * Item
* Geração de tarefas de contagem
* Pesquisa e acompanhamento das contagens

---

## 📤 Outbound

Módulo responsável pela **saída de produtos**.

Permite:

* Criar ondas
* Realizar separações
* Acompanhar status
* Expedir pedidos

---

## 📑 Relatórios

Painel de análise e acompanhamento das operações.

Permite filtros por:

* Usuário
* Painel / área

Utilizado para visualizar:

* Atividades realizadas
* Movimentações do inventário
* Ações executadas no sistema

---

## 📱 Mobile (RFS)

Versão mobile do WMS para uso no armazém.

Funcionalidades:

* Operação direta no chão de fábrica
* Botão **Home** para retornar ao painel principal
* Botão **Sair** para encerrar a sessão

---

## ✅ Conclusão

O **SMW** centraliza toda a operação logística em um único sistema, oferecendo **controle, rastreabilidade e agilidade** para operações de inbound, outbound, inventário e gestão operacional.

O sistema também conta com suporte mobile, permitindo que o time de armazém opere diretamente via RFS.

---

📌 **Projeto em desenvolvimento** – novas funcionalidades e melhorias continuam sendo adicionadas.

