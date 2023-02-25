import telegram

bot_token = '6059262884:AAG6EYrUsWYmXldLnDE3oX1kHsrIi7ZNQ48'
chat_id = '5484339949'

# create a bot object
bot = telegram.Bot(6059262884:AAG6EYrUsWYmXldLnDE3oX1kHsrIi7ZNQ48)

# send a document to the bot
document_path = '/path/to/document.pdf'
bot.send_document(chat_id=chat_id, document=open(document_path, 'rb'))
