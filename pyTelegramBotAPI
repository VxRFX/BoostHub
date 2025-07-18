import telebot
import os

BOT_TOKEN = os.getenv("BOT_TOKEN")
bot = telebot.TeleBot(BOT_TOKEN)

@bot.message_handler(commands=['start'])
def start(message):
    bot.send_message(message.chat.id, "👋 Привет! Это BoostHubBot. Здесь будет накрутка Telegram и YouTube!")

bot.polling()
