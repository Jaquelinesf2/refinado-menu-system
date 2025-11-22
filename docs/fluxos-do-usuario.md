# 🔄 Fluxos de Uso — Refinado Menu System

## 📌 1. Fluxo Completo do Cliente

1. Cliente escaneia o QR Code na mesa.
2. Sistema abre automaticamente o menu digital.
3. Cliente navega pelas categorias e escolhe produtos.
4. Cliente adiciona itens ao carrinho.
5. Cliente envia o pedido.
6. Cliente acompanha o status em tempo real:
   - Recebido  
   - Preparando  
   - Pronto  
   - Entregue  
7. Cliente solicita a conta pelo sistema.
8. Cliente seleciona a forma de pagamento (somente presencial).
9. Atendente confirma a finalização no painel.

---

## 📌 2. Fluxo do Atendente / Cozinha

1. O painel exibe novos pedidos em tempo real.
2. Cozinha atualiza o status para *Preparando*.
3. Ao finalizar o preparo, muda para *Pronto*.
4. Atendente entrega o pedido e marca como *Entregue*.
5. Atendimento registra pedidos feitos no balcão (manual).
6. Painel marca o pedido como finalizado.

---

## 📌 3. Interações Entre os Fluxos
- Cada mesa gera um QR Code único.  
- Cada pedido fica vinculado à mesa.  
- Status atualizado no painel aparece imediatamente para o cliente.  
- Pedidos manuais também entram na fila geral.
