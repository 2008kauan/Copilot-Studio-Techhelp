# Casos de Teste

## Objetivo

Este documento apresenta cenários de teste para validar o comportamento esperado do TechHelp Copilot.

O objetivo é garantir que os fluxos de conversa estejam funcionando conforme planejado e que o usuário receba respostas adequadas para cada situação.

---

# Caso de Teste 01

## Cenário

Usuário inicia a conversa.

### Entrada

> Olá

### Resultado Esperado

O TechHelp Copilot apresenta a mensagem de boas-vindas e pergunta como pode ajudar.

---

# Caso de Teste 02

## Cenário

Problemas com Internet.

### Entrada

> Minha internet caiu.

### Resultado Esperado

O copiloto identifica o tópico "Problemas com Internet", solicita mais informações e apresenta sugestões iniciais para diagnóstico.

---

# Caso de Teste 03

## Cenário

Problemas com Computador.

### Entrada

> Meu notebook está muito lento.

### Resultado Esperado

O copiloto identifica o tópico correspondente e fornece orientações básicas para análise do problema.

---

# Caso de Teste 04

## Cenário

Instalação de Programas.

### Entrada

> Como instalar o Python?

### Resultado Esperado

O copiloto apresenta um passo a passo para instalação do Python e pergunta se o usuário conseguiu concluir o processo.

---

# Caso de Teste 05

## Cenário

Solicitação de atendimento humano.

### Entrada

> Quero falar com um atendente.

### Resultado Esperado

O TechHelp Copilot informa que a solicitação será encaminhada para um atendente humano.

---

# Caso de Teste 06

## Cenário

Pergunta fora do escopo.

### Entrada

> Qual é o melhor time do mundo?

### Resultado Esperado

O copiloto informa que atende apenas assuntos relacionados ao suporte técnico.

---

# Caso de Teste 07

## Cenário

Pergunta não compreendida.

### Entrada

> asjdh123 @@##

### Resultado Esperado

O TechHelp Copilot exibe a mensagem de fallback e solicita que o usuário reformule a pergunta.

---

# Critérios de Sucesso

O teste será considerado aprovado quando:

- O tópico correto for identificado.
- A resposta estiver de acordo com o fluxo definido.
- O usuário receber uma orientação clara.
- O atendimento for escalado quando necessário.

---

# Conclusão

A execução desses testes garante que o comportamento do TechHelp Copilot esteja alinhado com os requisitos definidos para o projeto, proporcionando uma experiência consistente para o usuário.