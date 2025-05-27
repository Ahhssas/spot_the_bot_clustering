# spot_the_bot_clustering

Данный репозиторий содержит материалы для эксперимента по детекции AI-сгенерированных текстов с использованием двух методов кластеризации. В рамках эксперимента тексты были преобразованы в векторное представление и кластеризованы, после чего по результатам кластеризации были извлечены метрики, использованные для обучения классификаторов.

## в папке sets лежат выборки с полученными в процессе кластеризации признаками:

### кластеризация K-means:
- [features_train_k_means_20.csv](https://github.com/Ahhssas/spot_the_bot_clustering/blob/main/sets/features_train_k_means_20.csv) и [features_test_k_means_20.csv](https://github.com/Ahhssas/spot_the_bot_clustering/blob/main/sets/features_test_k_means_20.csv) -- выборки текстов с одной длиной (20 тыс слов в каждом)
- [features_train_k_means.csv](https://github.com/Ahhssas/spot_the_bot_clustering/blob/main/sets/features_train_k_means.csv) и [features_test_k_means.csv](https://github.com/Ahhssas/spot_the_bot_clustering/blob/main/sets/features_test_k_means.csv) -- выборки текстов в диапазоне от 500 до 30 тыс слов

### кластеризация HDBSCAN:
- [hdbscan_train.csv](https://github.com/Ahhssas/spot_the_bot_clustering/blob/main/sets/hdbscan_train.csv) и [hdbscan_test.csv](https://github.com/Ahhssas/spot_the_bot_clustering/blob/main/sets/hdbscan_test.csv) -- тексты разной длины для HBDSCAN

### ноутбуки:
- 
