[![CI](https://github.com//ai-forever/gigachain/actions/workflows/check_diffs.yml/badge.svg)](https://github.com//ai-forever/gigachain/actions/workflows/check_diffs.yml)
[![Downloads](https://static.pepy.tech/badge/gigachain/month)](https://pepy.tech/project/gigachain)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

<br />
<div align="center">

  <a href="https://github.com/ai-forever/gigachain">
    <img src="docs/static/img/logo.png" alt="Logo" width="80" height="80">
  </a>

  <h1 align="center">🦜️🔗 Клон GigaChain</h1>

  <p align="center">
    Библиотека для разработки LangChain-style приложений на русском языке с поддержкой GigaChat
    <br />
    <a href="https://github.com/ai-forever/gigachain/issues">Создать issue</a>
    ·
    <a href="https://developers.sber.ru/docs/ru/gigachat/overview">Документация GigaChat</a>
  </p>
</div>

## Примечания:
У нас есть два ноутбука - "ChromaLoad.ipynb" - для создания базы данных ChromaDB и "UseDB.ipynb" - для использования существующей базы. Они находятся в директории notebooks.
### Для ноутбука создания БД "ChomaLoad.ipynb":
Файлы для добавления в базу находится в google drive в папке 'IT_Purple_Hack/Text_version/'. Чтобы все заработало, нужно положить папку Text_version в ту директорию, которую вы указали как **base_dir**.
Файлы "FAQ_full.csv" и "url_mapping.csv" находятся в репозитории и пути на них должны автоматически определиться когда вы клонируете patsayevchain.
### Для ноутбука использования БД "UseDB.ipynb":
Нужно скачать базу данных с google drive. Она находится в папке 'IT_Purple_Hack/chroma'. Эту папку chroma необходимо подать на вход как persist_directory в строчке db = Chroma(persist_directory=persist_directory, embedding=embeddings, collection_name="Collection1").