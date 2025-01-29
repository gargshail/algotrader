# Algorithmic Trading Exploration

Welcome to the Algorithmic Trading Exploration project! This repository is dedicated to exploring various algorithmic trading strategies and techniques.

## Table of Contents

- [Introduction](#introduction)
- [Getting Started](#getting-started)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Algorithmic trading involves using computer algorithms to automate trading decisions. This project aims to provide a comprehensive guide to understanding and implementing different algorithmic trading strategies.

## Getting Started

To get started with this project, clone the repository and follow the installation instructions below.

## Getting API Key from Alpaca Markets

To use the trading scripts, you will need an API key from Alpaca Markets. Follow these steps to obtain your API key:

1. Sign up for an account at [Alpaca Markets](https://alpaca.markets/).
2. After logging in, navigate to the "API Keys" section in your account dashboard.
3. Click on "Generate New Key" to create a new API key.
4. Copy the `API Key` and `Secret Key` provided.

Once you have your API key and secret key, you can set them as environment variables or directly in your configuration file.

## Setting Up Your Environment

To securely store your API keys, you can use a `.env` file. Follow these steps to set up your `.env` file:

1. Create a file named `.env` in the root directory of the project.
2. Open the `.env` file in a text editor and add the following lines, replacing `your_api_key` and `your_secret_key` with your actual API key and secret key:
    ```plaintext
    ALPACA_API_KEY=your_api_key
    ALPACA_SECRET_KEY=your_secret_key
    ```
3. Save and close the `.env` file.

Your API keys will now be loaded from the `.env` file when you run the trading scripts.

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/algotrader.git
    ```
2. Navigate to the project directory:
    ```bash
    cd algotrader
    ```
3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Notebooks
Explore python notebooks in `notebooks` folder

## Streamlit Applications

`streamlit_apps` contain various streamlit applications.

you can run it using `streamlit run streamlit_apps/[application file].py

## Contributing

We welcome contributions from the community. Please read our [contributing guidelines](CONTRIBUTING.md) before submitting a pull request.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
