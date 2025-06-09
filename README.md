# prompt-injections

Этот репозиторий содержит набор инструментов для тестирования устойчивости русскоязычных больших языковых моделей (LLM) к различным типам промпт-инъекций. Проект включает скрипты для генерации примеров атак, их локализации на русский язык, а также пайплайны для проведения экспериментов с моделями OpenAI и визуализации результатов.

## Содержание

/pipeline - Jupyter-ноутбуки с пайплайном тестирования моделей

ruPINT.ipynb - Пайплайн для тестирования моделей на устойчивость к промпт-инъекциям

LICENSE - лицензия кода (MIT)

## Ссылки

Оригинальный датасет на Kaggle: https://www.kaggle.com/datasets/dmitrydruchinin/direct-prompt-injections-in-russian

Оригинальный датасет на Hugging Face: https://huggingface.co/datasets/dmtrdr/russian_prompt_injections

## License

Код: MIT License (см. LICENSE)

Данные: CC BY-NC 4.0

Репозиторий предоставляется исключительно для некоммерческого академического и исследовательского использования.

## Цитирование

Если вы используете этот репозиторий в своих исследованиях, пожалуйста, укажите:

@misc{druchinin2025prompt,
  author = {Druchinin, Dmitry},
  title = {Prompt-Injections: Benchmarking Russian LLM Security},
  year = {2025},
  howpublished = {\url{https://github.com/Dmtr-Dr/prompt-injections}}
}
