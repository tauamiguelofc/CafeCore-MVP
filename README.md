# CafeCore-MVP
Sistema modular e responsivo para gerenciamento de cafeterias e lojas de conveniência, com controle de estoque, vendas, alertas automáticos e painéis diferenciados para clientes e proprietários. Integração com MongoDB para autenticação e controle de privilégios.


# CafeCore-MVP

## Descrição
Sistema moderno para gerenciamento de cafeterias e lojas de conveniência. Controle de estoque, vendas, notificações automáticas e dashboards diferenciados para clientes e proprietários.

## Funcionalidades

### Cliente
- Registro/Login
- Visualização de produtos e promoções
- Pedido online
- Avaliação de produtos
- Recebimento de emails
- Histórico de pedidos

### Proprietário
- Dashboard administrativo
- Gestão de produtos e usuários
- Valor total de caixa e número de clientes
- Automação de notificações e promoções
- Exportação de dados

## Estrutura
- `/server` → Backend unificado (API, modelos, utilitários)
- `/client` → Frontend React
- `/scripts` → Scripts utilitários (DB seed)
- `.env` → Variáveis secretas (Mongo URI, Gmail, JWT)

## Como Rodar
1. Clonar o repositório
2. Instalar dependências:
   ```bash
   npm install
   cd client && npm install
