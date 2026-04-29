# 📈 Acme Dashboard

O **Acme Dashboard** é uma plataforma de gestão financeira moderna projetada para centralizar o controle de faturas, clientes e receitas. A aplicação oferece uma interface intuitiva para monitoramento de métricas em tempo real e gerenciamento completo do fluxo de faturamento.

---

## 🖥️ Funcionalidades Principais

- **Dashboard de Visão Geral:** Gráficos de receita mensal e exibição das faturas mais recentes para decisões rápidas.
- **Gestão de Faturas:** Fluxo completo de CRUD (Criação, Leitura, Atualização e Deleção) de faturas.
- **Filtros e Pesquisa Dinâmica:** Sistema de busca em tempo real com paginação integrada à URL, permitindo compartilhamento de filtros específicos.
- **Status de Pagamento:** Monitoramento visual de faturas pendentes e pagas.
- **Autenticação Segura:** Proteção de rotas administrativas com NextAuth.js e controle de sessão.
- **Design Responsivo:** Interface otimizada para dispositivos móveis, tablets e desktops.

---

## 🛠️ Stack Tecnológica

- **Framework:** Next.js (App Router)
- **Estilização:** Tailwind CSS (com suporte a fontes otimizadas via `next/font`)
- **Banco de Dados:** PostgreSQL (Vercel Postgres)
- **Validação de Dados:** Zod
- **Gerenciamento de Formulários:** React Server Actions
- **Infraestrutura:** Vercel

---

## 📦 Estrutura da Aplicação

1.  **Login:** Área restrita para acesso ao painel.
2.  **Dashboard:** Resumo visual das finanças.
3.  **Invoices:** Listagem completa com busca e gerenciamento.
4.  **Customers:** Centralização de dados dos clientes.

---

## 🚀 Como Executar

1. **Clone o repositório:**
   ```bash
   git clone https://github.com/Brugo24/Next_AppRouter.git
   
2. **Instale as dependências:**
   ```bash
   pnpm install
   ```

3. **Configure as variáveis de ambiente:**
   Crie um arquivo `.env` na raiz do projeto com as credenciais do seu banco de dados Vercel Postgres e a chave `AUTH_SECRET`.

4. **Execute as Migrations (Se necessário):**
   ```bash
   pnpm run seed
   ```

5. **Inicie o servidor de desenvolvimento:**
   ```bash
   pnpm dev
   ```

Acesse `http://localhost:3000` para ver o resultado.
