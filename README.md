# BenderBot
Um bot para ajudar a moderar e enviar informações (in)úteis para um grupo.

O projeto ainda está em desenvolvimento e você pode colaborar. Existe uma lista de features que ainda precisam ser implementadas para que o bot possa acrescentar mais ao nosso grupo (OpenCV Brasil).

Features a serem implementadas no curto prazo:

- Comandos /mute e /unmute: Comandos para habilitar e desabilitar as interações do bot com o grupo;

- Timer para evitar que o bot flood o grupo xingando linguagens de programação;

- Comando /helpOpenCV: Comando para ser utilizado quando o usuário tiver dúvidas sobre a instalação da openCV (ambiente Linux ou Windows). O bot deve enviar um lista de links úteis contendo tutoriais/intruções da doc oficial da openCV;

- Comando /help contendo informações sobre o bot: Uma lista de palavras-chave com as quais ele interage, lista de comandos e breve descrição do que cada um faz.


Features a serem implementadas no longo prazo:

- Técnicas de Processamento de Linguagem Natural para que o bot interaja de forma semelhante à natual com os membros do grupo.

## With Docker

```
$ docker-compose build
$ docker-compose up
$ docker-compose down
```

## Without Docker

Needs: Ubuntu, Python3

```
export TELEGRAM_TOKEN=12345678:telegram_token_bot
export TELEGRAM_BOT_NAME=Bender Bot Rodrigues
$ cd src && pip install -r requirements.txt && python core.py
```