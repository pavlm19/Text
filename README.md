# Text
Text calssification

Проверка использования различных методов машинного обучения для классификации текстов:
1. RNN - рекурентная нейронная сеть
2. CNN - сверточная нейронная сеть
3. LSTM - нейронная сеть долгой краткосрочной памяти (улучшенная RNN)

https://www.kaggle.com/code/aviskumar/imdb-dataset/data - ссылка на датасет (из-за большого размера, нельзя загрузить)

Были произведены тесты по сравнению сетей для классификации комметариев к фильмам 
были обучены 2 сети: RNN (LSTM) и CNN

Обе сети показали приближенные друг к другу показатели по метрике F1 (метрика показывает среднее значение между ошибками первого и второго рода)
Для улучшения качества предсказания впоследствии была произведена предобработка датасета, путем иницилизации эмбеддингов слов
