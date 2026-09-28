# Антибот

## Пререквизиты

Используется Python `3.14.5`. Используемые библиотеки и их версии указаны в `requirements.txt`.

## Запуск

Необходимо иметь пакетный менеджер `uv`.

```bash
uv python install 3.14.5
uv venv --python 3.14.5
source .venv/bin/activate
uv pip install -r requirements.txt
```

Далее необходимо запустить Jupyter:
```bash
python -m jupyterlab solution.ipynb
```
и исполнить все ячейки с помощью `run all`. 
   
После этого результат будет находиться в файле `submission.csv`.

## Дополнительная информация

Описание задачи содержится в файле `task.md`.

Описание решения содержится в файле `MODEL.md`.