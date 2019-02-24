# Задача 46
### Задача поиска символов в текстах

* Суть: В простейшем случае эта задача сводится к задаче Sequence Labeling на размеченной выборке. Сложность заключается в получении достаточного объёма обучающих данных, то есть требуется по имеющейся небольшой экспертной разметке получить выборку большего размера (автоматически путём поиска закономерностей или же путём составления несложной и качественной инструкции для разметки, например, в Толоке). Наличие разметки позволяет начать эксперименты с подбором оптимальной модели, здесь могут быть интересны разнообразные нейросетевые архитектуры (BiLSTM, Transformer и т.п.).

* Данные: Словарь символов , Размеченные художественные тексты

* Литература: http://www.machinelearning.ru/wiki/images/0/05/Mmta18-rnn.pdf

* Базовый алгоритм: HMM, RNN

* Решение: Предлагается сравнить работы нескольких state-of-the-art алгоритмов. Предложить метрику качества классификатора для символов (символ/не символ). Определить применимость методов.

* Новизна: Предлагаемый подход к анализу текста используется экспертами в ручном режиме и не был автоматизирован
