# 🐲 Twitter Clone

Uma aplicação web inspirada no Twitter, permitindo **criar posts**, **ver publicações de outros usuários** e **comentar**.  
Desenvolvido com **React** no frontend e **Node.js/Express** no backend.

---

## 🚀 Tecnologias
**Frontend:** React, React Router DOM, Axios, CSS Modularizado  
**Backend:** Node.js, Express, CORS, Nodemon

---
## 📂 Estrutura do Projeto
```bash
twitter-clone/ <br>
├── backend/ <br>
│ ├── routes/ # Rotas da API <br>
│ ├── controllers/ # Lógica das rotas <br>
│ ├── app.js # Configuração do servidor <br>
│ └── package.json <br>
├── frontend/ <br>
│ ├── src/ <br>
│ │ ├── Components/ # Componentes reutilizáveis (PostCard, Navbar) <br>
│ │ ├── Pages/ # Páginas (Home, Post) <br>
│ │ ├── App.jsx # Roteamento principal <br>
│ │ └── App.css # Estilos globais <br>
│ ├── package.json <br>
├── package.json <br>
└── README.md <br>
```
---

## ⚡ Funcionalidades

- Listagem de posts com título, conteúdo e usuário  
- Navegação para página individual de post  
- Formulário para criar posts  
- Comentários em posts  
- Estilização moderna com CSS e efeitos de hover  

---

## 🛠️ Rotas da API

### Posts
- **GET** `/posts` → Lista todos os posts  
- **POST** `/posts` → Cria um novo post  

### Comentários
- **GET** `/comments/:postId` → Lista comentários de um post  
- **POST** `/comments` → Cria um comentário em um post  

---

## 💻 Instalação

Clone o projeto:

```bash
git clone https://github.com/Pedrolucas0106/twitter_clone/tree/main/twitter-clone-main
cd twitter-clone
```
Backend

```bash
cd backend
npm install
npm run dev
```

O servidor backend iniciará em: http://localhost:3000

Frontend
```bash
cd frontend
npm install
npm run dev
```

O servidor frontend iniciará em: http://localhost:5173 (ou a porta que o Vite usar)

---

## 📌 Observações 
Certifique-se de que o backend esteja rodando antes de acessar o frontend. <br>
O frontend consome os endpoints do backend para listar e criar posts. <br>
O CSS é moderno, com sombras, transições e cores inspiradas no Twitter. <br>

---
Pedro Lucas Pereira de Sousa
Estudante de informática, apaixonado por programação e desenvolvimento web.
