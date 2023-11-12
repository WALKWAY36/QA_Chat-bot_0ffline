# Приватный чат-бот
Бесплатный чат бот, который не требует подключения к интернету

Архитектура чат бота:
<img width="930" alt="SCR-20230917-qbto" src="How_do.png">

# Пользование:
1.клонировать репозторий
2.Загрузить модель(например, ggml-gpt4all-j-v1.3-groovy.bin) https://huggingface.co/orel12/ggml-gpt4all-j-v1.3-groovy/tree/main
3.В проекте добавить папку models и туда закинуть загруженную модель
4.Добавить папку source_documents и туда загрузить необходимые вам файлы (пока что только .pdf)
5.Запустить сначала ingest.py а затем privateGPT.py
6.Вводите вопрос, инетерсующий вас из вашего файла .pdf , он переводится на англ. для более лучшей работы модели, получаете ответ на русском.
7.Если будут вопросы, пишите https://vk.com/walkway36 или @WALKWAY36 в тг.

## Технический стек:
1. Langchain
2. GPT4all LLM
3. Sentence Transformer embeddings
3. Chroma Vector DataBase
4. Python 3.10 +
