# chatbot-telegram
Chatbot no Telegram desenvolvido com n8n que consulta a API OpenWeather e retorna a temperatura atual de cidades do Brasil.

## Descrição
Chatbot que recebe Cidade,UF e retorna a temperatura atual em °C.

## Como importar o workflow
1. Abrir n8n
2. Import from file
3. Selecionar workflow-chatbot-telegram.json

## Credenciais necessárias

### Telegram
Criar credencial Telegram API com:
TELEGRAM_BOT_TOKEN

### OpenWeather
Adicionar sua API Key no node HTTP Request
ou configurar variável de ambiente:

OPENWEATHER_API_KEY

## Como testar

Exemplos válidos:
- Belo Horizonte,MG
- Curitiba,PR
- Salvador,BA

Erro esperado:
- CidadeInexistente,ZZ
