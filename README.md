# prompt-injections

[![GitHub stars](https://img.shields.io/github/stars/Dmtr-Dr/prompt-injections?style=social)](https://github.com/Dmtr-Dr/prompt-injections/stargazers)  
[![License](https://img.shields.io/github/license/Dmtr-Dr/prompt-injections)](LICENSE)  
[![Hugging Face Dataset](https://img.shields.io/badge/HuggingFace-dmtrdr%2Frussian_prompt_injections-orange?logo=huggingface)](https://huggingface.co/datasets/dmtrdr/russian_prompt_injections)  
[![Kaggle Dataset](https://img.shields.io/badge/Kaggle-dmitrydruchinin%2Fdirect--prompt--injections--in--russian-blue?logo=kaggle)](https://www.kaggle.com/datasets/dmitrydruchinin/direct-prompt-injections-in-russian)  
[![Python](https://img.shields.io/badge/python-3.8%2B-blue?logo=python)](https://www.python.org/)  

Этот репозиторий содержит набор инструментов для тестирования устойчивости русскоязычных больших языковых моделей (LLM) к различным типам промпт-инъекций. Проект включает скрипты для генерации примеров атак, их локализации на русский язык, а также пайплайны для проведения экспериментов с моделями OpenAI и визуализации результатов.

---

## Содержание
- **/pipeline** – Jupyter-ноутбуки с пайплайном тестирования моделей  
- **ruPINT.ipynb** – Пайплайн для тестирования моделей на устойчивость к промпт-инъекциям  
- **LICENSE** – лицензия кода (MIT)  

---

## Ссылки
- **Kaggle:** [direct-prompt-injections-in-russian](https://www.kaggle.com/datasets/dmitrydruchinin/direct-prompt-injections-in-russian)  
- **Hugging Face:** [russian_prompt_injections](https://huggingface.co/datasets/dmtrdr/russian_prompt_injections)  

---

## License
- **Код:** MIT License ([LICENSE](LICENSE))  
- **Данные:** CC BY-NC 4.0 ([data/LICENSE](data/LICENSE))  

_Репозиторий предоставляется исключительно для некоммерческого академического и исследовательского использования._

---

## Цитирование
Если вы используете этот репозиторий в своих исследованиях, пожалуйста, укажите:

```bibtex
@misc{druchinin2025prompt,
  author       = {Druchinin, Dmitry},
  title        = {Prompt-Injections: Benchmarking Russian LLM Security},
  year         = {2025},
  howpublished = {\url{https://github.com/Dmtr-Dr/prompt-injections}}
}
