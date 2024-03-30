[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ranvier2d2/DATA-API-Python/blob/main/DATA_API.ipynb)


# Data API Python Client

This repository contains a Python client for interacting with the DataAPI to execute data skills. The client is implemented in a Jupyter Notebook (`DATA_API.ipynb`) and provides a convenient way to send user requests to the API and receive responses.

## Features

- Easy-to-use Python client for the DataAPI
- Sends user requests to the API and retrieves responses
- Parses API responses and extracts relevant information
- Formats the dialogue between the user and the bot
- Saves user input and API responses to files for logging purposes

## Getting Started

### Prerequisites

- Python 3.x
- Jupyter Notebook
- `requests` library

### Usage

1. Run the notebook cells in order.

2. When prompted, enter your request for DATA.

3. The notebook will send the request to the DataAPI and display the formatted dialogue between the user and the bot.

4. The user will get the response in a markdown Bionic Reading style (optional) #ToDO.

5. The user input and API response will be saved to `chatlog.md` and `chatlog.txt` files for logging purposes. #ToDO.

## Code Overview

The notebook contains the following main components:

- `HeyDataAPIClient` class: Interacts with the DataAPI to execute data skills. It initializes with an API URL and has a `call_api` method that sends a POST request to the API with user input and returns the response.

- `save_to_file` function: Saves the user input and API response to files. It creates a `chatlog.md` file if it doesn't exist and appends the formatted dialogue. It also appends the user input, bot name, and response details to `chatlog.txt`.

- Main execution flow: Prompts the user for input, creates an instance of `HeyDataAPIClient`, calls the `call_api` method with the user input, parses the API response, prints the formatted dialogue, and saves the input and response to files.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

## License

This project is licensed under the Apache License 2.0. See the [LICENSE](LICENSE) file for more information.

## Acknowledgements

- [DATA](https://chat.heydata.org) for providing the data skills execution functionality.
- The open-source community for their valuable contributions and inspiration.

## Contact
Feel free to conact me on X for ML related stuff. Happy to talk! [![Twitter URL](https://img.shields.io/twitter/url/https/twitter.com/Dis_Trackted.svg?style=social&label=Follow%20%40Dis_Trackted)](https://twitter.com/Dis_Trackted)

Partner & creator at DATA.
