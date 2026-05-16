# Simulador de Email

<p align="left">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" alt="Python" width="60" height="60"/>
  &nbsp;&nbsp;
  <img src="https://flagcdn.com/w80/us.png" alt="Inglês (EUA)" width="60"/>
</p>

Um simulador de email simples feito em Python utilizando Programação Orientada a Objetos. O projeto representa usuários, caixas de entrada e emails — permitindo enviar, receber, ler e excluir mensagens.

> O código foi escrito em inglês como prática do idioma.

## Funcionalidades

- Envio de emails entre usuários
- Recebimento de emails em uma caixa de entrada pessoal
- Listagem de emails com status de lido/não lido
- Abertura e exibição do conteúdo completo do email
- Marcação automática como lido ao abrir
- Exclusão de emails da caixa de entrada
- Registro de data e hora em cada email recebido

## Estrutura do Projeto

```
simuladordeemail/
└── email.py
```

O projeto é organizado em torno de três classes principais:

- **`Email`** — representa uma mensagem de email (remetente, destinatário, assunto, corpo, data/hora e status de leitura).
- **`Inbox`** — armazena e gerencia os emails recebidos por um usuário.
- **`User`** — representa uma pessoa que pode enviar emails e acessar sua caixa de entrada.

## Como Executar

Requisitos: **Python 3.x**

```bash
python email.py
```

## Exemplo de Saída

```
Email sent from Tory to Ramy!
Email sent from Ramy to Tory!

Ramy's Inbox:

Your Emails:
1. [Unread] From: Tory | Subject: Hello | Time: 2026-05-16 14:30

--- Email ---
From: Tory
To: Ramy
Subject: Hello
Received: 2026-05-16 14:30
Body: Hi Ramy, just saying hello!
------------
```

## Autor

Desenvolvido por **Matheus** como parte dos exercícios de lógica de programação.
