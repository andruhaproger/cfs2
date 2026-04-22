# Лабораторная работа 2 - Вариант на тройку

### Выполнил: Прокофьев А.Р. - М8О-401Б-22

В данной работе используется локальный сервер Ollama и модель Qwen2.5:0.5B.
Цель работы — отправить запросы к LLM по HTTP, получить ответы модели и сохранить результаты инференса в таблицу.

## Стек
- Ollama
- Qwen2.5:0.5B
- Python
- requests
- pandas

## Установка

```bash
git clone https://github.com/andruhaproger/cfs2
cd cfs2
python -m venv .venv

.venv\Scripts\Activate.ps1

python -m pip install -r requirements.txt

ollama pull qwen2.5:0.5b
```
## Запуск
1. Убедиться, что Ollama запущена локально.
2. Открыть lab2.ipynb в VS Code или Jupyter Notebook.
3. Последовательно выполнить все ячейки ноутбука.
4. После выполнения будет создан файл inference_report.csv.

## Результат
В результате работы формируется отчёт инференса с двумя столбцами:
- запрос к LLM
- соответствующий ответ модели
