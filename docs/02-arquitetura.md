# 🏗️ Arquitetura do Projeto

## Visão Geral

O **TechHelp Copilot** foi projetado para atuar como um assistente virtual de suporte técnico, oferecendo respostas rápidas para dúvidas frequentes e auxiliando usuários na resolução de problemas relacionados a computadores, internet e softwares.

A arquitetura foi baseada nos conceitos apresentados pelo Microsoft Copilot Studio, utilizando uma estrutura modular que facilita a manutenção e a expansão do copiloto.

---

## Componentes da Solução

### 👤 Usuário

Pessoa que inicia a conversa com o copiloto através de um canal de atendimento.

---

### 🤖 Copilot

Responsável por:

- Receber as mensagens do usuário;
- Identificar a intenção da conversa;
- Selecionar o tópico adequado;
- Gerar respostas;
- Encaminhar para atendimento humano quando necessário.

---

### 💬 Tópicos

Os tópicos representam os principais assuntos tratados pelo copiloto.

Neste projeto foram definidos:

- Boas-vindas;
- Problemas com Internet;
- Problemas com Computador;
- Instalação de Programas;
- Atendimento Humano.

---

### 🧠 IA Generativa

A IA Generativa é utilizada para produzir respostas mais naturais quando não existe um fluxo totalmente estruturado.

Ela segue regras previamente definidas por meio de prompts para garantir respostas objetivas, claras e seguras.

---

### 👨‍💼 Atendimento Humano

Caso o copiloto não consiga resolver a solicitação do usuário, a conversa poderá ser encaminhada para um atendente humano.

---

## Fluxo Geral da Solução

1. O usuário inicia uma conversa.
2. O Copilot identifica a intenção da mensagem.
3. O tópico correspondente é selecionado.
4. A resposta é gerada.
5. Caso necessário, a IA Generativa complementa a resposta.
6. Se o problema não for resolvido, o atendimento é encaminhado para um humano.

---

## Benefícios da Arquitetura

- Organização por tópicos.
- Fácil manutenção.
- Escalabilidade.
- Respostas mais naturais.
- Melhor experiência para o usuário.

---

## Tecnologias Utilizadas

- Microsoft Copilot Studio (conceitos)
- Microsoft Power Platform
- IA Generativa
- Markdown
- Mermaid
- Git e GitHub