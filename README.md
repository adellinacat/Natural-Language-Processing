# Natural-Language-Processing

#### 3. Embedding Word2vec Fasttext
Задача поиск похожих по эмбеддингам

Скачиваем датасет (источник): положительные, отрицательные.

или можно через ноутбук

!wget https://www.dropbox.com/s/fnpq3z4bcnoktiv/positive.csv?dl=0
!wget https://www.dropbox.com/s/r6u59ljhhjdg6j0/negative.csv?dl=0

рабочие ссылки с твитами
https://disk.yandex.ru/i/v5HM-ENiGXZVpQ
https://disk.yandex.ru/i/koR5eMCToCZS2Q

В связи с удалением даных можно взять другой датасет, к примеру

!wget https://github.com/ods-ai-ml4sg/proj_news_viz/releases/download/data/gazeta.csv.gz

# пример работы с ним 
from corus import load_ods_gazeta
path = 'gazeta.csv.gz'
records = load_ods_gazeta(path)
next(records)
что надо сделать
1. объединить в одну выборку
2. на основе word2vec/fasttext слоя Embedding реализовать метод поиска ближайших твитов
(на вход метода должен приходить запрос (какой-то твит, вопрос) и количество вариантов вывода к примеру 5-ть, ваш метод должен возвращать 5-ть ближайших твитов к этому запросу)
3. Проверить насколько хорошо работают подходы
