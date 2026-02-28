# Генерация текста LSTM по произведениям Достоевского

Pet-проект по символьной генерации текста на LSTM с обучением на литературном корпусе.

## Что сделано

- Подготовка словаря/токенов для символьной модели.
- Реализация CharRNN на базе LSTM.
- Генерация текста после обучения и загрузки весов.

## Стек

- Python
- PyTorch
- NumPy
- Jupyter Notebook

## Как запустить

`ash
python -m venv .venv
.venv\Scripts\activate
pip install -r requirements.txt
jupyter notebook ltsm_Dostoevskiy.ipynb
`

## Результаты

Построена и обучена RNN/LSTM-модель для генерации стилизованного текста.

## Чему научился

- Работать с последовательностями и скрытыми состояниями LSTM.
- Контролировать проблему взрывающихся градиентов (gradient clipping).

## Ограничения и что улучшить

- Добавить temperature sampling и сравнение с GRU/Transformer baseline.

## Автор

Арсений Козлов - [github.com/ArseniyKoz](https://github.com/ArseniyKoz)
