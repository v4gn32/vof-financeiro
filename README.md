# 💰 VOF-Financeiro

Sistema web de **gestão financeira pessoal** completo, desenvolvido com Angular, Node.js, PostgreSQL e Docker. O projeto é baseado em uma planilha real de controle financeiro, com funcionalidades modernas como lançamento de despesas, receitas, emissão de notas fiscais (MEI), e dashboard interativa.

---

## 📌 Funcionalidades

- ✅ Autenticação de usuários (admin e comum)
- ✅ Dashboard com totais e gráficos
- ✅ Lançamentos de receitas e despesas
- ✅ Suporte a parcelamentos
- ✅ Categorias e formas de pagamento
- ✅ Lançamento de Notas Fiscais (MEI)
- ✅ Filtros por período e tipo de transação
- ✅ Visualização em cards e tabelas
- ✅ Gestão de usuários (apenas admin)
- ✅ Responsivo para desktop e mobile

---

## 🧱 Tecnologias Utilizadas

### Frontend

- Angular 20
- TypeScript
- Tailwind CSS

### Backend

- Node.js + Express
- Prisma ORM
- PostgreSQL
- JWT para autenticação

### Outros

- Docker e Docker Compose
- Figma (protótipos de layout)
- GitHub Projects (organização do desenvolvimento)

---

## 🚀 Como rodar o projeto

### Pré-requisitos

- Git
- Node.js
- Docker + Docker Compose

### Passos iniciais

```bash
# Clone o repositório
git clone https://github.com/v4gn32/vof-financeiro.git
cd vof-financeiro

# Suba o ambiente com Docker (quando configurado)
docker-compose up
