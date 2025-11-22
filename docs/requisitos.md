# 📘 Requisitos do Projeto — Refinado Menu System

## 📌 1. Requisitos Funcionais (RF)

### **Acesso e Navegação**
- **RF01** – O cliente deve acessar o menu digital por meio de um QR Code.
- **RF02** – O sistema deve exibir categorias e itens do cardápio.
- **RF03** – O cliente deve conseguir visualizar detalhes de cada item (descrição, preço, imagem).

### **Pedidos**
- **RF04** – O cliente deve adicionar itens ao carrinho.
- **RF05** – O cliente deve enviar o pedido diretamente pelo sistema.
- **RF06** – O sistema deve permitir acompanhar o status do pedido.
- **RF07** – O cliente deve poder solicitar a conta pelo sistema.
- **RF08** – O cliente deve informar a forma de pagamento (somente presencial).

### **Painel Administrativo / Cozinha**
- **RF09** – O painel deve exibir todos os pedidos em tempo real.
- **RF10** – O atendente deve poder atualizar o status do pedido:
  - Recebido  
  - Preparando  
  - Pronto  
  - Entregue  
- **RF11** – O atendente deve poder registrar pedidos manuais feitos no balcão.

---

## 📌 2. Requisitos Não Funcionais (RNF)

### **Performance e Qualidade**
- **RNF01** – A interface deve ser responsiva (mobile-first).
- **RNF02** – O menu deve ser carregado rapidamente após leitura do QR Code.
- **RNF03** – O sistema deve ser intuitivo e de fácil uso para qualquer cliente.

### **Arquitetura e Segurança**
- **RNF04** – O backend deve garantir integridade dos dados dos pedidos.
- **RNF05** – O sistema deve permitir escalabilidade simples caso novas mesas sejam adicionadas.
- **RNF06** – A API deve seguir boas práticas REST.

---

## 📌 3. Escopo Geral
Este documento descreve as regras essenciais do sistema e serve como base para todas as etapas seguintes:  
- Design (Figma)  
- Arquitetura  
- Desenvolvimento  
- Testes  
- Entrega
