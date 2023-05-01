
# Command Line Chat Bot with OpenAI API

This is a command line chat bot that uses OpenAI's GPT-3 API to generate human-like responses to user queries. It is written in Python and requires an OpenAI API key to work.

## Installation

To install the command line chat bot, follow these steps:

1. Clone this repository to your local machine.
```
git clone https://github.com/chibuezedev/command-line-chat-bot.git
```

2. Install the required Python packages using pip.
```
pip install -r requirements.txt
```

3. Set your OpenAI API key as an environment variable.
```
export OPENAI_API_KEY=your_api_key
```

## Usage

To start the chat bot, run the `chatbot.py` file.
```
python chatbot.py
```

The chat bot will ask you to enter a prompt to start the conversation. Type in your prompt and press Enter.

The chat bot will then generate a response based on your prompt using the OpenAI API. You can continue the conversation by entering more prompts and receiving more responses.

To exit the chat bot, type `exit` or `quit` and press Enter.

## Configuration

You can configure the chat bot by editing the `config.py` file. This file contains the following options:

- `MAX_TOKENS`: The maximum number of tokens to generate for each response. Defaults to 100.
- `STOP`: A list of tokens that, if generated, will cause the chat bot to end the response. Defaults to `['.', '?', '!']`.
- `TEMPERATURE`: A float value between 0 and 1 that controls the randomness of the response. Higher values will result in more random responses. Defaults to 0.5.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contributing

If you would like to contribute to this project, please open an issue or submit a pull request.