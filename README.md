# Desafio Product Owner — Datacrazy

## 📌 Projeto

Revitalização da tela de **Produtos do Datacrazy**, com foco em transformar a experiência atual em uma estrutura preparada para gestão multicanal e integrações externas.

## 🎯 Objetivo

Evoluir a gestão de produtos para permitir:

- Cadastro e edição de produtos
- Busca, filtros e paginação
- Gestão de estoque
- Associação de produtos a canais de venda
- Identificadores externos por canal
- Status e histórico de sincronização
- Integração com sistemas externos de catálogo e estoque
- Estrutura preparada para novos canais

## 💡 Solução

A proposta utiliza o **Product como fonte central dos dados**, mantendo as informações específicas de cada canal separadas.

```text
Product
   │
   └── ProductChannel
         ├── TikTok Shop
         ├── Shopify
         └── Mercado Livre
