# 🤖 Assistente Inteligente JR OdontoPrime com n8n e Telegram

Este projeto é um sistema de atendimento automatizado para a clínica odontológica *JR OdontoPrime, criado utilizando a plataforma **n8n, com integração de **IA (Groq Chat Model)* e envio de mensagens via *Telegram*.

---

## 📌 Objetivo

Oferecer um atendimento inicial acolhedor e inteligente aos pacientes da clínica via Telegram, com respostas personalizadas usando inteligência artificial e possibilidade de triagem automatizada.

---

## 🛠 Tecnologias e Ferramentas

- [n8n](https://n8n.io) – Plataforma de automação de workflows
- *Groq Chat Model* – Modelo de linguagem para IA conversacional
- *Simple Memory* – Armazena o contexto da conversa
- *Telegram Bot* – Canal de comunicação com os pacientes
- *JavaScript (Code Nodes)* – Lógica condicional personalizada

---

## 📲 Como funciona

1. *Telegram Trigger*: Inicia o fluxo sempre que o bot recebe uma nova mensagem.
2. *Code Node 1*: Analisa se a mensagem é uma saudação (bom dia, boa tarde, boa noite).
3. *If Node*: Decide se a mensagem será respondida com saudação ou direcionada para IA.
4. *Resposta personalizada*:
   - Se for saudação ➜ envia uma mensagem gentil com nome da clínica.
   - Caso contrário ➜ a IA responde com empatia, utilizando o contexto da conversa.
5. *Envio de mensagem final*: O bot envia a resposta pelo Telegram.

---

## 📦 Exemplo de mensagens

*Paciente:*  
> Estou com dor no dente.

*Bot (via IA):*  
> Olá! Sinto muito por isso. Me diga melhor o que está acontecendo para que possamos te ajudar da melhor forma possível.

---

## 🧠 IA com Memória

O agente de IA utiliza memória simples para manter o contexto da conversa e interagir de maneira mais humana, lembrando do que o paciente disse anteriormente.

---

## ✅ Status do Projeto

🚧 *Em desenvolvimento*  
- ✅ Detecção de saudação funcional  
- ✅ Integração Telegram OK  
- ✅ IA respondendo com contexto  
- 🔄 Próximas etapas:  
  - Agendamento com recepcionista automatizado  
  - Integração com calendário  
  - Dashboard web para controle

---

## 👨‍⚕ Autor

*Josinei Pundrich*  
> Dentista especialista em implantes e desenvolvedor em transição de carreira, apaixonado por tecnologia, IA e automações úteis para o dia a dia.

---

## 📸 Screenshots

> Adicione aqui prints do fluxo no n8n, tela do Telegram e código relevante.

---

## 📎 Licença

Este projeto é de uso pessoal e educacional. Sinta-se à vontade para estudar, adaptar e colaborar.
