# 🎯 Interface Web de Autenticação - Prototipação e Fidelidade Figma

![HTML5](https://img.shields.io/badge/Frontend-HTML5-E34F26.svg)
![CSS3](https://img.shields.io/badge/Styles-CSS3-1572B6.svg)
![Figma](https://img.shields.io/badge/Design-Figma%20Pixel%20Perfect-F24E1E.svg)
![Status](https://img.shields.io/badge/Status-Conclu%C3%ADdo-brightgreen.svg)

## 📌 Visão Geral
Este projeto consiste na implementação em código front-end (HTML5 e CSS3) de alta fidelidade (**Pixel Perfect**) de um fluxo completo de **Autenticação e Perfil de Usuário** desenhado originalmente no **Figma**.

O trabalho exercita a conversão fidedigna de especificações de UI/UX para a web, respeitando rigorosamente espaçamentos, tipografia, contraste de cores (tema escuro esportivo/gamer), inputs com estados de foco e responsividade.

---

## 🚀 Fluxos de Telas Implementados
1. 🔐 **Login de Usuário (`index.html`)**: Formulário de autenticação com campos de e-mail/usuário, senha e links de recuperação.
2. 📝 **Criação de Conta (`criarConta.html`)**: Cadastro completo de usuário com confirmação de dados e termos de uso.
3. 🔑 **Recuperação de Senha (`recuperarSenha.html`)**: Etapa inicial para envio de e-mail de redefinição.
4. 🔢 **Verificação de Código 2FA (`codigoVerificacao.html`)**: Tela com inputs numéricos dedicados para validação de token temporário de segurança.
5. 🔄 **Redefinição de Senha (`registrarNovaSenha.html`)**: Atualização de credenciais com validação visual.
6. 👤 **Perfil do Usuário (`perfil.html`)**: Dashboard pessoal contendo foto de avatar, banner customizado (tema FURIA Esports), bio, estatísticas e configurações.

---

## 🛠️ Tecnologias e Ferramentas
- **Linguagens**: HTML5 Semântico e CSS3
- **Técnicas de Estilização**:
  - Flexbox e CSS Grid para alinhamento centralizado dos cards
  - Pseudo-classes (`:hover`, `:focus`, `:active`) para feedback táctil do usuário
  - Arquitetura de arquivos CSS modulares por tela (`criarConta.css`, `perfil.css`, etc.)

---

## 📂 Estrutura do Repositório
```plaintext
SiteFigma/
├── index.html                           # Tela de Login
├── criarConta.html                      # Tela de Cadastro
├── recuperarSenha.html                  # Tela de Solicitação de Recuperação
├── codigoVerificacao.html               # Tela de Token de Confirmação
├── registrarNovaSenha.html              # Tela de Nova Senha
├── perfil.html                          # Dashboard de Perfil do Usuário
├── CSS/                                 # Folhas de estilo individuais para cada tela
└── IMG/                                 # Banners, avatares e ícones utilizados
```

---

## ⚙️ Como Executar Localmente
Clone o repositório e abra qualquer um dos arquivos `.html` no navegador:
```bash
git clone https://github.com/LucaS4nt0s/SiteFigma.git
```

---

## 👨‍💻 Autores
Desenvolvido por **Luca Samuel dos Santos** ([@LucaS4nt0s](https://github.com/LucaS4nt0s)) e **Maria Eduarda Batista Henrique**.
