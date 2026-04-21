# Moraes Tech - Soluções de TI de Alta Precisão 💻

Bem-vindo ao repositório oficial da **Moraes Tech**! Este é um projeto de Landing Page moderno, desenhado para apresentar soluções tecnológicas de forma clara e profissional, focado em conversão de leads e automação do primeiro contato em Brasília (DF).

## 🌐 Acesso Rápido (Live Demo)
Você pode acessar o projeto finalizado e em funcionamento diretamente através do GitHub Pages:
👉 **[CLIQUE AQUI PARA ACESSAR O SITE](https://gabrielmoraesti93.github.io/MoraesTech/Index.html)**

---

## 🚀 Funcionalidades

- **Landing Page (Index.html)**: Apresentação premium de especialidades (formatação, remoção de vírus, infraestrutura de redes e suporte corporativo), com ancoragem fluida e seções bem definidas.
- **Sistema de Orçamento Automatizado (suporte.html)**: Formulário inteligente de triagem técnica. Coleta dados vitais do cliente (nome, localização em Brasília, melhor horário e preferência de atendimento) e encaminha a solicitação detalhada diretamente para o e-mail da equipe.
- **Integração de E-mail Serverless**: Utilização do **FormSubmit** para processamento do formulário estático, eliminando a necessidade de um backend dedicado (PHP/Node.js).
- **Portal de WhatsApp (whatsapp.html)**: Subpágina dedicada para criar um "funil" amigável e focado antes de abrir o aplicativo do cliente, detalhando SLAs (tempo de resposta) e garantias.
- **Dark Mode Ready**: A estrutura de cores foi configurada considerando tokens de superfície responsivos, garantindo legibilidade.

## 🛠️ Tecnologias Utilizadas

O projeto foi construído de forma intencionalmente leve (Vanilla/Estático) para garantir tempo de carregamento zero e máxima compatibilidade:

- **HTML5 Semântico**: Base estrutural limpa.
- **Tailwind CSS (via CDN)**: Framework CSS utilitário. Todo o "Design System" (cores hexadecimais, fontes e bordas) foi injetado via script de configuração para facilitar a manutenção.
- **Google Fonts**: 
  - `Manrope`: Utilizada para títulos pesados (Headlines) dando um visual corporativo moderno.
  - `Inter`: Utilizada para corpo de texto, garantindo a melhor legibilidade possível.
- **Material Symbols (Google)**: Ícones vetoriais modernos e escaláveis.

## 📁 Estrutura de Arquivos

```text
📦 MoraesTech
 ┣ 📜 Index.html     # Página inicial (Home / Serviços / Vantagens)
 ┣ 📜 suporte.html   # Formulário de abertura de chamado/orçamento
 ┣ 📜 whatsapp.html  # Página de redirecionamento e contato rápido
 ┗ 📜 README.md      # Documentação do projeto
```

## ⚙️ Como executar localmente

Por ser uma aplicação totalmente *front-end* e estática, não há necessidade de instalação de pacotes complexos (`npm` ou `yarn`).

1. Clone este repositório para a sua máquina:
   ```bash
   git clone https://github.com/gabrielmoraesti93/MoraesTech.git
   ```
2. Dê um clique duplo no arquivo `Index.html` para abri-lo diretamente em qualquer navegador moderno (Chrome, Edge, Safari, Firefox).
3. Todo o CSS (Tailwind) será carregado instantaneamente via CDN (requer conexão com a internet).

## ✉️ Configuração do Formulário (Aviso Importante)

O arquivo `suporte.html` utiliza o **FormSubmit** (`https://formsubmit.co/`). 
Para que os e-mails cheguem corretamente:
1. Faça um envio de teste no navegador.
2. O FormSubmit exigirá uma verificação (Anti-Spam).
3. Vá até a caixa de entrada do e-mail configurado e clique no link de ativação enviado pelo FormSubmit.
4. A partir daí, todos os envios cairão direto na sua caixa de entrada formatados corretamente!

---
*Moraes Tech © 2026. Soluções precisas para um mundo digital melhor. | Precise solutions for a better digital world.*
