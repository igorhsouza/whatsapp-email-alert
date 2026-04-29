<h1 align="center">⚡ Website Contact Alert Bot ⚡</h1>

<p align="center">
<img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=22&pause=1000&color=8A2BE2&center=true&vCenter=true&width=700&lines=Lead+Capture+Automation;Email+to+WhatsApp+Alert;Real-Time+Notification+System;Built+with+n8n+%2B+WAHA" />
</p>

<p align="center">
<img src="https://img.shields.io/badge/n8n-Automation-111111?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Gmail-Trigger-8A2BE2?style=for-the-badge"/>
<img src="https://img.shields.io/badge/WAHA-WhatsApp-111111?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Realtime-Alerts-8A2BE2?style=for-the-badge"/>
</p>

---

## Overview

Automação para captura de leads enviados pelo formulário "Fale Conosco" do site e envio imediato de alerta via WhatsApp.

O objetivo é reduzir o tempo de resposta e evitar perda de contato com clientes.

<img width="853" height="229" alt="image" src="https://github.com/user-attachments/assets/6ba11bce-50eb-4577-afc1-ab4121a01eca" />

---

## Capabilities

- monitoramento contínuo de e-mails  
- identificação de novas mensagens do formulário  
- leitura automática do conteúdo  
- envio de alerta em tempo real via WhatsApp  
- marcação de e-mails como lidos  

---

## Stack

- n8n  
- Gmail API  
- WAHA API (WhatsApp)  

---

## Core Features

- alerta imediato de novos leads  
- integração direta com WhatsApp  
- automação sem intervenção manual  
- fluxo leve e eficiente  
- execução contínua  

---

## Flow

Gmail Trigger → Get Message → Process → WhatsApp Alert → Mark as Read


---

## Use Case

Sempre que um cliente envia mensagem pelo site:

1. o e-mail é recebido  
2. o sistema captura automaticamente  
3. a mensagem é processada  
4. um alerta é enviado no WhatsApp  
5. o e-mail é marcado como lido  

---

## Security

- dados sensíveis removidos  
- credenciais substituídas  
- pronto para ambiente self-hosted  

---

## Setup

1. Importar JSON no n8n  
2. Configurar credenciais:
   - Gmail  
   - WAHA API  
3. Ajustar filtros de e-mail  
4. Ativar workflow  

---

## Notes

O foco do sistema não é responder automaticamente,  
mas garantir que nenhum lead fique sem atendimento.

---

## Author

Igor Henrique  
Automation • Data • Systems
