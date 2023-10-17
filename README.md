# Natural-Language-Processing

### 7. Сверточные нейронные сети для анализа текста

#### Задание<br>
Берем отызывы за лето (из архива с материалами или предыдущего занятия)<br>
1. Учим conv сеть для классификации
2. Рассмотреть 2-а варианта сеточек:
2.1 Инициализировать tf.keras.layers.Embedding предобученными векторами взять к примеру с https://rusvectores.org/ru/
2.2 Инициализировать слой tf.keras.layers.Embedding по умолчанию (ну то есть вам ничего не делать с весами)

Сравнить две архитектуры с предобученными весами и когда tf.keras.layers.Embedding обучается сразу со всей сеточкой, что получилось лучше
