This code represents a Telegram bot written in Python using the Telebot library, enabling users to fetch the price of selected cryptocurrencies by accessing the Binance API. Upon entering the "/start" command, the bot provides users with a keyboard containing buttons to choose their desired cryptocurrency. Upon selection, the bot sends the price of the chosen cryptocurrency in a response message. To retrieve the price, the code utilizes the get_price_by_ticker function, which accesses the Binance API by providing the necessary cryptocurrency ticker.

The bot creates a user interface with buttons for selecting cryptocurrencies and interacts with the exchange API to obtain the current price. This allows users to quickly and conveniently access information about the price of selected cryptocurrencies without manually entering queries or switching to other platforms. Additionally, the code rounds the price to two decimal places, enhancing readability and clarity for the user.
<p align="center">
  ![image](https://github.com/korek293/Telegram-bot/assets/125805835/4fa4ca3f-16ff-4369-8f7f-bddae86c0732)
</p>


Such a bot can be beneficial for traders and cryptocurrency enthusiasts who seek prompt information about current prices without the need to browse or analyze data on other platforms. It demonstrates a straightforward method of creating an interactive interface within the Telegram messenger and integrating with external services via API to fetch real-time information.

