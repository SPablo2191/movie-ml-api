# MOVIE EXPERIENCE

## Introduction:

Bienvenido al proyecto de coderhouse para el manejo de API´s publicas empleando la siguiente [api](https://www.themoviedb.org/)

## Table of content:

- [Author](#author👀)
- [Technologies](#technologies-👨‍💻)
- [Environments](#environments-💻)
- [Configuration](#configuration-🤖)

## Author👀

- [Pablo Sandoval](https://github.com/SPablo2191)

## Technologies 👨‍💻

![Pandas](https://img.shields.io/badge/Pandas-2.1.2-brightgreen.svg)
![requests](https://img.shields.io/badge/requests-2.31.0-blue.svg)

## Environments 💻

![Linux](https://img.shields.io/badge/Linux-compatible-green)
![Windows](https://img.shields.io/badge/Windows-compatible-green)

## Configuration 🤖
To use the project locally, you need to follow these steps:

1) Enter the following commands in the console:

```bash
python3 -m venv [nameOfTheVirtualEnvironment]
```

This command will create a virtual environment for you to later import packages there. To activate it, use the following command:

```bash
source nameOfTheVirtualEnvironment/bin/activate
```
NOTE: In case you are working on Windows, the virtual environment is created with scripts, so you need to activate the virtual environment as follows:

```bash
nameOfTheVirtualEnvironment\Scripts\activate.bat
```
And to deactivate it (in both cases), use:

```bash
deactivate
```

2) Then run the following command to obtain the packages used in the API:

```bash
pip install -r requirements>dev.txt
```
3) After that, you have to create a .env file with the following fields:
```json
API_KEY=[api key value]
API_URL= https://api.themoviedb.org
LANGUAGE = [language value]
API_VERSION = [version value]
```

4) Run the code in the code-blocks!


