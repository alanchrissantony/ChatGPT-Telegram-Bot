# ChatGPT Telegram Bot

This is a Python script that sets up a Telegram bot that uses OpenAI's GPT (Generative Pre-trained Transformer) model to generate responses to incoming messages.

## Getting Started

- Clone this repository to your local machine.
- Install the required packages by running `pip install -r requirements.txt`.
- Set up your OpenAI API key by following the instructions in the [OpenAI documentation](https://platform.openai.com/docs/api-reference/authentication).
- Set up your Telegram bot by following the instructions in the [Telegram documentation](https://core.telegram.org/bots#3-how-do-i-create-a-bot).
- Replace the `OpenAI_API_key` and `Telegram_Bot_API` values in the script with your own API keys.
- Run the script by executing `python main.py`.

## Usage

Once the bot is running, users can send messages to it via Telegram. The bot will respond with text generated by the GPT model, up to a maximum of 60 tokens. To initiate the bot and receive a greeting message, users can type the `/start` command.

## Customization



If you want to customize the behavior of the bot, you can modify the parameters in the `generate_response` function, such as the `max_tokens` and `temperature` values. You can also modify the responses generated by the GPT model by changing the input prompts in the function. Additionally, you can add or modify the handlers in the script to implement additional functionality.
  

[Alan Chris Antony](https://github.com/alanchrissantony)
