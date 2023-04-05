<a name="readme-top"></a>

[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![GPL 3.0][license-shield]][license-url]


<!-- ABOUT THE PROJECT -->
## About The Project

Escape every sweeper on Ethereum and Binance Smart Chain. The counter tool provided in this repo is easy to read because of the nature of python and super effective because of its bulletproof funcitonality. A simple to use help-yourself tool in understandable source code language provided to you.

### Built With

[![Python][Python]][PythonURL]

### Prerequisites

In order to run this tool, you need to download Python 3.10. Python is maybe THE most easiest programming language to understand. Good for you, so you dont need to be an educated coder to run this tool.

Download & Install Python 3.10 from [https://www.python.org/downloads/](https://www.python.org/downloads/)

IMPORTANT! Make sure to click "Add Python to Path" in the beginning of the installation. Like so:

![Add to Path](https://i.ibb.co/KV7pCsT/win-installer.png)

### Required third party services

Because of complexity and userfriendliness I decided to optain data from external API provider including Alchemy and Moralis. Also Tenderly has been included for quick simulation of the outcome, so you can enjoy a seamless experience saving tokens out of your compromised wallet.

Required API Keys:

1. Alchemy (Fetching ERC20, ERC721, ERC1155 tokens)
   * Go to https://dashboard.alchemy.com
2. Moralis (Fetching BEP20 tokens)
   * Go to https://admin.moralis.io
3. Tenderly (Simulating transactions)
   * Go to https://dashboard.tenderly.co

### Installation and Usage

1. Install the requirements. Open up a terminal for that in the main directory
   ```py
   pip install -r requirements.txt
   ```
2. Insert details of compromised wallet, safe wallet, required api keys and chain details in the `config.json`
3. Run the beast!
   ```py
   py sweeperEscape.py
   ```

<!-- LICENSE -->
## License

Distributed under the GNU Public License v3.0. See `LICENSE.txt` for more information.

<!-- CONTACT -->
## Contact

EVMJunkie - [@evmjunkie](https://twitter.com/evmjunkie) - dope@evmjunkie.xyz

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/evmjunkie/sweeper-escape.svg?style=for-the-badge
[contributors-url]: https://github.com/evmjunkie/sweeper-escape/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/evmjunkie/sweeper-escape.svg?style=for-the-badge
[forks-url]: https://github.com/evmjunkie/sweeper-escape/network/members
[stars-shield]: https://img.shields.io/github/stars/evmjunkie/sweeper-escape.svg?style=for-the-badge
[stars-url]: https://github.com/evmjunkie/sweeper-escape/stargazers
[issues-shield]: https://img.shields.io/github/issues/evmjunkie/sweeper-escape.svg?style=for-the-badge
[issues-url]: https://github.com/evmjunkie/sweeper-escape/issues
[license-shield]: https://img.shields.io/github/license/evmjunkie/sweeper-escape.svg?style=for-the-badge
[license-url]: https://github.com/evmjunkie/sweeper-escape/blob/master/LICENSE.txt

[Python]: https://img.shields.io/badge/python-000000?style=for-the-badge&logo=python&logoColor=white
[PythonUrl]: https://python.org/
