# Polly E-commerce 🛍️

Bem-vindo ao repositório do **Polly E-commerce**! Este projeto foi criado como parte de meus estudos em desenvolvimento web e tem como objetivo oferecer uma experiência de e-commerce moderna, responsiva e funcional.

## 📚 Visão Geral

Polly E-commerce é um projeto de aprendizado contínuo que visa desenvolver uma aplicação de e-commerce funcional, utilizando tecnologias modernas como Next.js, TailwindCSS, Prisma e MySQL. Ideal para explorar boas práticas e criar uma experiência completa para usuários e administradores.

---

## 🚀 Tecnologias Utilizadas

### **Front-end**
- **Next.js**: Framework para React com renderização server-side e client-side, ideal para performance e SEO.
- **TailwindCSS**: Framework CSS utilitário para estilização rápida e responsiva.

### **Back-end**
- **Node.js**: Ambiente de execução para JavaScript no servidor.
- **Prisma**: ORM moderno para gerenciamento de banco de dados com TypeScript.
- **Express**: Framework minimalista para construir APIs RESTful.

### **Banco de Dados**
- **MySQL**: Banco de dados relacional robusto e eficiente.

### **Outras Ferramentas**
- **TypeScript**: Superset de JavaScript com tipagem estática para maior segurança e escalabilidade.
- **Axios**: Para requisições HTTP.
- **Jest** e **Cypress**: Para testes unitários e end-to-end, respectivamente.

---

## 📋 Funcionalidades Planejadas

- Página inicial com listagem de produtos e promoções.
- Páginas detalhadas para categorias e produtos.
- Carrinho de compras com gerenciamento de itens e cálculo de totais.
- Sistema de autenticação e registro de usuários.
- Integração de formulários e animações interativas.
- Painel administrativo para gerenciamento de produtos, categorias e pedidos.
- Design responsivo e focado em boas práticas de UX/UI.

---

## 🎯 Objetivos

1. Criar uma aplicação funcional que simula um e-commerce real.
2. Aplicar conceitos de desenvolvimento front-end e back-end com tecnologias modernas.
3. Garantir escalabilidade e modularidade com boas práticas de desenvolvimento.
4. Praticar o uso de TypeScript para melhorar a qualidade do código.

---

## 🛠️ Como Rodar o Projeto

### Pré-requisitos
Certifique-se de ter as seguintes ferramentas instaladas:
- **Node.js** (v16 ou superior)
- **npm** ou **yarn**
- **MySQL**

### Passos para executar:

1. Clone o repositório:
   ```bash
   git clone https://github.com/gabriel-rocha-pimentel/polly-ecommerce.git
   cd polly-ecommerce
   ```

2. Instale as dependências:
   ```bash
   npm install
   # ou
   yarn install
   ```

3. Configure o banco de dados:
   - Crie um arquivo `.env` na raiz do projeto e adicione as variáveis de ambiente:
     ```env
     DATABASE_URL="mysql://username:password@localhost:3306/polly_ecommerce"
     ```

4. Execute as migrações do Prisma:
   ```bash
   npx prisma migrate dev
   ```

5. Inicie o servidor de desenvolvimento:
   ```bash
   npm run dev
   # ou
   yarn dev
   ```

6. Acesse o projeto no navegador:
   ```
   http://localhost:3000
   ```

---

## 🧪 Testes

Execute os testes para garantir que tudo está funcionando corretamente:

- **Testes unitários:**
  ```bash
  npm run test
  ```

- **Testes end-to-end:**
  ```bash
  npm run test:e2e
  ```

---

## 📂 Estrutura do Projeto

```plaintext
polly-ecommerce/
├── public/                # Assets estáticos
├── src/
│   ├── components/        # Componentes reutilizáveis
│   ├── pages/             # Rotas do Next.js
│   ├── services/          # Integrações de APIs e lógica de negócio
│   ├── styles/            # Estilos globais e Tailwind
│   └── utils/             # Funções auxiliares
├── prisma/                # Esquemas do banco de dados
├── .env                   # Variáveis de ambiente
├── package.json           # Dependências do projeto
└── README.md              # Documentação
```

---

## 🌟 Próximos Passos

- Implementar sistema de checkout.
- Melhorar a acessibilidade e o desempenho do site.
- Criar testes abrangentes para garantir a qualidade do código.
- Implantar a aplicação em produção (Vercel e AWS RDS).

---

## 🛠️ Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues e pull requests para melhorias.

---

## 📞 Contato

Para dúvidas ou sugestões, entre em contato:
- **E-mail:** gabrielrochapimentel.dev@gmail.com
- **GitHub:** [gabriel-rocha-pimentel](https://github.com/gabriel-rocha-pimentel)

---

Obrigado por conferir este projeto! 💻✨
