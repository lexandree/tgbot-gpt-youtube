# Telegram Bot with ChatGPT connection via node.js  
## (text and voice)  
## Usage:  
1. Create OpenAI key  
2. Create your telegram bot with @BotFather and save token to access the HTTP API  
3. Create your vm, install docker on it. I did it for free on Oracle Cloud  
4. Clone this repository  
5. Place both tokens in /config/production.json like this:  
  {  
      "TELEGRAM_TOKEN": "18xxx:KecYAxx",  
      "OPENAI_KEY": "sk-EIoFxxxxx",  
      "TEST_ENV": "prod"  
  }  
 6. Create docker image with 'make build'  
 7. Run container with 'make start'  
 
 Source:  
 https://selectel.ru/blog/tutorials/tgbot-with-chatgpt
