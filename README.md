# DanGPT Bot-Telegram: **Rapido. Sem Limites Diarios. Modos de chat Speciais**

<div align="center">
<img src="https://raw.githubusercontent.com/karfly/chatgpt_telegram_bot/main/static/header.png" align="center" style="width: 100%" />
</div>

<p align="center">
<a href="https://t.me/chatgpt_karfly_bot" alt="Run Telegram Bot shield"><img src="https://img.shields.io/badge/RUN-Telegram%20Bot-blue" /></a>
</p>

A gente ama o [chat.openai.com](https://chat.openai.com), So que... é HORRIVEL! Tem lag, Limites diarios, e so da pra usar com uma interface web arcaica.

Este repo é o ChatGPT recriado com a API GPT-3.5-Turbo LLM como um Bot do Telegram. **Que funciona :) **

voce pode fazer o seu proprio bot, ou usar o do criador ORIGINAL: [@chatgpt_karfly_bot](https://t.me/chatgpt_karfly_bot)

## News
- *5 Mar 2023: Memoria expandida.*
- *2 Mar 2023*: Adicionado suporte a [API ChatGPT](https://openai.com/blog/introducing-chatgpt-and-whisper-apis). Está ativada por padrão e pode ser removida em `use_chatgpt_api` no arquivo config. Não esqueça de **rebuildar** sua imagem docker (`--build`).

## Funções
- Baixa latencia (Geralmente de 3 a 5 segundos) 
- Sem limite de pedidos/conversa
- Codigo em Highlight
- Modos especiais: 👩🏼‍🎓 Assistente, 👩🏼‍💻 Programador Assistente, 🎬 Especialista em Filmes... E outros
- Suporte a  [API ChatGPT](https://platform.openai.com/docs/guides/chat)
- Lista de usuarios do Telegram autorizados
- Rastreio $ do saldo gasto com a API

## Comandos do BOT
- `/nova` – Gera uma nova resposta
- `/dialogo` – Começa um novo dialogo
- `/modo` – Muda o modo
- `/saldo` – Mostra o saldo
- `/ajuda` – Mostra a ajuda

## Setup
1. Consiga sua API [OpenAI API](https://openai.com/api/) key

2. Consiga seu TelegramBot token do [@BotFather](https://t.me/BotFather)

3. Modifique `config/config.example.yml` com os seus 2 tokens e rode os 2 comandos abaixo (*Se voce se acha avançado pode mudar os arquivos em * `config/config.example.env`):
```bash
mv config/config.example.yml config/config.yml
mv config/config.example.env config/config.env
```

🔥 E agora **RODE!**:

```bash
docker-compose --env-file config/config.env up --build
```

## References
1. [*O cara*] (https://github.com/karfly/chatgpt_telegram_bot)
2. [*Build ChatGPT from GPT-3*](https://learnprompting.org/docs/applied_prompting/build_chatgpt)
