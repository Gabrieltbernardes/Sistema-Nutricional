# 🥗 Sistema de Organização Nutricional Inteligente

Este projeto visa desenvolver um **sistema inteligente de recomendação de dietas personalizadas**, considerando a **composição física** e os **gostos alimentares** dos usuários. A aplicação será voltada para pacientes, nutricionistas e administradores, com funcionalidades adaptadas para cada perfil, utilizando inteligência artificial, aprendizado adaptativo e uma interface intuitiva para acompanhamento nutricional.

---

## 🚀 Visão Geral

O **Sistema de Organização Nutricional Inteligente** oferecerá:

- **Recomendações personalizadas de dietas**
- **Substituições alimentares inteligentes**
- **Diário alimentar e monitoramento de progresso**
- **Painel para nutricionistas e administradores**
- **Integração entre frontend (React Native), backend (Java Spring Boot) e banco de dados (MySQL)**

---

## 🧭 Roadmap de Desenvolvimento

### 📌 Fase 1: Planejamento e Arquitetura

- Definição de requisitos e regras de negócio
- Casos de uso (UML) e especificações de funcionalidades
- Arquitetura do sistema:
  - Backend: Java (Spring Boot)
  - Frontend: React Native + TypeScript
  - Banco de dados: MySQL (modelo MER)
- Escolha de bibliotecas e ferramentas

### 🧩 Fase 2: Desenvolvimento do Backend (Java)

- Estruturação com Spring Boot, JPA, REST APIs
- Módulos principais:
  - Autenticação e perfis (usuário, nutricionista, admin)
  - Cadastro e recomendação de dietas
  - Substituições inteligentes com base em composição nutricional
  - Acompanhamento de métricas (peso, IMC, etc.)
- Integração com banco de dados
- Testes unitários e de integração
- Documentação via Swagger/OpenAPI

### 📱 Fase 3: Desenvolvimento do Frontend (React Native)

- Estrutura de pastas e navegação (React Navigation)
- Telas principais:
  - Login e Registro
  - Questionário inicial inteligente
  - Visualização e edição de dieta personalizada
  - Substituições alimentares com recálculo de macros
  - Diário alimentar e gráficos de progresso
  - Painéis para nutricionistas e administradores
- Consumo de APIs REST
- Testes de interface e integração

### ✅ Fase 4: Testes, Implantação e Manutenção

- Testes funcionais, de usabilidade, performance e segurança
- Otimização de código e UI
- Deploy:
  - Backend: em servidor (Ex: Render, Heroku, AWS)
  - Frontend: publicações nas lojas (Google Play / App Store)
- Monitoramento contínuo e manutenção evolutiva

---

## 🛠️ Tecnologias e Ferramentas

| Camada         | Tecnologia/Ferramenta                     |
|----------------|-------------------------------------------|
| **Frontend**   | React Native, TypeScript, Axios, Chart Kit |
| **Backend**    | Java, Spring Boot, Spring Security, JPA   |
| **Banco de Dados** | MySQL, Workbench                        |
| **Dev Tools**  | Swagger, Git, Postman, VS Code, IntelliJ  |
| **Testes**     | JUnit, Jest, React Testing Library         |
| **CI/CD (futuro)** | GitHub Actions, Docker, Firebase       |

---

## 📚 Funcionalidades Previstas

### 👤 Para Usuários (Pacientes)

- Registro e login
- Preenchimento de questionário inicial
- Dieta personalizada com substituições inteligentes
- Diário alimentar
- Gráficos de progresso (peso, IMC, ingestão calórica)
- Notificações e lembretes
- Classificação visual dos alimentos

### 🩺 Para Nutricionistas

- Cadastro de pacientes
- Criação e edição de dietas personalizadas
- Definição de regras de substituição
- Acompanhamento da evolução nutricional

### 🛡️ Para Administradores

- CRUD de usuários
- Monitoramento geral da plataforma
- Definição de diretrizes nutricionais

---

## 📈 Progresso do Projeto

| Etapa                              | Status     |
|-----------------------------------|------------|
| Planejamento e especificações     | 🟢 Em andamento |
| Arquitetura backend e frontend    | 🔜 Em breve |
| Banco de dados (MER)              | 🔜 Em breve |
| Desenvolvimento backend           | ⏳ A iniciar |
| Desenvolvimento frontend          | ⏳ A iniciar |
| Integração e testes               | ⏳ A iniciar |

---

## 📌 Contribuições Futuras

- Integração com APIs externas (ex: TACO, MyFitnessPal)
- Recomendação com base em histórico alimentar e IA
- Reconhecimento de alimentos via câmera (visão computacional)
- Gamificação e recompensas por metas atingidas
- Suporte multilinguagem

---

## 👥 Equipe

- **Gabriel Teixeira Bernardes** — _Desenvolvedor Full Stack & Idealizador do projeto_

---

## 📄 Licença

Este projeto será disponibilizado futuramente sob uma licença de código aberto (provavelmente MIT ou GPLv3).

---

## 🤝 Contribuindo

Contribuições serão muito bem-vindas! Após a publicação inicial do projeto, será disponibilizado um guia de contribuição com os padrões de código, abertura de issues e envio de pull requests.

---

## 💡 Contato

Caso tenha sugestões ou dúvidas, entre em contato via:

- [GitHub](https://github.com/Gabrieltbernardes)
- [LinkedIn](https://www.linkedin.com/in/gabriel-teixeira-bernardes-2b97ab271)

---

**Vamos transformar a nutrição personalizada em uma experiência acessível, inteligente e intuitiva!**
