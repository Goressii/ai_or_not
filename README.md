Решение соревнования по классификации изображений на сгенерированные и настоящие.

Было использовано две модели, ноутбуки с обучением которых можно найти в этом репозитории. 
В случае с convnext, обучение происходило сразу на целевую задачу. 
А resnet-152 использовался для получения эмбедингов изображений, на которых в дальнейшем обучался XGBoost.

Результаты на приватном наборе данных: accuracy = 1.0, log_loss = 0.02581
