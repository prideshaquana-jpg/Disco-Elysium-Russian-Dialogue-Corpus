# Disco-Elysium-Russian-Dialogue-Corpus
Complete Russian dialogue dataset for Disco Elysium video game.  Contains 271K+ character dialogues with metadata, ready for NLP  and machine learning research. Полный датасет диалогов Disco  Elysium на русском языке.

# Disco Elysium Russian Dialogue Corpus

Полный датасет диалогов видеоигры Disco Elysium на русском языке.

## Содержание

- **271,000+** диалоговых реплик
- **47** уникальных персонажей  
- **Метаданные** о сценах и контексте
- **Готов для NLP** и машинного обучения

## Использование

from datasets import load_dataset
dataset = load_dataset("uvowaidef/Disco_Elysium_Russian_Dialogue_Corpus")

text

## Структура данных

{
"character": "Harry Du Bois",
"dialogue": "Русский текст диалога",
"character_ru": "Гарри Дю Буа",
"context": "описание сцены"
}

text

## Источник данных

Основан на официальной русской локализации игры Disco Elysium (2020).

## Лицензия

CC-BY-4.0

## Цитирование

@dataset{DiscoRusDialogue2025,
author = {prideshaquana-jpg},
title = {Disco Elysium Russian Dialogue Corpus},
year = {2025},
url = {https://github.com/prideshaquana-jpg/Disco-Elysium-Russian-Dialogue-Corpus}
}
